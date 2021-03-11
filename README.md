# setup-nuget-msbuild-selfhostrun
This GitHub action is a combination of [NuGet/setup-nuget](https://github.com/NuGet/setup-nuget) and [microsoft/setup-msbuild](https://github.com/microsoft/setup-msbuild) intended for use with self hosted Windows based runners.

## Usage

```yml
- name: Setup NuGet & Add msbuild to PATH
  uses: dannevesdantas/setup-nuget-msbuild-selfhostrun@v0.1.0
```

All params of [NuGet/setup-nuget@v1.0.2](https://github.com/NuGet/setup-nuget) and [microsoft/setup-msbuild@v1.0.2](https://github.com/microsoft/setup-msbuild) are also supported!

Default value for the `vswhere-path` param is `C:\Program Files (x86)\Microsoft Visual Studio\Installer`.\
If you would like to provide e diferente one, please specify it. For example:

```yml
- name: Setup NuGet & Add msbuild to PATH
  uses: dannevesdantas/setup-nuget-msbuild-selfhostrun@v0.1.0
    vswhere-path: 'D:\Program Files (x86)\Microsoft Visual Studio\Installer'
```

# License

The scripts and documentation in this project are released under the [MIT License](LICENSE)
