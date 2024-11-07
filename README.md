# WSL Docs
 Windows Subsystem for Linux


https://learn.microsoft.com/en-us/windows/wsl/install


## Install (PowerShell) :

```wsl --install```

### Change WSL Version 2 <--> WSL 1:

```wsl --set-version```

```wsl --set-version <Distribution Name> 2```

ex: ```wsl --set-version Ubuntu-20.04 2```


### Change the installed distribution :

```wsl --install -d <Distribution Name>```


### List available distributions: 

```wsl.exe --list --online```

```wsl -l -o```


### List installed Linux distributions and check WSL version:

```wsl -l -v```


### Set the default Linux distribution :

```wsl -s <DistributionName>```

```wsl --set-default <DistributionName>```

ex : ```wsl -s Debian```