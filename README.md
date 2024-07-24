# CLASE 01 - DESARROLLO COLABORATIVO CON GIT

## configuraciones iniciales de las herramientas

### agrego un nombre de usuario y correo
este usuario y el correo va a ser utilizado para firmar cada uno de la instantaneas (fotos/commit). 
Es obligatoria la configuracion de este usuario y correo

```sh

git config --global user.name "sandra-99"
git config --global user.email sandrabenitez321@gmail.com
git config --local (tiene que existir un repositorio para poder)
git config --system (computadora, se sacantodos la misma foto)
```


## borrar alguna de las configuraciones 

```sh
git config --global --unser user.name
```

## Modificar el editor de teexto que usa GIT

```sh
git config --global core.editor "nano"
```

## Modificar la rama por defecto. master a main 

```sh
git config --global init.defoultBrunch main
```

## Empezar a trabajar con GIT 

```sh
git init
```

## Controlar el status de los archivos dentro del repositorio

```sh
git status
```


## agregar al area de staging => al repositorio 
```sh
git add <nombre del archivo>
#subir todos los archivos a la vez
git add . 

```

# subir el archivo al area de staging => guardia en el repositorio una instatanea
```sh

git commit -m "mensaje"
```


# ver el estado e info del commit
```sh
git log
```   

# ver las modificaciones / diferencias que se agregaron o quitaron en el working directory y el local repo

```sh
git diff
```
 




