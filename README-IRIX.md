# POV-Ray - The Persistence of Vision Raytracer

Fork with adjustments for IRIX 6.5.x / GCC 9 / SGUG-RSE.

- Some boost calls removed and replaced with std c++11 due to segfaults.

## How to build on IRIX with GCC 9.2

$ cd unix
$ ./prebuild.sh
$ mkdir build && cd build
$ ../configure COMPILED_BY="flexion on Origin300" --with-boost=/usr/sgug/include/boost --with-boost-libdir=/usr/sgug/lib32 --disable-io-restrictions --prefix=/usr/sgug 

