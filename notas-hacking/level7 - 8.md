# Level 7 - Level 8
## Objetivo
The password for the next level is stored in the file **data.txt** next to the word **millionth**
## Datos acceso
user: bandit7
host: bandit.labs.overthewire.org
port: 2220
paswd:HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs
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
2>/dev/null -> direccionar los errores, todos los errores vayan a null
-size 33 -> el **-size** es para decir que tiene un tamaño especifico el archivo y el **33c** quiere decir que tiene 33 caracteres o bytes
-user -> es para especificar que tipo de usuario voy a buscar 
-group -> el grupo de usuario

## Referencias
-   [Secure Shell (SSH) on Wikipedia](https://en.wikipedia.org/wiki/Secure_Shell)
-   [How to use SSH on wikiHow](https://www.wikihow.com/Use-SSH)