# gr-bladeRF

GNU Radio source and sink blocks for bladeRF devices.

## bladeRF wiki

* [bladeRF wiki](https://github.com/Nuand/bladeRF/wiki)

## Installation

Build from source

    git clone https://github.com/Vincenque/gr-bladeRF
    cd gr-bladeRF
    git pull https://github.com/Vincenque/gr-bladeRF.git main-with-fixes 
    mkdir build
    cd build
    cmake ..
    make -j4
    sudo make install

## GNURadio-Companion Examples
Run FM-receiver example:

    cd 
    gnuradio-companion gr-bladeRF/apps/fm_receiver.grc

## Run on Raspberry
   
   [How to install gr-bladeRF on Raspberry Pi 4
](raspberry/)



