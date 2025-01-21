<!-- PROJECT LOGO -->
<br />
<div align="center">

<h1 align="center">Laboratorio 1</h1>

  <p align="center">
    Manejo basico de git y github
    <br />
  </p>
</div>

</br>

> [!NOTE]
> La guia para desarrollar este trabajo es la siguiente: https://github.com/CVDS-ESCUELAING/Laboratory2025/blob/main/LAB01.md

</br>

<!-- ABOUT THE PROJECT -->
## Parte individual

Para comenzar, esta parte tiene como objetivo aprender los comandos básicos de git y su correcta vinculación con repositorios locales.
En primer lugar, vamos a crear un repositorio remoto en GitHub, para ello se selecciona la respectiva opción que nos manda a la pantalla
donde crearemos un repo completamente vacío, tal como se ve la siguiente imagen.

![a](/Assets/create.png)

Tras la creación, se nos da una serie de pasos sugeridos para realizar la conexión del repositorio remoto a uno local, donde podemos 
ver las siguientes opciones:
- Clonar el repositorio mediante el comando en consola `git clone` y la URL que nos proporcionan dependiendo si elegimos la opción
  HTTPS que simplemente es el link del repositorio, o por SSH que es mediante una clave que vincula el dispositivo con la cuenta de GitHub.
  A partir de este clon, se puede modificar el repositorio local generado.
- Crear un repositorio local en un directorio con el comando `git init`, para luego manipular este repositorio y vincularlo al remoto que
  creamos mediante el comando `git remote add`, de modo que al realizar un push se actualiza el repositorio remoto. También, se puede
  Únicamente generar y subir la rama principal al repositorio y de igual forma quedaría vinculado.

![a](/Assets/init.png)

En mi caso, mi computadora ya tenía las credenciales configuradas con anterioridad, por lo que conjunto a una clave SSH fue posible 
clonar el repositorio y manipularlo sin ningún tipo de restricción. De este modo se realizaron las siguientes acciones para completar
la primera parte del laboratorio:
- Clonar el repositorio mediante SSH y `git clone`.
- Crear el este archivo README.
- Validar es estado de los archivos con `git status`.
- Añadir archivos al área de preparación con `git add .`, siendo el punto el indicativo que afecte a todos los archivos nuevos, removidos o modificados.
- Realizar el commit para guardar los cambios de forma local.
- Subir el commit con los cambios al repositorio remoto con `git push`.

![a](/Assets/clone.png)
![a](/Assets/comands.png)

De otro modo, hubiera tenido que usar los siguientes comandos para poder validar las credenciales de mi GitHub, pues estas son necesarias para comunicarse con
la plataforma que se esté usando para el repositorio remoto:
- `git config --global user.name "Tu Nombre"`
- `git config --global user.email "tu_correo@example.com"`
Donde el global es opcional, pues sin este solo se añaden las credenciales en el repositorio local.

Finalmente, se da por culminada la primera parte del laboratorio con este documento en sus primeras instancias y repitiendo el proceso para añadir  la carpeta que alberga las imágenes.

</br>

<!-- GETTING STARTED -->
## Parte en parejas

This


<!-- CONTACT -->
## Contact

Andrés Felipe Chavarro Plazas -- andres.chavarro-p@mail.escuelaing.edu.co
