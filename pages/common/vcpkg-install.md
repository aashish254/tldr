# vcpkg-install

> Build and install one or more packages into the vcpkg environment (classic mode) or the manifest's installed tree.
> More information: <https://learn.microsoft.com/en-us/vcpkg/commands/install>.

- Install one or more packages for the default triplet:

`vcpkg install {{package1 package2 ...}}`

- Install a package for a specific target triplet, in `package:triplet` form:

`vcpkg install {{package}}:{{triplet}}`

- Install using the latest upstream sources rather than the pinned version:

`vcpkg install {{package}} --head`

- Show what would be built and installed without actually doing it:

`vcpkg install {{package}} --dry-run`

- Clean buildtrees, packages and downloads after building each package to save disk space:

`vcpkg install {{package}} --clean-after-build`

- Force classic mode even if a manifest file is found in the current directory:

`vcpkg install {{package}} --classic`
