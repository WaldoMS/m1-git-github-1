# Comandos y Configuración Git y Github
## Crear un nuevo repositorio 
- Crear un repositorio en su cuenta de github
- Crear el archivo README.md (Markdown) en su proyecto local
- Crear  el archivo .gitignore para no subir los archivos o carpetas ingresados
## Inicializar un nuevo repositorio GIT
- Para inicializar un nuevo reporistorio de amnera local, debemos ejecutar el siguiente comando:
```
git init
```

##  Referencia del reporsitorio local al repositorio remoto
```
git remote add origin https://github.com/WaldoMS/m1-git-github-1.git
```
```
git remote add origin-bitbucket https://bitbucket
```
Origin puede ser el alias para otro repositorio en bitbucket
- Para verificar ejecutar los siguientes comandos:
```
git remote
git remote -v
```
##  Finalizando (publicar)
```
git add .
git add index.html
git commit -m "configuracion inicial de git"
git push origin master
```
Para clonar se utiliza C:\>git clone https://github.com/WaldoMS/m1-git-github-1.git