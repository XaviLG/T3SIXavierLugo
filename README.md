# Partiendo de tu directorio de inicio, realiza cada uno de los siguientes apartados:

1. A. Haz que tu directorio de trabajo actual sea el directorio padre de tu directorio de inicio.

Para posicionarte en el directorio padre de tu directorio de inicio se puede usar el siguiente comando.

~~~
cd ../
~~~

>Nota: el ../  quiere decir que queremos ir a una carpeta anterior a la actual.

2. Visualiza la ruta de tu directorio de trabajo actual

Para visualizar la ruta en la que nos encontramos usamos el siguiente comando.

~~~
pwd
~~~

La salida ne mi caso seria:
~~~
/home
~~~

3. Obtén un listado de todos los ficheros/directorios que cuelgan de tu directorio de trabajo actual.

Para obtener una lista de los directorios de trabajo se usa el siguiente comando

~~~
ls
~~~
La salida en mi caso seria: 
~~~
xavier
~~~
>Nota: el comando ls lista los archivos o directorios que no estan ocultos.

4. Realiza un listado recursivo de tu directorio de inicio.

Para realizar un listado recurisvo usamos el comando ls con la siguiente opcion.

~~~
ls -R
~~~

5. Obtén la ayuda del comando passwd

Usamos el siguiente comando.

~~~
passwd -h o --help
~~~ 

>Nota: La salida de este comando es muy larga, ya que nos muestra todas las opciones del comando passwd y como usarlo.

6. Obtén la fecha y la hora del sistema

Para obtener la fecha y la hora usamos el siguiente comando.

~~~
date 
~~~

La salida seria la siguiente:
~~~
luns 21 nov 2022 12:48:00 CET
~~~
>Nota: si usas el comando --help o -h puedes ver las opciones para modificar la salida de datos de este comando.

7. Usando un solo comando posiciónate en tu directorio de inicio.

Para hacerlo usamos el siguiente comando

~~~
cd 
~~~

>Nota: por defecto el comando cd nos lleva a nuestro directorio de inicio.

8. Crea un fichero materias que contenga el nombre de las materias en las que te has matriculado (cada una en una línea distinta).

Para crear el fichero se puede usar cualquier editor de texto, pero yo voy a usar cat el cual viene por defecto y no abre ninguna interfaz.

~~~ 
cat > materias
FOL
SISTEMAS INFORMATICO
PROGRAMACION

...
~~~

>Nota: siempre se pone ">" y a continuacion "nombreDelArchivo".

A continuacion de introducir el comando podremos escribir en la consola y le daremos al enter para saltar una linea.

>Nota: En el caso de cat para guardar el archivo se usa "ctrl + D", pero dependiendo del editor puede ser diferente.

9. Con un solo comando, crea dos directorios grado y lru

Para crear directorios se usa el siguiente comando.

~~~
mkdir grado Iru
~~~ 

>Nota: siempre se usa "mkdir" y acontinuacion "nombreDelDirectorio".

10. Usando un solo comando, mueve tu fichero materias para que cuelgue de tu directorio grado pero con el nombre asignaturas.

Para mover ficheros se usa el siguiente comando.

~~~
mv materias grados/asignaturas
~~~

>Nota: siempre se usa "mv" acontinuacion "nombreDirectorio/Archivo" y por siguiente "rutaDestino". Tambien puedes cambiar el nombre del archivo simplemente escribiendo el nuevo nombre que le quieres dar, por ejemplo:

~~~
mv materias grados/asignaturas

mv materias asignaturas
~~~

11. Visualiza los ficheros/directorios de tu directorio de trabajo actual y responde a la siguiente cuestión: ¿dónde está tu fichero materias?

Para visualiar usamos el comando previanmente explicado "ls".

En este caso el fichero materias lo movimos en el paso anterior al directorio grados y le asignamos el nombre asignaturas.

12. Posiciónate en tu directorio grado.

Usamos el comando previamente visto.

~~~
cd grado
~~~ 


13. Elimina el fichero asignaturas

Para eliminar ficheros y directorios se usa el siguiente comando.

~~~
rm aisgnaturas
~~~

>Nota: para eliminar directorios hay que usar la opcion -R, es decir "rm -R nombreDirectorio"
>Nota: Puedes borrar los ficheros que quieres aunque esten en otra carpeta, solo tienes que usar la ruta donde se encuentra el fichero a eliminar.

14. Sube al directorio de inicio.

Usamos el comando previamente dicho

~~~
cd
~~~

15. Con un solo comando elimina los directorios grados y Iru.

Usamos el comando el comando previamente explicado

~~~
rm -R grados Iru
~~~
