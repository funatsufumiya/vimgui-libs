# vimgui-libs

Prebuilt binaries for [vimgui](https://github.com/funatsufumiya/vimgui)

## Build

```bash
$ git clone --depth=1 https://github.com/cimgui/cimgui
$ cd cimgui

$ cmake -B build -DCMAKE_BUILD_TYPE=Debug
$ cmake --build build --parallel 8 --config Debug
$ cmake -B build -DCMAKE_BUILD_TYPE=Release
$ cmake --build build --parallel 8 --config Release

```
