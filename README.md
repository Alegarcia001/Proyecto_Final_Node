# Node_Proyecto
Contenido .ENV:
PORT=4000
USER=cursonode
PASSWORD=kZdiQvPjtKADq54c
DBNAME=dbSalvarVidaSubmarina

//Ejecutar proyecto
Cuando habras el proyecto debes añadir el archivo ".ENV" con el contenido mencionado anteriormente, debe de crearse en la carpeta principal.
Luego debes crear un terminal y ejecutar el siguiente comando "npm install nodemon" o "npm install -g nodemon" para instalar la carpeta de node_modules.
Despues para lanzar el proyecto debes lanzar la base de datos con el siguiente comando: "npx nodemon .\app.js".
Una vez tengamos la base de datos conectada nos vamos a google y escribimos la siguiente ruta: "localhost:4000", nos abrira la página principal para iniciar sesion, donde en el parametro rol solo puedes introducir rio, playa o lago que son cada uno de los roles del proyecto. Una vez iniciemos sesion nos sale la pagina principal con 4 botones donde cada uno de ellos te dirige a la pagina de datos correspondiente.
Proyecto realizado por:
  - Pablo Andersen Cabello
  - Alejandro González García
