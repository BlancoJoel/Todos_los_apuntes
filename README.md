## Todos_los_apuntes
Aqui estan todos los apuntes que tomaremos en clase.

Antes de todo vamos a explicar como creamos un repositorio y lo ponemos en marcha.

Para crear un repositorio hacemos lo siguiente, entramos en github, sino tenemos una cuenta nos la creamos, despues le damos a __New__ > le ponemos el nombre que queramos a nuestro repositorio, la descripción se la ponemos sino no pasa nada > lo dejamos en publico a no ser que queramos que sea privado, en ese caso seleccionamos esa opción, donde pone el siguiente texto: (Initialize this repository with:) le damos al cuadradito, esto es para que nos cree un file y no lo tengamos que hacer nosotros ya que asi es mas facil y con esto le damos al botón verde que pone (Create repository).

Una vez hecho esto nos dejara en nuestro repositorio, ahora solo tenemos que clonarlo, para ello le damos al botón verde que pone (<> code) y copiamos la URL que nos da en la opción de HHTTPS, vamos al CMD o simbolo de sistema, nos ponemos en la carpeta que queramos tenerlo y hacemos la siguiente lista de comandas.


1. Pasos a seguir
    1. git clone + URL
    2. git init //Es para iniciar el repositorio
    3. git branch //Para ver en que rama estamos trabajando nos tendria que salir que estamos en main sino hacemos el siguiente paso
    4. git branch -M main //Es para indicarle en que rama trabajaremos
    5. git add //Es para añadir un archivo a la zona intermedia que luego con el commit se subira, si ponemos un . se suben todos
    6. git commit -m "" //Para subir los archivos, las comillas son para añadir un mensaje
    7. git push origin main
  
Y esto es lo q haremos una vez hecho el ultimo ya lo podremos ver en el git hub.
   



## MARKDOWN


## Encabezados

```
Estos son los encabezados que hemos visto en clase.
Los generamos poniendo un hastag (#) podemos poner hasta 6, siendo el 1 el más grande y el 6 el más pequeño

# H1
## H2
### H3
#### H4
##### H5
###### H6

```

# H1
## H2
### H3
#### H4
##### H5
###### H6


## Negrita y cursiva


### Texto en negrita 

Ahora veremos como poner texto tanto en negrita como en cursiva, tenemos varias formas

Para poner un texto o parte de en negrita lo haremos de la sigüiente forma: utilizaremos o bien 2 guiones bajos o 2 asteriscos al principio y final de la palabra/parte del texto, como vemos en el ejemplo de abajo y mas abajo vemos como queda

```
__Texto en negrita con guines bajos__
**Texto en negrita con asteriscos**
```

__Texto en negrita con guines bajos__

**Texto en negrita con asteriscos**


### Texto en cursiva

Para poner un texto o parte de en cursiva lo haremos de la sigüiente forma: utilizaremos o bien 1 guione bajo o 1 asterisco al principio y final de la palabra/parte del texto, como vemos en el ejemplo de abajo y mas abajo vemos como queda

```
_Texto en cursiva con guines bajos_
*Texto en cursiva con asteriscos*
```

_Texto en cursiva con guines bajos_

*Texto en cursiva con asteriscos*


### Texto en negrita y cursiva a la vez

Si os preguntais si se pueden juntar en un mismo texto la negrita y la cursiva, la respuesta es q si.

Se hace de la sigüiente manera pero vamos a matizar una cosa, y es que la gente pensara si 1 asterisco o guion bajo es cursiva y 2 asteriscos o guiones bajos es negrita, y si junto las dos cosas es decir pongo 3 asteriscos o guiones bajos y ya estaria, pero la realidad es que no es asi, basicamente porque esta union no hace nada, si nos fijamos tenemos 2 formas de poner tanto la negrita como la cursiva, eso esta hecho para que podamos combinarlos, hay que poner primero . Ej abajo

```
**_Texto en cursiva y negrita 1r opción_**
*__Texto en cursiva y negrita 2n opción__*
```

**_Texto en cursiva y negrita 1r opción_**

*__Texto en cursiva y negrita 2n opción__*

__*Texto en cursiva y negrita 2n opción*__




## Listas

Para hacer una lista, simplemente pondremos un punto y un espacio, seguido del texto y después de eso añadiremos un punto y un espacio.

1. Primer punto de la lista
    1. Primer elemento de la sublista
    2. Segundo elemento de la sublista
2. Segundo punto de la lista
    * Primer elemento de la sublista 2
    * Segundo elemento de la sublista 2
3. Tercer punto de la lista
    - Primer elemento de la sublista 3
    + Segundo elemento de la sublista 3

* Primer punto de lista desordenada
- Segundo punto de lista desordenada
+ Tercer punto de la lista desordenada




## Links

Los links los pondremos de la siguiente forma: **[textoClicable](URL "Titulo opcional")**

[textoClicable](URL "Titulo opcional")
[Pagina web jesuites Bellvitge](https://www.fje.edu/ca/fje "Titulo opcional")





## Poner una imagen

Para poner una imagen utilizaremos la siguiente nomenclatura ![TextoAlternativo](UbicacionDeLaImagen "Titulo opcional")

![TextoAlternativo](UbicacionDeLaImagen "Titulo opcional")
![Imagen Venom Carnage](https://github.com/BlancoJoel/Aprendizaje_Markdown/blob/main/imagen.jpg "Titulo opcional")



## Tablas

Para poner una tabla la haremos como se ve abajo, los guiones es para darle la anchura que deseemos cuantos mas pongamos mas habra, sino ponemos nada se ajustara al texto mas largo, la posicion de los puntos es para decidir donde estara la informacion, es decir si no ponemos nada se pondra automaticamente en la izquierd, si ponemos dos puntos en el lado derecho la informacion la encontraremos en la parte de la derecha, en cambio si ponemos dos puntos a la izquierda y otros dos en la derecha la info la encontraremos en medio.

|Titulo 1 | Titulo 2 | Titulo 3 |
|----------|:--------------:|-------------:|
|SMX2 |Curso 2425|25|
|ASIX 1|Curso 2425|33|
|DAW2|Curso 2425|32|


# HTML



