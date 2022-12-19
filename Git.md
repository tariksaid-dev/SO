# Características y comandos de Git

Git es un softwre de código libre que proporciona un sistema de control de versiones. En la actualidad, es el más usado del mundo con más de 80 millones de repositorios. Podemos registrarnos gratuitamente en [su página oficial](www.github.com) y [aquí](https://docs.github.com/es) podremos ver la documentación de las distintas herramientas.

## Comandos de git.

A continuación veremos una tabla con los comandos típicos de git:


|Comando|Acción|
|-|-|
|`git init`| Inicia en el directorio donde nos encontramos un sistema de control de versiones|
| `git status` | Hace una comprobación para ver si tenemos archivos sin control o modificados |
|`git add`| Añade el archivo a la zona de control |
|`git commit` | Acepta los cambios de los archivos modificados en la zona de control de manera local|
|`git push`| Sube los cambios desde un repositorio local a uno en línea|
|`git pull`| Descarga cualquier cambio desde un repositorio remoto a el repositorio local |
|`git clone`| Clona un repositorio de GitHub en un directorio local|
|`git branch`| Muestra una lista de las ramas en local y te indica en cuál estás|
| `git log`| Muestra un log de los cambios históricamente aceptados con `git commit` en la rama en la que nos encontramos|
|`git remote`|  Comando para gestionar los repositorios remotos. Sin ninguna flag, nos devuelve el nombre de la rama en remoto en la que estamos. |
___
Cabe destacar que estos comandos pueden llevar modificadores en forma de flag. Por ejemplo, si escribimos: 

```bash
git remote -v
```

Nos devolverá no solo el nombre de la rama remota, si no también su URL o dirección SSH.
