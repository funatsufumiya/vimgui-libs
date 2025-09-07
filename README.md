## Build

```bash
$ git clone https://github.com/funatsufumiya/cimgui-sokol-starterkit
$ cd cimgui-sokol-starterkit

$ cmake -B build -DCMAKE_BUILD_TYPE=Release -DBUILD_SHARED_LIBS=ON
$ cmake --build build --parallel 8 --config Release
```

## Test example

```bash
$ cmake -B build -DCMAKE_BUILD_TYPE=Debug
$ cmake --build build --parallel 8 --config Debug
$ cmake -B build -DCMAKE_BUILD_TYPE=Release
$ cmake --build build --parallel 8 --config Release
```
