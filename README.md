
# Teapot Package Manager
[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)
## Overview
Teapot is a Windows package manager inspired by [Homebrew](https://github.com/Homebrew/brew), designed to simplify software installation and management for Windows users. Teapot supports automatic conversion of Homebrew packages to Windows-compatible versions, offering a unified command-line experience. It brings powerful dependency resolution and cross-platform support without the need for additional subsystems.


# Features
- Install Packages: Easily install software packages with simple commands.
- Automatic Conversion: Converts Homebrew packages for Windows compatibility.
- Dependency Management: Automatically resolves and installs required dependencies for each package.
- User-Friendly CLI: Mimics the familiar brew command structure, making it easy for users of Homebrew to transition.
- Cross-Platform Support: Designed to work on Windows without requiring Linux or macOS subsystems.
## Installation
To install Teapot, run the following command in PowerShell:

```powershell
iwr -useb https://raw.githubusercontent.com/dolovesvw/teapot/main/install.ps1 | iex
```
This command will download and execute the Teapot installation script. Make sure PowerShell is running with the appropriate execution policy to allow script execution.
# Usage
## Basic Commands
Here are some basic commands to get you started:

### Install a package:

```bash
brewt install <package>
```
### Update package list:

```bash
brewt update
```
### Upgrade installed packages:

```bash
brewt upgrade
```
### Uninstall a package:

```bash
brewt uninstall <package>
```

## Teapot works just like homebrew! 
But here is the documentation if you need it:

[Documentation](https://linktodocumentation)


## Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to fork the repository and submit a pull request.

See `contributing.md` for ways to get started.

Steps to Contribute:
- Fork the repository.
- Create a new branch for your feature or bug fix.
- Make your changes and commit them.
- Push to your fork and submit a pull request.

Please adhere to this project's `code of conduct`.


## FAQ

#### No questions right now.

Come back later when Teapot is done!

## Acknowledgments

#### Inspired by Homebrew: 
- Teapot is inspired by the simplicity and effectiveness of Homebrew for macOS and Linux users.
#### Homebrew Community: 
- Thanks to the open-source community behind Homebrew for their work and inspiration.

For more information, visit [Homebrew's documentation](https://brew.sh/).

For questions or feedback, please reach out to [mail4dolovesv@gmail.com].
## License

Teapot is open-source and available under the [MIT](https://choosealicense.com/licenses/mit/) License. See the LICENSE file for more details. Please ensure any package conversions respect the original licenses.

Teapot's inspiration comes from Homebrew, an open-source project under the MIT License. While Teapot uses a similar structure to Homebrew, it’s designed specifically for Windows users and does not directly copy Homebrew’s source code.
