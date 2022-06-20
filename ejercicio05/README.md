## Ejercicio N°5

**explorando Dockerfile commands**

- HEALTHCHECK: **Dockerfile Healthcheck** es una opción del sistema que se encarga de indicarle al daemon de Docker **cómo comprobar que el contenedor se encuentre funcionando**, es decir, le dice cómo probar un determinado container de Docker para verificar si aún se encuentra realizando sus labores.
  Una de las principales características de la instrucción de Dockerfile Healthcheck es que cuenta con dos opciones principales, denominadas **HEALTHCHECK [OPTIONS] CMD command** y **HEALTCHECK NONE**.
  La primera opción hace referencia a la herramienta que **permite verificar el estado del container**, a través del uso y ejecución de alguno de los comandos disponibles para ese contenedor determinado.
  La segunda opción se encuentra relacionada con el **proceso de inhabilitación de cualquiera de los controles de salud que pudieran haber sido heredados** por la base imagen o imagen base.

- ONBUILD: La declaración le **permite establecer disparadores** dentro de una imagen. **Sus disparadores se ejecutarán más tarde**, cuando la imagen se utilice como base para otra.
  Se utiliza con mayor frecuencia en imágenes de utilidades que automatizan tareas como la compilación de código.

- VOLUME: Con un Docker volume (también volumen), es posible **intercambiar datos entre contenedores** o guardar los datos de un Docker container de manera **permanente**.
  Un **container volume** “vive” fuera del propio contenedor en el ordenador host. Fuera del container, el volumen se comporta como una carpeta en la que se pueden almacenar datos y desde la que se pueden recuperar datos. Se trata del mount point de un directorio en el host.
