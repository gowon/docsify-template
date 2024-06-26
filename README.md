# docsify-template

## 1. Developing

For Windows users, you can install of the required and recommended development tools using the Chocolatey package manager.

1. Install Chocolatey on your machine using the [individual installation instructions](https://chocolatey.org/install#individual)

2. In a command prompt with Administrator privileges, run the following command from the project root folder:

  ```powershell
  choco install .\solution.chocolatey.config --confirm
  ```

- .NET 8 SDK
- PowerShell Core
- Visual Studio Code

## 2. Running Locally

While in the [`docs`](docs/) folder, you can use the [`dotnet-serve`](https://github.com/natemcmaster/dotnet-serve) tool to serve the static documentation website locally:

```powershell
dotnet tool restore
dotnet serve --open-browser
```

When running, the website can be accessed through <http://localhost:3080>.
