# HACK-HTML1
hack html numero 1
git checkout -b develop
git checkout -b feature/H-1
# Realiza cambios en el código
git add .
git commit -m "Descripción de los cambios realizados para H-1"
git checkout develop
git merge feature/H-1
git checkout main
git merge develop
git push origin main
git push origin develop
