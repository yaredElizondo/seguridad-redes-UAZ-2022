# Level 8 - Level 9
## Objetivo
The password for the next level is stored in the file **data.txt** and is the only line of text that occurs only once
## Datos acceso
user: bandit8
host: bandit.labs.overthewire.org
port: 2220
paswd:cvX2JJa4CFALtqS87jk27qwqGhBM9plV
linea-comando:ssh bandit5@bandit.labs.overthewire.org -p 2220

## Solucion
```shell
bandit7@bandit:~$ ls
data.txt
bandit7@bandit:~$ wc data.txt 
  98567  197133 4184396 data.txt
bandit7@bandit:~$ grep millonth data.txt 
bandit7@bandit:~$ grep millionth data.txt 
millionth	cvX2JJa4CFALtqS87jk27qwqGhBM9plV
bandit7@bandit:~$ 
```

## Notas adicionales
sort -> ordena
 uniq -u -> muestra los repetidos o los que solamente hay una vez

cat data.txt | sort | uniq -u

## Referencias
-   [Secure Shell (SSH) on Wikipedia](https://en.wikipedia.org/wiki/Secure_Shell)
-   [How to use SSH on wikiHow](https://www.wikihow.com/Use-SSH)