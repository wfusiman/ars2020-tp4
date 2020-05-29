
# ARQUITECTURA DE REDES Y SERVICIOS - 2020 
## RESOLUCION TRABAJO PRACTICO 4

1. Desarrollo de proyecto en la plataforma Google Firebase, siguiendo el código: \
https://codelabs.developers.google.com/codelabs/firebase-web/#0 
2. Agregando la opcion que permite autenticación con Facebook, desde el menu Sign-in.
    
    Codigo del proyecto: https://github.com/wfusiman/ars2020-tp4.git
    
    Aplicacion web desplegada: 
    https://friendlychat-5b9e3.web.app/
    https://friendlychat-5b9e3.firebaseapp.com/

## RESOLUCION TRABAJO PRACTICO 5

1. Inicialmente se cargan los últimos 10 mensajes, luego mediante el botón "cargar" se cargan de a 5 mensajes anteriores por cada vez que se presiona.

2. https://codelabs.developers.google.com/codelabs/firebase-cloud-functions/#4

3. Permite ver la versión no borrosa de una imagen. \
Al cargar una imagen en la aplicación, se realiza la carga en el Cloud Storage de la misma imagen dos veces, de tal manera que una de ellas no se modificara (llevara antepuesto la cadena ’original-’ al principio del nombre del archivo), y la otra sera procesada y difuminada al momento de cargarse en el cloud Storage. También se generan las url publicas para las dos imágenes. \
Cuando se realiza la carga de los mensajes, en el caso de una imagen se realiza la carga de las dos imágenes, y se mostrara por defecto la imagen difusa, de tal manera que haciendo click sobre ella se muestra la imagen original. \ 
También es posible volver a ver la imagen difusa haciendo click sobre la imagen original.
