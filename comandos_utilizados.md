# Comandos utilizados en práctica de clonación

## Git clone

Con este comando clonamos un repositorio que haya remoto a nuestro ordenador.

```
git clone URL_REPO
```

## Git checkout

Con este comando podemos movernos libremente por las ramas de nuestro proyecto.
```
git checkout RAMA
```


## Git add

Añadimos todos los documentos y archivos que queramos subir a nuestra rama.

```
git add NOMBREFICHERO
```

## Git commit

Este comando lo utilizamos para hacer el commit para que posteriormente podamos subir todas las modificaciones que hayamos especificado en este paso.

```
git commit -m "MENSAJE DEL COMMIT"
```

## Git branch
Si queremos ver todas las ramas de nuestro proyecto utilizamos este comando

```
git branch
```

Si lo que queremos es crear una rama nueva, utilizaremos este comando

```
git branch NOMBREDELARAMA
```

## Git status

Para ver como está el estado de nuestros ficheros y las ramas utilizamos este comando.
```
git status
```

## Git remote

Para ver dónde está alojado en remoto nuestro repositorio, lo podemos ver con:

```
git remote -v
```

Si queremos eliminar nuestro repositorio origen por problemas de permisos o por cualquier otra cosa, lo podemos hacer de esta manera:

```
git remote rm origin
```

Y si no tenemos nada en remoto, lo podemos añadir de esta manera:

```
git remote add origin URL_REPO
```

## Git push

Si queremos subir nuestros archivos a remoto utilizamos

```
git push
```

Si es la primera vez que queremos hacer un push en nuestra rama y nos falta alguna configuración, deberemos utilizar:

```
git push --set-upstream RAMAS
```

## Git merge

Para hacer un merge únicamente tendremos que ejecutar este comando:
```
git merge RAMA
```

Es importante a la hora de hacer el merge, posicionarse en la rama central o rama "main"