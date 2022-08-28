# Level 9 - Level 10
## Objetivo
The password for the next level is stored in the file **data.txt** in one of the few human-readable strings, preceded by several ‘=’ characters.
## Datos acceso
user: bandit9
host: bandit.labs.overthewire.org
port: 2220
paswd:UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR
linea-comando:ssh bandit5@bandit.labs.overthewire.org -p 2220

## Solucion
```shell
bandit9@bandit:~$ cat data.txt  | strings -n 30| grep =
&========== truKLdjsbJ5g7yyJ2X2R0o3a5HQJFuLk
bandit9@bandit:~$ 
```

## Notas adicionales
strings -> busca en un archivo solamente las cadenas
-n -> los caracteres es un limitador
## Referencias
-   [Secure Shell (SSH) on Wikipedia](https://en.wikipedia.org/wiki/Secure_Shell)
-   [How to use SSH on wikiHow](https://www.wikihow.com/Use-SSH)