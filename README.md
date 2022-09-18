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
pip install torch pillow jupyter torchvision numpy matplotlib
```

#### Download the Project
Clone the repo from github using
```
cd Documents
git clone https://github.com/Nittany-Data-Labs/AI-Workshop
cd AI-Workshop
```

#### Run Project
Inside of the proper repository run
```
jupyter notebook
```

You should get a screen like this
![[Pasted image 20220918183250.png]]
Open the project and run!
![[Pasted image 20220918183344.png]]

#### Adding to your github

Visit GitHub and create your own repository 
![[Pasted image 20220918184446.png]]
![[Pasted image 20220918184524.png]]
##### Run the top set of commands FIRST LINE
```
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin <YOUR GITHUB>
git push -u origin main
```

### After running this, delete the instructions and add it to your github!

## Note: For troubleshooting purposes

##### MacOS
Removing the `.git` repository. We are removing this so you can put it on your own github.
```
rm -rf .git
```


##### Windows
```
del .git
```
Note: If you are unable to delete it may be because you cloned using the ADMIN Powershell window


## Instructions Complete
----

## CIFAR-10 Neural Network
This is a Convolutional Neural Network trained on the CIFAR-10 Dataset