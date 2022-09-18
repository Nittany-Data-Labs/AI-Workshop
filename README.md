# Computer Vision using CIFAR10

#### Download Package Manager

## Instructions
-----

##### Windows: 

Run Powershell as `Admin` using command
```
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```

Install Python
```
choco install python3 git.install -y
```

Refresh env variables (PATH):
```
refreshenv
```
Close and reopen powershell

##### MacOS:

Install Homebrew
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Add brew executables to path
```
export PATH="/usr/local/opt/python/libexec/bin:$PATH"
```

Install Python
```
brew install python git
```

#### Set Up Python

Install pip
```
python -m pip install -U pip
```

Install python packages
```
pip install torch pillow jupyter torchvision
```

## Instructions Complete
----
