# pokedex_despliegue

PARA EL DESPLIEGUE DE ESTA PAGINA SE UTILIZO NETLIFY 


EL DESPLIEGUE DE ESTA APLICACION SE REALIZO POR CONSOLA CON VISUAL STUDIO CODE

LOS PASOS PARA EL DESPLIEGUE FUERON:

LUEGO DE ESTAR REGISTRADO EN NETLIFY

ESCRIBIMOS LOS SIGUIENTE COMANDO EN LA CONSOLA:

1. ´´´npm i -g netlify-cli ´´´
2. (este comando nos servira para instalar el cli de netlify para inciarlo en el equipo )  

2. Luego de que termine se escribe el comando (netlify status) este nos servira para ver el estado de la sesion y ver que cuenta esta conectada con netlify

Nota: debemos estar en la ruta raiz del proyecto

3. Ejecutamos el comando ng build --prod (esto nos generara la carpeta DIST/POKEDEX-ANGULAR la cual sera la que se desplegara en el servidor
4. Ejecutamos el comando netlify deploy --prod  (en este comando primero si no estamos loggeados nos abrira una pestaña en el navegador para hacerlo luego de esto nos preguntara si queremos crear un sitio nuevo y tambien nos pedira seleccionar un team ya que netlify maneja este tema "Como equipos o espacios de trabajo") despues de seleccionar todo eso nos pedira que ingresemos el nombre del sitio que vamos a crear

![image](https://user-images.githubusercontent.com/52515863/199610129-f9f05e78-9d5b-479f-b475-16fcb2e3e805.png)


6. Nos pedira la ruta donde tenemos el despliegue listo que seria la carpeta DIST/POKEDEX luego de ingresar la ruta nos creara el sitio
![image](https://user-images.githubusercontent.com/52515863/199610286-d9618314-23e6-420a-bfe4-41a7f0345b24.png)

