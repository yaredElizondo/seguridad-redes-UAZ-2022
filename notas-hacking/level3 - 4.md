# Level 3 - Level 4
## Objetivo
The password for the next level is stored in a hidden file in the **inhere** directory.
## Datos acceso
user: bandit3
host: bandit.labs.overthewire.org
port: 2220
paswd:UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK
linea-comando:ssh bandit2@bandit.labs.overthewire.org -p 2220

## Solucion
```shell
bandit3@bandit:~$ cd inhere/
bandit3@bandit:~/inhere$ ls -la
total 12
drwxr-xr-x 2 root    root    4096 May  7  2020 .
drwxr-xr-x 3 root    root    4096 May  7  2020 ..
-rw-r----- 1 bandit4 bandit3   33 May  7  2020 .hidden
bandit3@bandit:~/inhere$ cat .hidden 
pIwrPrtPN36QITSp3EQaw936yaFoFgAB
bandit3@bandit:~/inhere$ 


```

## Notas adicionales


## Referencias
-   [Secure Shell (SSH) on Wikipedia](https://en.wikipedia.org/wiki/Secure_Shell)
-   [How to use SSH on wikiHow](https://www.wikihow.com/Use-SSH)
