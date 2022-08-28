# Level 6 - Level 7
## Objetivo
The password for the next level is stored **somewhere on the server** and has all of the following properties:

-   owned by user bandit7
-   owned by group bandit6
-   33 bytes in size
## Datos acceso
user: bandit6
host: bandit.labs.overthewire.org
port: 2220
paswd:DXjZPULLxYr17uwoI01bNLQbtFemEgo7
linea-comando:ssh bandit5@bandit.labs.overthewire.org -p 2220

## Solucion
```shell
bandit6@bandit:~$ ls
bandit6@bandit:~$ find / -user bandit7 -group bandit6 -size 33c 2>/dev/null
/var/lib/dpkg/info/bandit7.password
bandit6@bandit:~$ cat /var/lib/dpkg/info/bandit7.password
HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs
bandit6@bandit:~$ 
```

## Notas adicionales
2>/dev/null -> direccionar los errores, todos los errores vayan a null
-size 33 -> el **-size** es para decir que tiene un tamaño especifico el archivo y el **33c** quiere decir que tiene 33 caracteres o bytes
-user -> es para especificar que tipo de usuario voy a buscar 
-group -> el grupo de usuario

## Referencias
-   [Secure Shell (SSH) on Wikipedia](https://en.wikipedia.org/wiki/Secure_Shell)
-   [How to use SSH on wikiHow](https://www.wikihow.com/Use-SSH)