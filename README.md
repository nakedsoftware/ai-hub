# AI Hub

[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)

## About AI Hub

TODO

## Getting Started

Before cloning the AI Hub repository, please review the [software requirements](docs/software_requirements.md) and ensure that your development environment is configured properly. Once you have installed and configured all of the required software, you can use [GitHub CLI](https://cli.github.com) to clone the AI Hub repository. In a terminal (Apple macOS or Linux) or Command Prompt or PowerShell window (Microsoft Windows), navigate to the location in your file system where you want to store the repository and run:

    gh repo clone nakedsoftware/ai-hub

After cloning the repository, you must prepare the repository for development. AI Hub makes use of software development tools and requires libraries and dependencies that are managed in the repository. These software packages need to be downloaded and installed to be able to build and run AI Hub locally. The steps required to prepare the local repository for development have been automated using the `do setup` command.

- __Apple macOS or Linux__: In the terminal, run the following commands to set up the local repository for development:

```shell
cd ai-hub
./do setup
```

- __Microsoft Windows__: In a Command Prompt window, run the following command:

```batch
pwsh do.ps1 setup
```

Or in a PowerShell window, run:

```powershell
&"./do.ps1" setup
```

After the `do setup` command completes, the local repository is ready to build and run AI Hub locally or support your software development activities.
