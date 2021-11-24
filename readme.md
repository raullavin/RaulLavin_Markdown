**Comandos de Configuracion**
git config --global user.mail raul.lavinmartinez@iesmiguelherrero.com
git config --global user.name "Raul Lavin"

**Clonar repositorio**
git clone https://github.com/raullavin/RaulLavin_Markdown.git

**Añadir archivo**
git add readme.md

**Comprobar el estado**
git status

**Hacer un commmit**
git commit -m "Primer Commit Raul Lavin"

**Subir los cambios al repositorio remoto**
git push

**Actualizar el repositorio local**
git pull

**Crear archivo**
touch .gitignore

**Configuracion archivo .gitignore**
git config --global core.excludesFile .gitignore

**Crear un tag y visualizar**
git tag v0.1
git log

**Tabla con enlaces a los github de los compañeros**
| Nombre             | Enlace a GitHub                                                 |
| :----------------- | --------------------------------------------------------------: | 
| Alejandro Ceballos | https://github.com/daw203/Alejandro_Markdown                    | 
| Javier Sosa        | https://github.com/JavierSosa1/Javier_markdown                  | 
| Antonio Lopez      | https://gitlab.com/antonioalopezfernandez/ANTONIOLOPEZ_Markdown | 

**Crear una rama**  
git checkout -b rama-Raul

**Subir cambios al repositorio remoto de una rama**  
git push origin rama-Raul

**Hacer un merge**  
git merge rama-Raul

**Cambiar entre las ramas**  
git checkout rama-Raul
git checkout main

**Borrar una rama**  
git branch -d rama-Raul

**Ver todo lo que has realizado**  
git log --graph
