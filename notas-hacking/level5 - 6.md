# Level 4 - Level 5
## Objetivo
The password for the next level is stored in the only human-readable file in the **inhere** directory. Tip: if your terminal is messed up, try the “reset” command.
## Datos acceso
user: bandit5
host: bandit.labs.overthewire.org
port: 2220
paswd:DXjZPULLxYr17uwoI01bNLQbtFemEgo7
linea-comando:ssh bandit5@bandit.labs.overthewire.org -p 2220

## Solucion
```shell
bandit5@bandit:~/inhere$ find ./ -type f -size 1033c ! -executable
./maybehere07/.file2
bandit5@bandit:~/inhere$ cd maybehere07/
bandit5@bandit:~/inhere/maybehere07$ ls
-file1  -file2  -file3  spaces file1  spaces file2  spaces file3
bandit5@bandit:~/inhere/maybehere07$ cat .file2
DXjZPULLxYr17uwoI01bNLQbtFemEgo7

```

## Notas adicionales


## Referencias
-   [Secure Shell (SSH) on Wikipedia](https://en.wikipedia.org/wiki/Secure_Shell)
-   [How to use SSH on wikiHow](https://www.wikihow.com/Use-SSH)