mini how to:

mbed import https://github.com/architech-boards/mbed-os-example-client-NUCLEO_L476RG.git - version forked
git clone https://github.com/architech-boards/SpwfInterface.git - Copy the SPW-interface foloder into the mbed-os-example-client-NUCLEO_L476RG project

mbed detect
mbed toolchain GCC_ARM
mbed target NUCLEO_L476RG
mbed deploy
mbed compile
