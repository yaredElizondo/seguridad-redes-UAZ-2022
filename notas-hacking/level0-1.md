# Level 0 - Level 1
## Objetivo
The password for the next level is stored in a file called **readme** located in the home directory. Use this password to log into bandit1 using SSH. Whenever you find a password for a level, use SSH (on port 2220) to log into that level and continue the game.

## Datos acceso
user: bandit0
host: bandit.labs.overthewire.org
port: 2220
paswd:bandit0
linea-comando: sudo ssh bandit0@bandit.labs.overthewire.org -p 2220

## Solucion
```shell
bandit0@bandit:~$ ls
readme
bandit0@bandit:~$ cat readme 
boJ9jbbUNNfktd78OOpsqOltutMc3MY1
bandit0@bandit:~$ 

```

## Notas adicionales


## Referencias
-   [Secure Shell (SSH) on Wikipedia](https://en.wikipedia.org/wiki/Secure_Shell)
-   [How to use SSH on wikiHow](https://www.wikihow.com/Use-SSH)
