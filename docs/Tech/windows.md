
# Windows

## Start Browser From CMD

浏览器
start firefox.exe <http://www.baidu.com>

## Windows Folder Shortcut

```shell
shell:startup 
rem %USERPROFILE%\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup  
rem C:\ProgramData\Microsoft\Windows\Start Menu\Programs\StartUp
shell:programs
shell:common programs
```

## Host

```shell
C:\Windows\System32\drivers\etc
netsh winsock reset
NETSH INT IP RESET  （重置IP设置）
NETSH WINHTTP RESET PROXY  （重置代理设置）
IPCONFIG /FLUSHDNS  （刷新DNS缓存）
```
