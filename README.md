# NewDivideEngine

## Build

On Windows, configure and build with the `x64-debug` preset from a Visual Studio Developer PowerShell initialized for the x64 toolchain:

```powershell
cmake --preset x64-debug
cmake --build out/build/x64-debug
```

## Tests

Tests are enabled by default through CTest. Run them after configuring and building:

```powershell
ctest --test-dir out/build/x64-debug --output-on-failure
```