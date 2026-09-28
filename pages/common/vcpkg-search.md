# vcpkg-search

> Search for packages available to be built in the registry.
> More information: <https://learn.microsoft.com/en-us/vcpkg/commands/search>.

- List every package available in the registry:

`vcpkg search`

- Search for packages whose name or text matches a pattern:

`vcpkg search {{pattern}}`

- Search without truncating long descriptions:

`vcpkg search {{pattern}} --x-full-desc`
