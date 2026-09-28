# vcpkg-remove

> Uninstall previously installed packages from the vcpkg environment.
> More information: <https://learn.microsoft.com/en-us/vcpkg/commands/remove>.

- Remove one or more installed packages:

`vcpkg remove {{package1 package2 ...}}`

- Remove a package installed for a specific target triplet, in `package:triplet` form:

`vcpkg remove {{package}}:{{triplet}}`

- Remove all installed packages whose versions no longer match the built-in registry:

`vcpkg remove --outdated`

- Show what would be removed without actually removing anything:

`vcpkg remove {{package}} --dry-run`

- Also remove dependent packages that were not explicitly specified:

`vcpkg remove {{package}} --recurse`
