Notes
=====

1) Build SDL2 using autoconf, not cmake, to get sdl2-config.cmake >:|

```bash
hg clone https://hg.libsdl.org/SDL SDL
cd SDL
mkdir build
cd build
# (if on OSX)
# CC=/where/i/cloned/SDL/build-scripts/gcc-fat.sh ../configure
../configure 
make
sudo make install
```    

