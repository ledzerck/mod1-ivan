## Hola Iván
![](https://http2.mlstatic.com/D_NQ_NP_2X_937616-MLM52691732664_122022-F.webp)

Muy buen trabajo Iván, hasta ahora has sido de los pocos que hizo uso de las etiquetas semánticas para agrupar el contenido, aunque hay algunos detalles a corregir. En cuánto a la estructura cumple con todo lo requerido y tu código es limpio y fácil de leer.

Entre los puntos a destacar:

- La utilización de etiquetas semánticas. Te faltó usar nav para el menú de navegación y main para el contenido principal. Poco a poco te irás familiarizando con las estructuras básicas.

- La forma de organizar la información es muy clara en cada página, aún cuando no estamos usando CSS para el diseño, facilitas la lectura por la forma de organización.

En cuanto a los puntos de mejora en general:

- Las imágenes que usaste son de links externos, esto es válido, pero recuerda que al estar alojadas en el servidor de alguien más, dependes de que ese servidor esté funcionando, por lo que es recomendable usar imágenes de tu propio proyecto, en tu servidor.

- En los archivos de tu repositorio viene un archivo oculto (.vscode) que trae la configuración de tu Visual Studio Code. Para evitar que se suban este tipo de archivos puedes usar un archivo .gitignore:

El archivo .gitignore se usa para decirle a Git qué archivos o directorios no deben ser rastreados o versionados en tu repositorio. Esto es útil para evitar que archivos temporales, configuraciones locales o artefactos de compilación sean incluidos en el control de versiones.

Dentro de tu repositorio, puedes crear este archivo .gitignore y dentro puede contener algo como esto:

```
# Ignorar archivos temporales de IDE
.vscode/

```

En [este enlace](https://desarrolloweb.com/articulos/eliminar-archivos-git-gitignore.html) puedes revisar más a detalle como eliminar este archivo y quitarle el seguimiento que hace git

En el pull request que le hice a tu proyecto, vas a ver como comentario los puntos que hay que corregir en cada archivo.

Te agradezco mucho el tiempo Iván, espero que este feedback te ayude y que sigas entusiasmada con el curso :D