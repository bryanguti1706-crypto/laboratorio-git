# laboratorio-git

## Comandos usados

git init
![alt text](image.png)
git branch -M main
git add .
![alt text](image-1.png)
git commit -m "Estructura inicial del proyecto"
![alt text](image-2.png)
git log --oneline
![alt text](image-3.png)
git checkout -b desarrollo
![alt text](image-4.png)
git commit -m "Agrega contenido en index"
![alt text](image-5.png)
git checkout main
git merge desarrollo
![alt text](image-6.png)
git diff
![alt text](image-7.png)
git commit -m "Cambio temporal"
![alt text](image-8.png)
git reset --hard HEAD~1
![alt text](image-9.png)
git reflog
![alt text](image-12.png)
git reset --hard 9adc26a
![alt text](image-13.png)
git add .
git commit -m "Agrega gitignore"
![alt text](image-14.png)
git remote add origin https://github.com/bryanguti1706-crypto/laboratorio-git.git
git pull origin main --allow-unrelated-histories
git push -u origin main
![alt text](image-15.png)
git checkout -b login
git commit -m "Agrega login"
git push -u origin login
![alt text](image-16.png)