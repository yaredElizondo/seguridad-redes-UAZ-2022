# Level 1 - Level 2
## Objetivo
The password for the next level is stored in a file called **-** located in the home directory
## Datos acceso
user: bandit1
host: bandit.labs.overthewire.org
port: 2220
paswd:boJ9jbbUNNfktd78OOpsqOltutMc3MY1
linea-comando:ssh bandit1@bandit.labs.overthewire.org -p 2220

## Solucion
```shell
bandit1@bandit:~$ ls
-
bandit1@bandit:~$ cat ./-
CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9
bandit1@bandit:~$ 

```

## Notas adicionales


## Referencias
-   [Secure Shell (SSH) on Wikipedia](https://en.wikipedia.org/wiki/Secure_Shell)
-   [How to use SSH on wikiHow](https://www.wikihow.com/Use-SSH)
