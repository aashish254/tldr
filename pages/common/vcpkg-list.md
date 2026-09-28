# vcpkg-list

> List libraries that are currently installed in the vcpkg environment.
> More information: <https://learn.microsoft.com/en-us/vcpkg/commands/list>.

- List all installed packages:

`vcpkg list`

- List only installed packages matching a filter pattern:

`vcpkg list {{filter}}`

- List installed packages without truncating long descriptions:

`vcpkg list {{filter}} --x-full-desc`
