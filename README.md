# practicas-yare
Este repositorio es para las practicas de yaré

## Como clonar un repositorio

comando: git clone, me permite clonar un repositorio, el parametro ´URL´ debe ser reemplazado por la url del repositorio.

´´´bash
git clone <url>
´´´

## como subo mis cambios:

1. primero debemos crear un paquete de cambios (commit)

2. Para crear un paquete de cambios, debes añadir cambios a la pila (stack)

    Usamos git ´git add .´ para agregar al stack todos los cambios realizados en la carpeta 
    actual.

    podemos verificar el estado de los cambios usando git status

    ´´´bash
    git status
    ´´´

3. Cuando tus cambios estan listos para ser enviados, se realiza un commit usando el comando 
    git commit

    ´´´bash
    git commit -m "mensaje"
    ´´´

4. Una vez que tenemos un paquete de cambios confirmados (commit), podemos enviar este paquete a el repositorio remoto usando el comando git push

´´´bash
git push
´´´

>[!NOTE]
> La primera vez que se hace un push en otras ramas, se usa -u origin <nombre de la rama>
