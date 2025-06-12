# Scenario : Advanced AI Pair Programming Challenge

Developers today agree that AI code assistant tools are useful for easy, repeatable tasks. JSON to Class, quick templated code, writing simple scripts. But most still think it's bad at more complex tasks. This exercise is here to show you that assumption is no longer as true as you might think!


## Prerequisites

- Clone the eShop repository: https://github.com/dotnet/eshop
- Clone the AI Assisted Coding Framework repository: https://github.com/ChrisMcKee1/AI-Assisted-Coding
- [Install & start Docker Desktop](https://docs.docker.com/engine/install/)

### Skills

- C# and .NET Tooling
- Git and GitHub
  - [Forking](https://docs.github.com/github/getting-started-with-github/quickstart/fork-a-repo) and [cloning](https://docs.github.com/github/creating-cloning-and-archiving-repositories/cloning-a-repository-from-github/cloning-a-repository) repositories

### Software

- [Git](https://git-scm.com/downloads)
  - [Install git on macOS](https://git-scm.com/download/mac)
  - [Install git on Windows](https://git-scm.com/download/win)
  - [Install git on Linux](https://git-scm.com/download/linux)
- [Visual Studio Code](https://code.visualstudio.com/)
- [.NET 9 SDK](https://dot.net/download?cid=eshop)

Or

- Run the following commands in a Powershell & Terminal running as `Administrator` to automatically configuration your environment with the required tools to build and run this application. (Note: A restart is required after running the script below.)

##### Install Visual Studio Code and related extensions
```powershell
install-Module -Name Microsoft.WinGet.Configuration -AllowPrerelease -AcceptLicense  -Force
$env:Path = [System.Environment]::GetEnvironmentVariable("Path","Machine") + ";" + [System.Environment]::GetEnvironmentVariable("Path","User")
get-WinGetConfiguration -file .\.configurations\vscode.dsc.yaml | Invoke-WinGetConfiguration -AcceptConfigurationAgreements
```

## Resources

In the [Example Requirements](./example-requirements/) folder, you'll find a series of Markdown files. These are just a few example requirements that we dreamed up to add new features to eShop. Choose one and see how well the AI framework implements the change!

## Goals

You'll understand better how to utilize advanced AI tools to increase your productivity and workflow.

1. [Setup the AI Coding Workflow](./goals/1-setup.md):
   The key to this workshop is our advanced workflow. This will show you how to reuse our work across your projects.
1. [Understanding Requirements](./goals/2-requirements.md):
   We've created several sample requirements docs. Run one and see the results.
1. [Tips and Tricks](./goals/3-tips.md):
   Pitfalls to avoid, custom instructions, and prompt files

## Validation

This workshop is designed to be a goal-oriented self-exploration of Advanced AI Coding using GitHub Copilot. Your results will vary, as AI development is non-deterministic.

## Where do we go from here?



## Additional notes and disclaimers

### Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

### Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft trademarks or logos is subject to and must follow [Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/legal/intellectualproperty/trademarks/usage/general). Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship. Any use of third-party trademarks or logos are subject to those third-party's policies.
