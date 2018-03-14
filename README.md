# dev-setup

## Windows

### Autohotkey

Save `change-desktop.ahk` to `%USERPROFILE%\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup`.

```
!^Right:: send {LCtrl down}{LWin down}{Right}{LWin up}{LCtrl up}
!^Left:: send {LCtrl down}{LWin down}{Left}{LWin up}{LCtrl up}
```

### Cmder

#### Git for Windows

##### Parameters

`/icon "C:\Program Files\Git\mingw64\share\git\git-for-windows.ico"`

##### Command

`cmd /c "C:\Program Files\Git\bin\bash.exe" --login -i -new_console:d:%USERPROFILE%`

#### Ubuntu Subsytem

## Ubuntu
