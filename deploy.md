# Choco Installation
```
Set-ExecutionPolicy AllSigned
```

```
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```

# My main packages Installation
```
choco install googlechrome zoom dropbox em-client miro notion telegram steam foxitreader mattermost-desktop obsidian github-desktop
```

# Needed smth else?
https://community.chocolatey.org/packages
