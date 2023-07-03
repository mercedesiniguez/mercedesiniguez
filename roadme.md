

## VIAJES RECOMENDADOS

Este es un portal online donde los usuarios pueden escoger viajes, hoteles y experiencias gracias a las opiniones de quienes ya han utilizado y disfrutado de esos viajes y experiencias. Existe un sistema de votación y comentarios de los que se nutre la página web. En la actualidad, los viajeros pueden utilizar este portal para planear cada detalle de sus viajes, desde dónde se van a hospedar hasta las atracciones que van a visitar.

## ¿CÓMO COMENZAR?
Para ejecutar el proyecto necesitas:
````Node Package Manager (NPM)
React
Usage

- En el directorio del proyecto, descárgate el repositorio, abre el terminal en tu editor y ejecuta el comando:
npm start

Ejecuta la aplicación en el modo de desarrollo.
Abre http://localhost:3000 para verla en tu navegador.

La página se recargará cuando realices cambios.
También puedes ver cualquier error en la consola.

npm test
Lanza el ejecutor de pruebas en el modo de observación interactivo.
Consulta la sección sobre ejecución de pruebas para obtener más información.

npm run build
Construye la aplicación para producción en la carpeta build.
Agrupa correctamente React en modo de producción y optimiza la compilación para obtener el mejor rendimiento.

npm run eject
Nota: esta es una operación unidireccional. Una vez que se expulsa, ¡no se puede volver atrás!

 ## INSTALACIÓN
 $ git clone 
 $ cd project
 $ npm install

 ## HERRAMIENTAS Y LENGUAJES UTILIZADOS
 <p>
<img align="left" alt="Visual Studio Code" width="26px" src="https://camo.githubusercontent.com/5fa137d222dde7b69acd22c6572a065ce3656e6ffa1f5e88c1b5c7a935af3cc6/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f64657669636f6e732f64657669636f6e2f69636f6e732f7673636f64652f7673636f64652d6f726967696e616c2e737667" data-canonical-src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" style="max-width: 100%;">
<img align="left" alt="JavaScript" width="26px" src="https://camo.githubusercontent.com/442c452cb73752bb1914ce03fce2017056d651a2099696b8594ddf5ccc74825e/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f64657669636f6e732f64657669636f6e2f69636f6e732f6a6176617363726970742f6a6176617363726970742d6f726967696e616c2e737667" data-canonical-src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" style="max-width: 100%;">
<img align="left" alt="MySQL" width="26px" src="https://camo.githubusercontent.com/2582ec2237a3a1fbd34e9b57332b72be27a7facb32abe7c2335e5f86e5f457a8/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f64657669636f6e732f64657669636f6e2f69636f6e732f6d7973716c2f6d7973716c2d6f726967696e616c2e737667" data-canonical-src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" style="max-width: 100%;">
<img align="left" alt="Node.js" width="26px" src="https://camo.githubusercontent.com/900baefb89e187c8b32cdbb3b440d1502fe8f30a1a335cc5dc5868af0142f8b1/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f64657669636f6e732f64657669636f6e2f69636f6e732f6e6f64656a732f6e6f64656a732d6f726967696e616c2e737667" data-canonical-src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" style="max-width: 100%;">
<img align="left" alt="GitHub" width="26px" src="https://user-images.githubusercontent.com/3369400/139448065-39a229ba-4b06-434b-bc67-616e2ed80c8f.png" style="max-width: 100%;"></p><BR>

## Datos de ejemplo

La base de datos travelexperience se inicializa con los siguientes datos de ejemplo:

### Tabla users

| **id** |          **email**         | **password** |
|:------:|:--------------------------:|:------------:|
|    1   | ilethem0@google.com.au     | 993870144    |
|    2   | kmungan1@howstuffworks.com | 497494899    |
|    3   | ydibbert2@businesswire.com | 776631050    |
|    4   | tmcgorley3@studiopress.com | 921948685    |
|    5   | eimbrey4@cpanel.net        | 304168000    |

### Tabla Places

| **id** | **title**                 | **shortDescription**                                         |    **city**   |     **country**    | **user_id** |
|:------:|---------------------------|--------------------------------------------------------------|:-------------:|:------------------:|-------------|
|    1   | Nadando con los tiburones | Un día de submarinismo con los tiburones blancos             |    Ningaloo   |      Australia     | 1           |
|    2   | Avistamiento de ballenas  | Ven a ver a las ballenas jorobadas                           | Santo Domingo | Dominican Republic | 1           |
|    3   | El Salto Ángel            | Ven a conocer el salto de agua más alto del mundo            |    Canaima    |      Venezuela     | 2           |
|    4   | Mercado de San Miguel     | Mercado emblemático para los amantes de la buena gastronomía |     Madrid    |        Spain       | 5           |

