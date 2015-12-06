# YGOPro Library Builder#

For multiplayer ygopro servers that utilize alternative [`[gframe]`](https://github.com/Fluorohydride/ygopro) implementation that are specialized for server side use, and require [`[ygopro-core]`](https://github.com/Fluorohydride/ygopro-core) as an external library of some forum (`*.dll`, `*.lib`, `*.so`).

### Usage
`git submodule update --force` to pull in [`[ygopro-core]`](https://github.com/Fluorohydride/ygopro-core)'s latest source code. Open `build/ygo.sln`,  set the project to `Release`, build the project, (it will only work in release atm) it will produce `bin\release\ocgcore.dll`. Its suggested you only build for `Win32` and not `x64`. 
    
### Compatible Servers
 - [YGOSharp by @IceYGO](https://github.com/IceYGO/ygosharp)
 - [YGOCore by @Buttys & SalvationDevelopment](https://github.com/SalvationDevelopment/YGOCore)
 - [JYGOServer by @garymabin](https://github.com/garymabin/JYGOServer)

### Goals
 - Set up build system for Linux based Servers.
 - Set up build system for MacOs based Servers.
 - Create test framework for [`[ygopro-core]`](https://github.com/Fluorohydride/ygopro-core).

###Contribution
Currently the project is highly active. If you want to make an improvement detail the *why* of the improvement first in a new issue. If you find this project useful please leave a thank you in issues.

### Special Thanks
  - @soarqin
  - @Buttys