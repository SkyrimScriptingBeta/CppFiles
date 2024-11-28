# `C++` Files

Mrowr Purr's common C++ files.

## .clang-format

This file configures the formatting rules for the C++ codebase. It uses the Google style as a base and includes customizations such as:
- No tabs, with a tab width and indent width of 4 spaces.
- Column limit set to 100 characters.
- Specific alignment rules for declarations, assignments, and array structures.
- Custom pointer and reference alignment settings.

## .clangd

This file configures additional compile flags for `clangd`, the C++ language server. It adds support for the latest C++ standard and enables C++23 features.

## .gitignore

This file specifies which files and directories should be ignored by Git. It includes:
- Build output directories (`build`).
- Clangd cache and compile commands.
- Xmake build system files.

## CMakeLists.txt

This file defines the build configuration for the project using CMake. It includes:
- Minimum required CMake version.
- Project name and version.
- Executable target definition.
- Required packages and libraries.

## CMakePresets.json

This file defines CMake presets for configuring and building the project. It includes:
- A base preset with common settings like the Ninja generator, binary and install directories, and compiler flags.
- Debug and Release presets that inherit from the base preset and set the build type accordingly.

## LICENSE

This file contains the BSD Zero Clause License, which allows for free use, modification, and distribution of the software without any warranty.

## README.md

This file provides an overview of the project and its files.

## vcpkg-configuration.json

This file configures the vcpkg package manager. It specifies:
- The default registry pointing to the official vcpkg repository.
- An additional registry for custom packages, including `example-library`.

## vcpkg.json

This file defines the project's dependencies for vcpkg. It includes:
- The project name and version.
- A list of dependencies, such as `example-library`.