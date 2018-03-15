# conan-<name>

![<name> image](/images/conan-<name>.png)

[![Download](https://api.bintray.com/packages/conan-community/conan/<name>%3Aconan/images/download.svg)](https://bintray.com/conan-community/conan/<name>%3Aconan/_latestVersion)
[![Build status](https://ci.appveyor.com/api/projects/status/jyeh443gn0l0f3bi/branch/stable/<version>?svg=true)](https://ci.appveyor.com/project/<appveyor_user>/conan-<name>/branch/stable/<version>)

[Conan.io](https://conan.io) build require package for [<name>](<homepage>) project.

The packages generated with this **conanfile** can be found in [Bintray](https://bintray.com/conan-community/conan/<name>%3Aconan).

## For Users: Use this package

### Basic setup

    $ conan install <name>/<version>@conan/stable

### Project setup

You can use this build require directly from a Conan profile or a *conanfile.txt*.

    [build_requires]
    <name>/<version>@conan/stable

## License

[MIT License](LICENSE)
