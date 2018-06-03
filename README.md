# dev-setup

## Windows

### Autohotkey

Save `change-desktop.ahk` to `%USERPROFILE%\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup`.

```
!^Right:: send {LCtrl down}{LWin down}{Right}{LWin up}{LCtrl up}
!^Left:: send {LCtrl down}{LWin down}{Left}{LWin up}{LCtrl up}
```

### Cmder

Make new tasks start in home directory by default by [setting startup location](https://stackoverflow.com/a/43836978/4832982).

#### Git for Windows

##### Parameters

`/icon "C:\Program Files\Git\mingw64\share\git\git-for-windows.ico" /dir "%USERPROFILE%"`

##### Command

`cmd /c "C:\Program Files\Git\bin\bash.exe" --login -i`

#### Ubuntu Subsytem

## Ubuntu
