# Aplicación de notas

![Captura](captura.png)

## Pasos

1° Creo un repositorio

Terminal > git bash
Escribo: git init

2° Configurar el usuario y mail
git config user.name "santiagoprietooo" global
git config user.mail "santiago.prieto@davinci.edu.ar" global

chequeo en: - git config user.name
            - git config user.mail

3° Agrego los archivos
Para agregar uno por uno: git add index.html
Para agregar todos:       git add .

4° Creo el commit
git commit -m "Nombre de los cambios"

5° Vincular el repositorio remoto con el local
git remote add origin https://github.com/santiagoprietooo/ejemplo.git

6° Subir los cambios (committs)
git push origin master

## Para crear ramas
git branch nombre

## Para cambiarme de rama
git chekout nombre