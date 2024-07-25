# git diff comparo entre diferentes commits en el tiempo

```sh
git diff <hash> <hash>
```
# para agregar algo que me olvide o quiero incomporara algo para el utlimo commit, uso el siguiente comando 

```sh
git add . 
git commit --amend (7988bf1)

```

# RAMAS (Branches)
## Nos permite trabajar en proyectos de manera auxiliar. trabaja ramas

## crear una rama

```sh
git branch <nombre-rama>
git branch feature/navbar
git branch feature/footer
```

# Moverme enntre ramas
## comando switch -> cambirar de ramas

```sh
git switch <nombre-rama>
git switch feature/navbar
git switch feature/footer

```

```sh
git switch -c <nombre-rama>
git switch -c feature/rama

```

## Ver todas las ramas del repositorio en el log

```sh
git log --oneline --all --graph --decorate

```

## Ver detalles de las ramas y sus ultimos commit

```sh
git branch -v

```


## Borrar una rama

```sh
git branch -d <nombre-de-la-rama>
```

## Borrar una rama de forma forzada. (seguro de lo que quiero borrar)

```sh
git branch -D <nombre-de-la-rama>

```