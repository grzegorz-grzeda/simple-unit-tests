# simple-unit-tests
Simple C unit tests CMake facility utilising [`cmocka`](https://cmocka.org/) test library.

## How to use it
Just include this test facility directory in your project and enjoy cmocka functionality.

```cmake
add_subdirectory(${CMAKE_CURRENT_SOURCE_DIR}/<path to this facility>)

add_simple_unit_test(<name> ${CMAKE_CURRENT_SOURCE_DIR}/<unit_test_source>.c <tested_library>)
```
## Copyright
This library was written by Grzegorz Grzęda, and is distributed under MIT Licence. Check the `LICENSE` file for
more details.