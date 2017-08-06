#CREATE AND COMMIT BRANCHS

#Create Branchs from GIT
git checkout -b develop
git checkout -b tk01
git checkout -b tk02

#Push branch develop
git checkout develop
git add .
git commit -m "add branch develop"
git push origin develop

#Push branch tk01
git checkout tk01
git add .
git commit -m "add branch tk01"
git push origin tk01

#Push branch tk02
git checkout tk02
git add .
git commit -m "add branch tk02"
git push origin tk02


#Create Branches from GITHUB
git pull origin tk02




