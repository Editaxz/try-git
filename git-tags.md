# USAR TAGS EN GIT

 ## COMMITS BAJO EL CONTROL DE WORKFLOW FEATURE BRANCH
 ```
 git checkout feature-newstyle
 git  add .
 git commit -m "retoque"
 git log --online --decorate 
 git checkout master 
 git checkout -b fix-fecha
 git log --online --decorate --all
 git log --online --decorate --all --graph
 ```
 ## GESTION DE VERSIONES DE CÓDIGO DE UN PROYECTO
 ```
 git tag v0.2.0
 git log --online --decorate 
 ```
 ## Tag a un commit en específico
 ```
 git tag v0.1.0 3456h53f
 ```
 # Hacer un checkout a un tag
 ```
 git checkout v0.1.0
 git lod
 git checkout -b fix-0.1.1
 git checkout master
 ```
 ## Listar todos los tags
 ```
 git tag 
 ```
 ## Eliminar tags
 ```
 git tag -d v0.1.1
 ```
 ## Mostrar tags anotados
 ```
 git tag -l
 git tag -l "v01.1*"
 git tag -l  "v01.0*"
 ```

 ## Eliminar tag determinados
 ```
 git tag -l "v2"
 git tag -d v02.1.0
 ```
 ## Creando tags anotados
 ```
 git tag -a v01.2.1
 git tag
 git show v0.1.0
 
 autor
 fecha
 mensaje
 fecha commit
 autor commit
 historial
 ```
 ```
 git show master
 git show 35435jnh5

 git show v21.3.6
 ```

