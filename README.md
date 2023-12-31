# [**PsModuleGen**](https://www.powershellgallery.com/packages/PsModuleGen/)

 "A PowerShell module generator module"

Helps to easily create a new PowerShell module.

[![CI](https://github.com/alainQtec/PsModuleGen/actions/workflows/CI.yaml/badge.svg)](https://github.com/alainQtec/PsModuleGen/actions/workflows/CI.yaml)
[![Upload artifact from Ubuntu](https://github.com/alainQtec/PsModuleGen/actions/workflows/Upload_Artifact.yaml/badge.svg)](https://github.com/alainQtec/PsModuleGen/actions/workflows/Upload_Artifact.yaml)
[![Publish to PowerShell Gallery](https://github.com/alainQtec/PsModuleGen/actions/workflows/Publish.yaml/badge.svg)](https://github.com/alainQtec/PsModuleGen/actions/workflows/Publish.yaml)

## Installation

- Install from Powershell Gallery:

    ```PowerShell
    Install-Module PsModuleGen
    ```

## Usage

- Import the module:

    ```PowerShell
    Import-Module PsModuleGen
    ```

- Create a new Module:

    ```PowerShell
    New-PsModule -Name DemoModule
    # Creates a new module in current directory
    ```

## Contributing

Contributions are welcome! Please feel free to submit a pull request.

## License

This project is licensed under the MIT License - see the [MIT License](https://alainQtec.MIT-license.org) for details.

## Todos

- [x] Add ast parser to the main class

- [ ] Add module manifest generator

- [ ] Add module directory tree generator
