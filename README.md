# new-computer-checklist

DONT FORGET TO BACKUP YOUR FILEZILLA CREDS AND SSH KEY AND VISUAL STUDIO USER SECRETS (C:\Users\bjorn\AppData\Roaming\Microsoft)!!!

* Run [Windows10Debloater](https://github.com/Sycnex/Windows10Debloater) `(iex ((New-Object System.Net.WebClient).DownloadString('https://git.io/debloat')))`
* Disable the search bar (reg key `HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Search = 0`)
* Disable Task View button (reg key HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced\ShowTaskViewButton = 0)
* Remove all games
* Change Edge start page, search engine
* Create C:\Dev
* Make exception for C:\Dev with Windows Defender (Add-MpPreference -ExclusionPath "C:\Dev")
* Make exception for NuGet with Windows Defender (Add-MpPreference -ExclusionPath "C:\Users\Bjorn\.nuget")
* Exclude Dev folder from being indexed (maybe this is already done - or rather its not included in indexing locations)
* Install [Visual Studio Community Edition](https://visualstudio.microsoft.com/vs/)
* Install [VS Code](https://code.visualstudio.com/)
  - Install Kubernetes extension
* Install [GifCam](http://blog.bahraniapps.com/gifcam/)
* Show hidden files
* Show file extensions
* Install [FileZilla](https://filezilla-project.org/download.php?type=client)
* Install [dotPeek](https://www.jetbrains.com/decompiler/)
* Install English & Arabic keyboards
* Activate "Remember language input setting in each window"
* Install [7-Zip](https://www.7-zip.org)
* Install [Git](https://git-scm.com/download/win)
* Install [az-cli](https://aka.ms/installazurecliwindows)
* Run `git config --global user.email "bjorn.a.goransson@gmail.com"`
* Run `git config --global user.name "Björn Ali Göransson"`
* Change DPI
* Unpin QuickLaunch shortcuts
* Add AppData, Dev as QuickLaunch shortcuts
* Install [Slack](https://slack.com/intl/en-se/downloads/windows)
* Install [Dell SupportAssist](https://lmgtfy.com/?q=dell+support+assist)
* Install [kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/#install-kubectl-on-windows)
* Install [Discord](https://discord.com/download)
* Install Docker
* Install [SSMS](https://aka.ms/ssmsfullsetup)
