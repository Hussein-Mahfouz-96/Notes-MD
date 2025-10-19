---
id: 1zblr3y4tll4qt16n5k5r21
title: DockerSetupWindows
desc: ""
updated: 1760837814500
created: 1760831321418
---

## Docker Setup for Windows

To set up Docker for Windows, visit the official website: [Docker Desktop for Windows Installation Guide](https://docs.docker.com/desktop/setup/install/windows-install/).

### Prerequisites

To use Docker Desktop on your system, you need to enable Hyper-V and Containers for Windows, also we need to enable WSL features in windows. Run the following commands in PowerShell as an administrator:

```powershell
Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Hyper-V -All
```

```powershell
Enable-WindowsOptionalFeature -Online -FeatureName Containers -All
```

For WSL we can follow instructions in this URL:
https://learn.microsoft.com/en-us/windows/wsl/install

### Installation

Follow the instructions provided on the Docker website to complete the installation of Docker Desktop on your system.

