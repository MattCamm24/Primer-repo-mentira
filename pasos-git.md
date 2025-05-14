Paso 1:
Crear un repositorio: git init

Paso 2:
Dar seguimiento a los archivos de nuestro repositorio
git add .

U : untracked (area sin seguimiento)

paso 3:
Crear una version (commit) del repositorio
git commit -m "version 1 de mi repositorio"

paso 4:
Renombra la rama master a main ( master => main)
git branch -M main

Paso 5:
CONECTAR NUESTRO REPOSITORIO LOCAL CON UN ORIGEN REMOTO
git remote add origin https://github.com/MattCamm24/Primer-repo-mentira.git

Paso 6:
Subir nuestros cambios al repositorio remoto
git push -u origin main


ver historial de commits:
git log

ver el estado actuald de nuestro repositorio:
git status


PASOS PARA ACTUALIZAR EL PROYECTO:

paso 1:
añadimos los cambios
git add .

Paso 2:
hacer una version
git commit .m "describis los cambios brevemente"

Paso 3:
Subir la nueva version
git push