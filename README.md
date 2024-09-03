# Build and Run

```
conan install . --build=missing
cmake . -DCMAKE_TOOLCHAIN_FILE=build/Release/generators/conan_toolchain.cmake -DCMAKE_BUILD_TYPE=Release
cmake --build . --config Release
```

```
ldd l1_hello_window/l1_hello_window
```