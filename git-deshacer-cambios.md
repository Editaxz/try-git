# DESHACIENDO CAMBIOS

 ## git checkout
 ```
 vi texto.txt
 git status
 git add texto.txt
 git commit -m "add texto"
 vi texto.txt # modificar texto
 git status
 git checkout -- texto.txt
 ```

 ## git reset
 ```
 vi texto.txt
 git status
 git add texto.txt
 git status
 git reset HEAD texto.txt
 git status
 git checkout -- texto.txt
 ```

 ## Deshaciendo commits (comando destructivo, usar de forma local)
 ```
 git log --oneline
 git reset 7b3c714
 git log --oneline
 git status
 git checkout -- texto.txt
 git  status
 ```
 ## git reset HARD (Despues de un commit)
  ```
  git status
  git reset --hard 7b3c714
  git log --oneline 
  ```
 ## git reverse  (Revirtiendo commit)
  ```
  git diff 7b3c714 9u3c710
  git log --oneline --decorate
  git diff HEAD~1  #Un commit antes que HEAD
  git diff HEAD~2
  git revert HEAD
  git log --oneline 
  git revert --no-commit HEAD
  git log --oneline
  ```