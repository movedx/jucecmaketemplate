## Build

`cmake -S . -B build`

`cmake --build build`

## Building Examples

replace "DemoRunner" with the name of the target you wish to build.

`cd libs/juce`

`cmake . -B cmake-build -DJUCE_BUILD_EXAMPLES=ON -DJUCE_BUILD_EXTRAS=ON`

`cmake --build cmake-build --target DemoRunner`


## Test

`cd build`

`ctest`

