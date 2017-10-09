# CREAR Y HACER COMITS EN RAMAS

# Ver ramas
```
git branch
```

## Crear rama
```
git branch develop
git branch
```
## Crear rama y posicionarse en ella
```
git checkout -b develop
git checkout -b tk01
git checkout -b tk02
```
## Cambiar nombre de rama
```
git branch -m develop developer
git branch
```
## Eliminar ramas
```
git branch -d developer
git branch
```
## Push rama develop
```
git checkout develop
git add .
git commit -m "add branch develop"
git push origin develop
```
## Push rama tk01
```
git checkout tk01
git add .
git commit -m "add branch tk01"
git push origin tk01
```
## Push rama tk02
```
git checkout tk02
git add .
git commit -m "add branch tk02"
git push origin tk02
```

## Pulling de ramas
```
git pull origin tk02
```

## Ver todos los comits de todas las ramas
```
git log --oneline --decorate --all --graph
```

