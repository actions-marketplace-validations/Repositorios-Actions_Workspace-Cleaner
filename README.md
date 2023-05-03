# Workspace cleaner

Actions para limpiar el los archivos alojados por el checkout del repositorio y la utilización de Actions en el runner.

## ¿Que es Workspace cleaner?

Workspace cleaner es un action que permite la eliminación de los archivos alojados en el runner especficamente en 2 directorios.

- My_Repository
- _Actions

<p align="center">
  <img width="541" height="234" alt="consola" src="public/img/consola.png">
</p>

IMPORTANTE: Este actions requiere definir un parametro de entrada que seria el nombre del repositorio que deseas eliminar.

## Instrucciones

1. Copiar el llamado del action en el maketplace de GitHub. Recomendamos usar siempre la ultima versión.

Ejemplo:

<p align="center">
  <img width="561" height="60" alt="action" src="public/img/action_one.png">
</p>

2. Pega en tu workflow y añade la etiqueta with: añadiendo el parametro workspace_repository: .

Ejemplo:

<p align="center">
  <img width="535" height="107" alt="action_with" src="public/img/action2.png">
</p>

Se debe indicar el valor que corresponde. Nota: se puedes colocar los valores directos otra forma de trabajar es variabilizar los valores.

Ejemplo 2:

<p align="center">
  <img width="585" height="102" alt="action_with_variables" src="public/img/action3.png">
</p>

## Ejecución por consola

- rm -rf _actions
- rm -rf my_repository