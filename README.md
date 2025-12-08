# POV-Ray - The Persistence of Vision Raytracer

Fork of [POV-Ray v3.8.0-beta.2](https://github.com/POV-Ray/povray) with adjustments for IRIX 6.5.x / GCC 9 / SGUG-RSE.

- Some boost calls removed and replaced with std c++11 due to segfaults.

## How to build on IRIX with GCC 9.2

- $ cd unix
- $ ./prebuild.sh
- $ cd ..
- $ mkdir build && cd build
- $ ../configure COMPILED_BY="YOUR NAME" --with-boost=/usr/sgug/include/boost --with-boost-libdir=/usr/sgug/lib32 --disable-io-restrictions --prefix=/usr/sgug 

## License

As of version v3.7, the source for POV-Ray is licensed under the AGPL3. The documentation is under the
Creative Commons Attribution-Noncommercial-ShareAlike 2.5 license, and support files such
as SDL includes, macros, sample scenes and so forth are under the Creative Commons Attribution-ShareAlike
3.0 Unported License (see each file header for the specific one).
