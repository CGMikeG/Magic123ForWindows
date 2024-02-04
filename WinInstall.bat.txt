@echo off
echo Installing module...

pip install ./raymarching
pip install ./shencoder
pip install ./freqencoder
pip install ./gridencoder


echo Cloning repository...
git clone https://github.com/NVlabs/nvdiffrast.git
echo Clone complete.

pip install ./nvdiffrast

echo Installation complete.
pause