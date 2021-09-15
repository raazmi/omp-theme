# raaz oh-my-posh theme for windows powershell

A omp (oh-my-posh) theme for windows powershell & the name is raaz.

### Installation process

_Make sure you had already installed powerline on your windows computer. To know more follow this [link](https://docs.microsoft.com/en-us/windows/terminal/tutorials/powerline-setup)_

- Download this repository
- Copy the raaz.omp.json file
- Paste it to this location C:\Program Files\WindowsPowerShell\Modules\oh-my-posh\3.180.1\themes
- Go to powershell & run 'Get-PoshThemes' & you'll see all themes there including this theme.
- Run 'notepad $PROFILE', a notepad window will open & paste the below code there.

```
Import-Module posh-git
Import-Module oh-my-posh
Set-PoshPrompt -Theme raaz
```

- Save the file & restart your powershell.
