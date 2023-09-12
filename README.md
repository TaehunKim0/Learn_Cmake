Cmake Project Build (Create MSBuild build setting file)
: cmake -S . -B build

Cmake Project Build (Create Ninja Build setting file )
: cmake -S . -B build -G 'Ninja Multi-Config'


[-S] : set cmake source dir (. is current dir)
[-B] : set build dir (build is created dir)
