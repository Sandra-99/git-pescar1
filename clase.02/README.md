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
## Nos permite trabajar en proyectos de manera auxiliar.

```sh
git branch <nombre-rama>
git branch feature/navbar
git branch feature/footer
```

# Fusiones (Marge) de ramas (ranches)

* Fusion -> fast-foward (automatica)
* Fusion -> tres vias (automatica) (genera un commit intermedio entre los ultimos commits)
* Fusion, manual (Git no puede solucionar los conflictos) pide que yo como desarrollador solucione los conflictos.
