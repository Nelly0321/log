# log
[main] Configuring project: _vcpkg 
[proc] Executing command: /opt/local/bin/cmake --no-warn-unused-cli -DCMAKE_TOOLCHAIN_FILE=D:/Users/NellyVardanyan/vcpkg/scripts/buildsystems/vcpkg.cmake -DCMAKE_TOOLCHAIN_FILE:STRING=/Users/NellyVardanyan/vcpkg/scripts/buildsystems/vcpkg.cmake -DCMAKE_EXPORT_COMPILE_COMMANDS:BOOL=TRUE -DCMAKE_BUILD_TYPE:STRING=Debug -DCMAKE_C_COMPILER:FILEPATH=/usr/bin/clang -DCMAKE_CXX_COMPILER:FILEPATH=/usr/bin/clang++ -S/Users/NellyVardanyan/Documents/ACA/_vcpkg -B/Users/NellyVardanyan/Documents/ACA/_vcpkg/build -G Ninja
[cmake] Not searching for unused variables given on the command line.
[cmake] -- Running vcpkg install
[cmake] Detecting compiler hash for triplet arm64-osx...
[cmake] The following packages will be removed:
[cmake]     eigen3:arm64-osx
[cmake]     libjpeg-turbo:arm64-osx
[cmake]     liblzma:arm64-osx
[cmake]     libpng:arm64-osx
[cmake]     tiff:arm64-osx
[cmake]     vcpkg-get-python-packages:arm64-osx
[cmake]     zlib:arm64-osx
[cmake] The following packages will be rebuilt:
[cmake]   * vcpkg-cmake[core]:arm64-osx -> 2022-01-19 -- /Users/NellyVardanyan/vcpkg/buildtrees/versioning_/versions/vcpkg-cmake/b7c050fe60f91dcedef6d87a3f87584151bf8aee
[cmake]   * vcpkg-cmake-config[core]:arm64-osx -> 2022-02-06 -- /Users/NellyVardanyan/vcpkg/buildtrees/versioning_/versions/vcpkg-cmake-config/24dc7dfc704406e9f745f033643dc25f56e4ca18
[cmake] The following packages will be built and installed:
[cmake]     fmt[core]:arm64-osx -> 8.1.1#1 -- /Users/NellyVardanyan/vcpkg/buildtrees/versioning_/versions/fmt/602d9743b7957c9e82a06d0e81d58637c6df5222
[cmake] Additional packages (*) will be modified to complete this operation.
[cmake] Removing 1/12 eigen3:arm64-osx
[cmake] Elapsed time to handle eigen3:arm64-osx: 125.9 ms
[cmake] Removing 2/12 vcpkg-get-python-packages:arm64-osx
[cmake] Elapsed time to handle vcpkg-get-python-packages:arm64-osx: 5.762 ms
[cmake] Removing 3/12 libpng:arm64-osx
[cmake] Elapsed time to handle libpng:arm64-osx: 10.26 ms
[cmake] Removing 4/12 tiff:arm64-osx
[cmake] Elapsed time to handle tiff:arm64-osx: 8.568 ms
[cmake] Removing 5/12 libjpeg-turbo:arm64-osx
[cmake] Elapsed time to handle libjpeg-turbo:arm64-osx: 13.07 ms
[cmake] Removing 6/12 liblzma:arm64-osx
[cmake] Elapsed time to handle liblzma:arm64-osx: 11.31 ms
[cmake] Removing 7/12 zlib:arm64-osx
[cmake] Elapsed time to handle zlib:arm64-osx: 4.679 ms
[cmake] Removing 8/12 vcpkg-cmake-config:arm64-osx
[cmake] Elapsed time to handle vcpkg-cmake-config:arm64-osx: 2.435 ms
[cmake] Removing 9/12 vcpkg-cmake:arm64-osx
[cmake] Elapsed time to handle vcpkg-cmake:arm64-osx: 4.393 ms
[cmake] Restored 0 package(s) from /Users/NellyVardanyan/.cache/vcpkg/archives in 573.8 us. Use --debug to see more details.
[cmake] Installing 10/12 vcpkg-cmake-config:arm64-osx...
[cmake] Building vcpkg-cmake-config[core]:arm64-osx...
[cmake] warning: -- Using community triplet arm64-osx. This triplet configuration is not guaranteed to succeed.
[cmake] -- [COMMUNITY] Loading triplet configuration from: /Users/NellyVardanyan/vcpkg/triplets/community/arm64-osx.cmake
[cmake] -- Installing port from location: /Users/NellyVardanyan/vcpkg/buildtrees/versioning_/versions/vcpkg-cmake-config/24dc7dfc704406e9f745f033643dc25f56e4ca18
[cmake] -- Installing: /Users/NellyVardanyan/vcpkg/packages/vcpkg-cmake-config_arm64-osx/share/vcpkg-cmake-config/vcpkg_cmake_config_fixup.cmake
[cmake] -- Installing: /Users/NellyVardanyan/vcpkg/packages/vcpkg-cmake-config_arm64-osx/share/vcpkg-cmake-config/vcpkg-port-config.cmake
[cmake] -- Installing: /Users/NellyVardanyan/vcpkg/packages/vcpkg-cmake-config_arm64-osx/share/vcpkg-cmake-config/copyright
[cmake] -- Performing post-build validation
[cmake] Stored binary cache: "/Users/NellyVardanyan/.cache/vcpkg/archives/a8/a81784d155986ed0e4095edd4fb00ee617993b022e0036964eb9f70661795895.zip"
[cmake] Elapsed time to handle vcpkg-cmake-config:arm64-osx: 35.61 ms
[cmake] Installing 11/12 vcpkg-cmake:arm64-osx...
[cmake] Building vcpkg-cmake[core]:arm64-osx...
[cmake] warning: -- Using community triplet arm64-osx. This triplet configuration is not guaranteed to succeed.
[cmake] -- [COMMUNITY] Loading triplet configuration from: /Users/NellyVardanyan/vcpkg/triplets/community/arm64-osx.cmake
[cmake] -- Installing port from location: /Users/NellyVardanyan/vcpkg/buildtrees/versioning_/versions/vcpkg-cmake/b7c050fe60f91dcedef6d87a3f87584151bf8aee
[cmake] -- Installing: /Users/NellyVardanyan/vcpkg/packages/vcpkg-cmake_arm64-osx/share/vcpkg-cmake/vcpkg_cmake_configure.cmake
[cmake] -- Installing: /Users/NellyVardanyan/vcpkg/packages/vcpkg-cmake_arm64-osx/share/vcpkg-cmake/vcpkg_cmake_build.cmake
[cmake] -- Installing: /Users/NellyVardanyan/vcpkg/packages/vcpkg-cmake_arm64-osx/share/vcpkg-cmake/vcpkg_cmake_install.cmake
[cmake] -- Installing: /Users/NellyVardanyan/vcpkg/packages/vcpkg-cmake_arm64-osx/share/vcpkg-cmake/vcpkg_cmake_get_vars.cmake
[cmake] -- Installing: /Users/NellyVardanyan/vcpkg/packages/vcpkg-cmake_arm64-osx/share/vcpkg-cmake/cmake_get_vars
[cmake] -- Installing: /Users/NellyVardanyan/vcpkg/packages/vcpkg-cmake_arm64-osx/share/vcpkg-cmake/cmake_get_vars/CMakeLists.txt
[cmake] -- Installing: /Users/NellyVardanyan/vcpkg/packages/vcpkg-cmake_arm64-osx/share/vcpkg-cmake/vcpkg-port-config.cmake
[cmake] -- Installing: /Users/NellyVardanyan/vcpkg/packages/vcpkg-cmake_arm64-osx/share/vcpkg-cmake/copyright
[cmake] -- Performing post-build validation
[cmake] Stored binary cache: "/Users/NellyVardanyan/.cache/vcpkg/archives/cf/cf637d87ceccb346d9fd0fef13dd3325b567ac522e7662c83b701de0b5b9696f.zip"
[cmake] Elapsed time to handle vcpkg-cmake:arm64-osx: 29.86 ms
[cmake] Installing 12/12 fmt:arm64-osx...
[cmake] Building fmt[core]:arm64-osx...
[cmake] warning: -- Using community triplet arm64-osx. This triplet configuration is not guaranteed to succeed.
[cmake] -- [COMMUNITY] Loading triplet configuration from: /Users/NellyVardanyan/vcpkg/triplets/community/arm64-osx.cmake
[cmake] -- Installing port from location: /Users/NellyVardanyan/vcpkg/buildtrees/versioning_/versions/fmt/602d9743b7957c9e82a06d0e81d58637c6df5222
[cmake] -- Downloading https://github.com/fmtlib/fmt/archive/8.1.1.tar.gz -> fmtlib-fmt-8.1.1.tar.gz...
[cmake] -- Extracting source /Users/NellyVardanyan/vcpkg/downloads/fmtlib-fmt-8.1.1.tar.gz
[cmake] -- Applying patch fix-write-batch.patch
[cmake] -- Applying patch fix-invalid-command.patch
[cmake] -- Using source at /Users/NellyVardanyan/vcpkg/buildtrees/fmt/src/8.1.1-11f8359597.clean
[cmake] -- Found external ninja('1.11.1').
[cmake] -- Configuring arm64-osx-dbg
[cmake] -- Configuring arm64-osx-rel
[cmake] -- Building arm64-osx-dbg
[cmake] -- Building arm64-osx-rel
[cmake] -- Installing: /Users/NellyVardanyan/vcpkg/packages/fmt_arm64-osx/share/fmt/copyright
[cmake] -- Fixing pkgconfig file: /Users/NellyVardanyan/vcpkg/packages/fmt_arm64-osx/lib/pkgconfig/fmt.pc
[cmake] -- Fixing pkgconfig file: /Users/NellyVardanyan/vcpkg/packages/fmt_arm64-osx/debug/lib/pkgconfig/fmt.pc
[cmake] -- Installing: /Users/NellyVardanyan/vcpkg/packages/fmt_arm64-osx/share/fmt/usage
[cmake] -- Performing post-build validation
[cmake] Stored binary cache: "/Users/NellyVardanyan/.cache/vcpkg/archives/54/54f11b3d1416561a52f9d6f3a771bdc0de6160fae704b13816dc76872456f088.zip"
[cmake] Elapsed time to handle fmt:arm64-osx: 6.538 s
[cmake] Total install time: 6.79 s
[cmake] The package fmt provides CMake targets:
[cmake] 
[cmake]     find_package(fmt CONFIG REQUIRED)
[cmake]     target_link_libraries(main PRIVATE fmt::fmt)
[cmake] 
[cmake]     # Or use the header-only version
[cmake]     find_package(fmt CONFIG REQUIRED)
[cmake]     target_link_libraries(main PRIVATE fmt::fmt-header-only)
[cmake] 
[cmake] -- Running vcpkg install - done
[cmake] -- The CXX compiler identification is AppleClang 14.0.0.14000029
[cmake] -- Detecting CXX compiler ABI info
[cmake] -- Detecting CXX compiler ABI info - done
[cmake] -- Check for working CXX compiler: /usr/bin/clang++ - skipped
[cmake] -- Detecting CXX compile features
[cmake] -- Detecting CXX compile features - done
[cmake] -- Configuring done
[cmake] -- Generating done
[cmake] -- Build files have been written to: /Users/NellyVardanyan/Documents/ACA/_vcpkg/build
