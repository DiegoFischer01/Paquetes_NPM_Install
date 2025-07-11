## Paquetes_NPM_Install
Paquetes NPM necesarios para que funcione Typescript y JS.


npm install -g typescript



npm i readline-sync
//Para instalar la biblioteca interactiva con el usuario
// es necesario importarla: 
import * as readlineSync from 'readline-sync' 


npm install -g ts-node
//Para ejecutar directamente archivos .ts en node.js o vscode


npm i @types/readline-sync
//Son lso tipos


npm install -g ts-node
//Compila y ejecuta en un solo paso (pero ahora se ejecuta con "ts-node + nombreArchivo").
//Sino es lo mismo compilar el archivo.js con "tsc", y eso crea un archivo js


- Tambien es importante el comando que permite ejecutar los scripts en powershell
Set-ExecotionPolicy Unrestricted


File-Saver:
npm i filesaver.js


## Comandos GIT importante

git add .
git commit -m "comentario"
git push -u origin main

git branch + nombre_rama_nueva La crea, (y luego la publicamos con git push origin + nombre de la rama creada).
git branch   Las muestra
git branch -a Muestra todas las ramas (locales y remotas)
git checkout
git pull origin + nombre de la rama de la cual quiero bajarme los cambios a la rama en la que estoy parado.

Otros importantes

git status
git remote -v (para ver a que repo remoto estoy conectado).
git remote remuve + nombre del remoto (origin)
git remote  add + (Nombre_de_la_rama (por convencion "origin")) + URL del repo remoto

Para mergear:
De la que estoy parado...
git merge + nombre la rama que quiero unir (se hace el merge a la rama donde estoy para)
Despues de mergear:
git commit -m "merge/nueva funcionalidad< por ej>"
git push origin... main o develop o la rama remota donde quiero publicar el merge