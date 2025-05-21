# GNU-Radio
Energy detector and dynamic OFDM allocator OOT blocks

GNU Radio version 3.10

INSTALLING:

1: go to the build/ directory of each gr- file and remove it -> rm -rf build/
2: create a new build directory -> mkdir build
3: move into the build directory -> cd build
4: then just compile and install each block -> 
cmake ..
make
sudo make install
sudo ldconfig
