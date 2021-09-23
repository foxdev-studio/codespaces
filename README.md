# Codespaces repository
This repository is used and startpoint for GitHub Codespaces

## Devcontainer configuration
- PowerShell CLI 7.1.4
- .NET 5.0.400 (LTS)
- Node.JS 14.17.6 (LTS)

## .NET 6 setup
Since some of Studio's projects utilize preview version of .NET and GitHub Codespaces don't offer to install such version until release, you need to install .NET 6 manually. Here some steps:
1. Download .NET 6 SDK from https://dotnet.microsoft.com/download/dotnet/6.0 (OS: Linux, Architecture: x64)
2. Upload upackage to your Codespace
3. Run following command:
```powershell
tar zxf dotnet-sdk-6.0.100-rc.1.21463.6-linux-x64.tar.gz -C $HOME/.dotnet
```