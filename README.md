# Paquetes_NPM_Install
Paquetes NPM necesarios para que funcione Typescript y JS.


npm install -g typescript



npm i readline-sync
//Para instalar la biblioteca interactiva con el usuario// es necesario importarla: 
import * as readlineSync from 'readline-sync' 


npm install -g ts-node
//Para ejecutar directamente archivos .ts en node.js o vscode//


npm i @types/readline-sync
//Son lso tipos


npm install -g ts-node
//Compila y ejecuta en un solo paso (pero ahora se ejecuta con "ts-node + nombreArchivo").
//Sino es lo mismo compilar el archivo.js con "tsc", y eso crea un archivo js


- Tambien es importante el comando que permite ejecutar los scripts en powershell
Set-ExecotionPolicy Unrestricted


File-Saver:
npm i filesaver.js