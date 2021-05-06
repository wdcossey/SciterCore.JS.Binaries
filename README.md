## SciterCore.JS.Binaries
Package containing Sciter *JS* binaries for Windows, MacOS and Linux.

Sciter.JS - `Sciter` with `QuickJS` on board instead of `TIScript`

[![Build Status](https://dev.azure.com/wdcossey/SciterCore/_apis/build/status/SciterCore.JS.Binaries?branchName=main)](https://dev.azure.com/wdcossey/SciterCore/_build/latest?definitionId=15&branchName=main)
[![NuGet](https://img.shields.io/nuget/v/SciterCore.JS.Binaries)](https://www.nuget.org/packages/SciterCore.JS.Binaries/)

Binaries are automatically resolved for the target configuration (i.e `x86`, `x64` and `AnyCPU`)

| OS              | Architecture   | FileName              | 
| --------------- | ---------------| --------------------- | 
| Windows         | `x86`          | `sciter.dll`          | 
| Windows         | `x64`          | `sciter.dll`          | 
| MacOS           | `x64`          | `sciter-osx-64.dylib` | 
| Linux           | `x64`          | `libsciter-gtk.so`    | 

### ⚠️.Net Framework 4.x / XamarinMac
There was an issue with the `.targets` file for `SciterCore.JS.Binaries` with versions `<` `4.4.7.3`.

If you are targeting `.Net Framework 4.x` or `XamarinMac` and are going to use a version `<` `4.4.7.3` check for packages ending with 
`-windows` (marked as `prerelease`) to get the correct binaries bundled with your projects.

i.e `4.4.7.2-windows`