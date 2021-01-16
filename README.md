## CMake Premake5 action

### Why cmake?

I just want to use premake5 with [CLion](https://www.jetbrains.com/clion/).


The generated cmake scripts are not good structured but it works with basic project configurations.

## To export CMakeLists.txt

1. Download this repository, extract to [premake module folder](https://github.com/premake/premake-core/wiki/Locating-Scripts) and rename it to `cmake`
2. Put `require('cmake')` into your `premake5.lua`
3. Run `premake5 cmake`
