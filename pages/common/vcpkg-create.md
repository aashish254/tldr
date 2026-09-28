# vcpkg-create

> Generate a starting-point port to package a source code project, which usually requires further edits to build.
> More information: <https://learn.microsoft.com/en-us/vcpkg/commands/create>.

- Download the sources from a URL to hash them and generate a `portfile.cmake` and `vcpkg.json` in a new port folder:

`vcpkg create {{port_name}} {{source_archive_url}}`

- Create a port using a specific filename for the downloaded archive:

`vcpkg create {{port_name}} {{source_archive_url}} {{downloaded_filename.zip}}`
