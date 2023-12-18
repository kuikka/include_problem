Pre-reqs
  1. CMake (https://cmake.org/download/)
  2. Ninja (https://github.com/ninja-build/ninja/releases)

Build instructions
  1. Install vcpkg (for vcpkg preset)
    - git clone https://github.com/Microsoft/vcpkg.git
    - vcpkg/bootstrap-vcpkg.[bat|sh]
  2. cmake --preset auto
  3. cmake --preset vcpkg


