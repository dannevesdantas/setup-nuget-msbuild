# setup-nuget-msbuild-selfhostrun
This GitHub action is a combination of [NuGet/setup-nuget](https://github.com/NuGet/setup-nuget) and [microsoft/setup-msbuild](https://github.com/microsoft/setup-msbuild) for use with self hosted Windows based runners.

## Usage

```yml
- name: Setup NuGet & Add msbuild to PATH
  uses: dannevesdantas/setup-nuget-msbuild-selfhostrun@v0.1.0
```

## Requirements
This GitHub Action is compatible with Windows based runners only.

# License

The scripts and documentation in this project are released under the [MIT License](LICENSE)
