Markdown
# Manejo de Ramas y Repositorios Remotos

Acá explicamos los comandos utilizados para trabajar en paralelo sin romper el código original y para sincronizar nuestro trabajo con GitHub.

### `git branch`
Nos permite gestionar las ramas (líneas de tiempo alternativas). Si lo ejecutamos solo, nos lista las ramas que tenemos. Si le agregamos un nombre (`git branch nombre-rama`), crea una rama nueva.

### `git checkout` (o `git switch`)
Se usa para "viajar" o saltar de una rama a otra. Por ejemplo, `git checkout main` nos devuelve a la rama principal. Si usamos `git checkout -b nombre-rama`, creamos una rama nueva y nos movemos a ella en un solo paso.

### `git merge`
Sirve para fusionar o unir los cambios de una rama secundaria hacia la rama en la que estamos parados. Por ejemplo, si estamos en `main` y ejecutamos `git merge feat/nueva-funcion`, traemos todo ese trabajo a la rama principal.

### `git clone`
Se usa una sola vez por proyecto. Hace una copia exacta de un repositorio que está en la nube (GitHub) y lo descarga a nuestra computadora local para que podamos empezar a trabajar.

### `git push`
"Empuja" o sube los commits que hicimos en nuestra computadora local hacia el repositorio remoto en GitHub. Así nuestros compañeros pueden ver el trabajo que hicimos.

### `git pull`
Hace lo contrario al push. Descarga los cambios más recientes que están en GitHub y los fusiona automáticamente en nuestra computadora. Es fundamental ejecutarlo antes de empezar a trabajar para asegurarse de tener la última versión del proyecto.