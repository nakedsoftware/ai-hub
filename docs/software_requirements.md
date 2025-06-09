# Software Requirements

Before attempting to work with the AI Hub source code, you should make sure that your local development environment is set up properly. AI Hub requires the following software packages be installed in your local development environment:

1. [Homebrew](#homebrew)
1. [Git](#git)
1. [GitHub CLI](#github-cli)

AI Hub supports Apple macOS, Linux, and Microsoft Windows as development environments for building, running, and developing new feature for AI Hub. Not all required software is required on all operating systems. Each software package indicates which operating system it is required on using the following icons:

- :white_check_mark:: The software package is required on this operating system
- :grey_question:: The software package is optional on this operating system
- :x:: The software package is not required on this operating system

## Homebrew

- :white_check_mark: Apple macOS
- :white_check_mark: Linux
- :x: Microsoft Windows

[Homebrew](https://brew.sh) is a package manager for Apple macOS and Linux operating systems. Homebrew can install many popular open source and commercial applications, development tools, and libraries. Homebrew can also keep dependencies up to date and install new versions as they become avaiable. To install Homebrew, open a terminal and run:

    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

After installing Homebrew, you will need to stop and restart your terminal before the environmental changes take effect.

## Git

- :white_check_mark: Apple macOS
- :white_check_mark: Linux
- :white_check_mark: Microsoft Windows

[Git](https://git-scm.com) is a distributed version control system and is used to manage the source code for the AI Hub product. Git gives each developer their own complete copy of the repository for developing either online or offline. Git makes it easy for developers to collaborate by sharing their changes directly with other developers or indirectly using a shared repository hosted on a service such as [GitHub](https://github.com).

- __Apple macOS and Linux__: Git can be installed using [Homebrew](#homebrew). To install Git, open a terminal and run:

```shell
brew install git
```

- __Microsoft Windows__: Git can be installed using [WinGet](https://learn.microsoft.com/en-us/windows/package-manager/winget/). In a Command Prompt or PowerShell window, run:

```batch
winget install --id Git.Git -e --source winget
```

## GitHub CLI

- :white_check_mark: Apple macOS
- :white_check_mark: Linux
- :white_check_mark: Microsoft Windows

[GitHub CLI](https://cli.github.com) is a command line interface for GitHub. GitHub CLI can be used to automate tasks for managing repositories or project, or can be used to start GitHub Actions workflows.

- __Apple macOS and Linux__: GitHub CLI can be installed using [Homebrew](#homebrew). To install GitHub CLI, open a terminal and run:

brew install gh

- __Microsoft Windows__: GitHub CLI can be installed using [WinGet](https://learn.microsoft.com/en-us/windows/package-manager/winget/). In a Command Prompt or PowerShell window, run:

```batch
winget install --id GitHub.cli
```