### Tabla Votes

| **id** | **vote** |    **comment**   | **user_id** | **place_id** |
|:------:|:--------:|:----------------:|:-----------:|:------------:|
|    1   |     5    | 100% Recommended |      3      |       1      |
|    2   |     3    | not so good      |      2      |       2      |
|    3   |     1    | so bad           |      3      |       2      |
|    4   |     5    | Amazing          |      5      |       1      |
|    5   |     5    | Must do          |      4      |       3      |
|    6   |     5    | Stunning         |      1      |       4      |

### Categories

| **Category 1** | **Category 2** | **Category 3** | **Category 4** | **Category 5** | **Category 6** |
|:--------------:|:--------------:|:--------------:|:--------------:|:--------------:|----------------|
|     Nature     |    Adventure   | Cultural       |      Sport     |      Relax     | Romantic       |

## AUTORES
  KAROL BRACHO, [bykarol](https://www.linkedin.com/in/karolbrachoyanez/)
  
  JON MARTÍNEZ BIDEZABAL, [JonBidezabal](https://www.linkedin.com/in/jonmartinezdev)
  
  ISABEL ABAD,  [IsaAbad](https://www.linkedin.com/in/isabel-abad-cami%C3%B1os/)
  
  MERCEDES IÑIGUEZ, [mercedesiniguez](https://www.linkedin.com/in/mercedes-iniguez-quintela-1424ba7/)

## AGRADECIMIENTOS
[Hack a Boss](https://www.hackaboss.com/)
    
## CONTRIBUCIONES
 Si quieres contribuir en este proyecto, ponte en contacto con nosotros
   
¿CÓMO COMENZAR?
Configurar el archivo .env (utilizar el archivo .env.example que hemos añadido como ejemplo).

Instalar las dependencias:
npm install

Inicializar la base de datos con el siguiente comando:
npm run initDB

Levantar el servidor:

Modo desarrollo (nodemon):
npm run dev

Modo normal:
npm start

npm test
Launches the test runner in the interactive watch mode.
See the section about running tests for more information.

npm run build
Builds the app for production to the build folder.
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.
Your app is ready to be deployed!

See the section about deployment for more information.

npm run eject
Note: this is a one-way operation. Once you eject, you can't go back!

If you aren't satisfied with the build tool and configuration choices, you can eject at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except eject will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use eject. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

Learn More

Mira Deployment para conocer como desplegar el proyecto.

Pre-requisitos 📋
Que cosas necesitas para instalar el software y como instalarlas

Da un ejemplo
Instalación 🔧
Una serie de ejemplos paso a paso que te dice lo que debes ejecutar para tener un entorno de desarrollo ejecutandose

Dí cómo será ese paso

Da un ejemplo
Y repite

hasta finalizar
Finaliza con un ejemplo de cómo obtener datos del sistema o como usarlos para una pequeña demo

Ejecutando las pruebas ⚙️
Explica como ejecutar las pruebas automatizadas para este sistema

Analice las pruebas end-to-end 🔩
Explica que verifican estas pruebas y por qué

Da un ejemplo
Y las pruebas de estilo de codificación ⌨️
Explica que verifican estas pruebas y por qué

Da un ejemplo
Despliegue 📦
Agrega notas adicionales sobre como hacer deploy

Construido con 🛠️
Menciona las herramientas que utilizaste para crear tu proyecto

Dropwizard - El framework web usado
Maven - Manejador de dependencias
ROME - Usado para generar RSS
Contribuyendo 🖇️
Por favor lee el CONTRIBUTING.md para detalles de nuestro código de conducta, y el proceso para enviarnos pull requests.

Wiki 📖
Puedes encontrar mucho más de cómo utilizar este proyecto en nuestra Wiki

Versionado 📌
Usamos SemVer para el versionado. Para todas las versiones disponibles, mira los tags en este repositorio.

Autores ✒️
Menciona a todos aquellos que ayudaron a levantar el proyecto desde sus inicios

Andrés Villanueva - Trabajo Inicial - villanuevand
Fulanito Detal - Documentación - fulanitodetal
También puedes mirar la lista de todos los contribuyentes quíenes han participado en este proyecto.

Licencia 📄
Este proyecto está bajo la Licencia (Tu Licencia) - mira el archivo LICENSE.md para detalles
