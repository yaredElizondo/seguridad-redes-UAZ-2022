# Level 4 - Level 5
## Objetivo
The password for the next level is stored in the only human-readable file in the **inhere** directory. Tip: if your terminal is messed up, try the “reset” command.
## Datos acceso
user: bandit4
host: bandit.labs.overthewire.org
port: 2220
paswd:pIwrPrtPN36QITSp3EQaw936yaFoFgAB
linea-comando:ssh bandit2@bandit.labs.overthewire.org -p 2220

## Solucion
```shell
bandit4@bandit:~/inhere$ ls -l
total 40
-rw-r----- 1 bandit5 bandit4 33 May  7  2020 -file00
-rw-r----- 1 bandit5 bandit4 33 May  7  2020 -file01
-rw-r----- 1 bandit5 bandit4 33 May  7  2020 -file02
-rw-r----- 1 bandit5 bandit4 33 May  7  2020 -file03
-rw-r----- 1 bandit5 bandit4 33 May  7  2020 -file04
-rw-r----- 1 bandit5 bandit4 33 May  7  2020 -file05
-rw-r----- 1 bandit5 bandit4 33 May  7  2020 -file06
-rw-r----- 1 bandit5 bandit4 33 May  7  2020 -file07
-rw-r----- 1 bandit5 bandit4 33 May  7  2020 -file08
-rw-r----- 1 bandit5 bandit4 33 May  7  2020 -file09
bandit4@bandit:~/inhere$ file ./*
./-file00: data
./-file01: data
./-file02: data
./-file03: data
./-file04: data
./-file05: data
./-file06: data
./-file07: ASCII text
./-file08: data
./-file09: data
bandit4@bandit:~/inhere$ cat ./-file07
koReBOKuIDDepwhWk7jZC0RTdopnAYKh
bandit4@bandit:~/inhere$ 
```

## Notas adicionales


## Referencias
-   [Secure Shell (SSH) on Wikipedia](https://en.wikipedia.org/wiki/Secure_Shell)
-   [How to use SSH on wikiHow](https://www.wikihow.com/Use-SSH)