# STM32_test1

An eclipse project for testing purposes. On a properly setup environment it will build successfully.
For a constant and reliable build environment use my Docker image petoknm/stm32builder

Build instructions:
-------------------

For building the debug version of the project just run this command
docker run --rm -v /path/to/project/test1/:/src -w=/src/Debug petoknm/stm32builder make -j4

The release version is not yet supported.
