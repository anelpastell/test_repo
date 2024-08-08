# Notas 7 Agosto 2024
*si necesitas instalar todo en tu compu :(*
## Pasos a seguir
Instala git en tu compu:
- https://git-scm.com/book/en/v2/Getting-Started-Installing-Git

Tambien necesitas instalar Py Charm
- https://www.youtube.com/watch?v=MJJpL9EmJBs

De paso instala esto
-  [https://www.youtube.com/watch?v=HLD-Ll_-IT4]

## Git Bash
Busca la app en tu buscador de windows, ábrela y haz esto:
- git config --list
- git config --global user.name "anelpastell"  -> aquí se supone que va tu username de GitHub
- git config --global user.email "anel.mendiola@comunidad.unam.mx"  -> este es el correo con el que iniciaste sesión
  Se supone que esto ayuda a que se conecte con lo que tienes en tu compu y en la app
- git config --list

Usa CTRL+C para guardar lo que llevas
- escribe exit y te saca de git
- abre tus carpetas y crea una nueva, en la parte superior ve el nombre de tu carpeta y copia la dirección, por ejemplo, en la compu de la escuela dice: C:\Users\V303_16\Desktop\Repositorio
- cuando lo corras no te va a dejar, le tienes que agregar doble diagonal a todo
    $ cd C:\\Users\\V303_16\\Desktop\\Repositorio
- ya con eso te deja establecer tu carpeta donde guardarás todo

- escribe: git init

el  mensaje que sale indica que tu carpeta está vacía y q no tiene nada aún, se supone que este folder que se crea es invisible, trátalo como un folder normal y úsalo

## Ahora ve a github
Abre un nuevo repositorio y nómbralo como el que tienes en tu archivo de carpetas, te debe salir una página que dice "Quick Setup", baja y copia lo que dice:
  
git remote add origin https://github.com/anelpastell/Repositorio.git
git branch -M main
git push -u origin main

NOTA: no nos salió xddd, se supone que con eso se conecta de la compu a GitHub, bueno no se pudo, haremos otra cosa:

copia la url que te da github de tu repositorio, borra tu repositorio de tu carpeta de archivos. Vamos a descargar el repositorio desde GitHub, escrbe exit y sal de gitbash, ábrelo de nuevo y escribe

  - git clone https://github.com/anelpastell/Repositorio.git -> ahí en el link, pega el que te dio github

En github crea un nuevo archivo, busca las letritas de colores chiquitas y haz un archivo nuevo, puede ser un .md
- ya que acabes, vuelve a tu repositorio y sube un archivo , es para probar, sube lo que quieras
- ahora bórralo xdddd

A ver, la carpeta que habías borrado de tu local, restáurala, el profe hizo algo raro, ve a la papelera y restaurala, ahora escribe

- cd "C:\Users\V303_16\Desktop\Repositorio"
- git clone C:\Users\V303_16\Desktop\Repositorio
- git pull -> con eso debería funcionar

### TAREA PARA EL LUNES

Crear un repositorio de github, el oficial para el semestre, hazlo en el servidor
- copia la URL de tu repositorio y pégalo en el repositorio del profe, se llama repositorios.txt
  
