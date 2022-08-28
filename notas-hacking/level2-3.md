# Level 2 - Level 3
## Objetivo
The password for the next level is stored in a file called **spaces in this filename** located in the home directory
## Datos acceso
user: bandit2
host: bandit.labs.overthewire.org
port: 2220
paswd:CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9
linea-comando:ssh bandit2@bandit.labs.overthewire.org -p 2220

## Solucion
```shell
bandit2@bandit:~$ ls
spaces in this filename
bandit2@bandit:~$ cat spaces\ in\ this\ filename 
UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK
bandit2@bandit:~$  

```

## Notas adicionales


## Referencias
-   [Secure Shell (SSH) on Wikipedia](https://en.wikipedia.org/wiki/Secure_Shell)
-   [How to use SSH on wikiHow](https://www.wikihow.com/Use-SSH)
