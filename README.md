# Curso de angular
- ng new nombre del proyecto
- ng serve, con esto inicializamos el servidor
## Creación de componentes
-Generar la estructura de un componente. Ejemplo: Listar los proyectos para consumir una API
ng generate component project-list

# Curso 3 
- Para abreviar el comando anterior se realiza de la siguiente forma:
 ng g c header
 
## Inicializar el servidor y compilar en puerto 4200
ng serve

## ruta de la practica ya terminada
 - https://github.com/webtrainingmx/angular-project-manager-temporal/blob/master/src/app/common/header/header.component.html

# Curso 4
## ruta de la practica ya terminada

https://github.com/webtrainingmx/angular-project-manager/blob/master/src/app/auth/project-list/project-list.component.html
- Se crea el componente loader con: ng g c loader, dentro de common

## se agrega funcionalidad de cargado por medio de un cdm
- spinkit
- https://cdnjs.com/libraries/spinkit 
- https://github.com/tobiasahlin/SpinKit/blob/master/examples/11-folding-cube.html

# Curso 5 Preguntas y respuestas
## Notas Git Preguntas y respuesta

- git add . y git all son lo mismo

- Servidores: digital ocean, linode 50% mas barato que digital oceab, namecheap, 
cloudFrond CDN Amazon (nginx, apache2)
- scope( alcances ) de variables entre los componentes: 
  - http://blog.webtraining.zone/compartiendo-informacion-entre-componentes-con-reactivex-en-angular-4/
  
- ng build : lo que hace es empaquetar todo los modulos en una carpeta llamada *dist*
donde se instala toda nuestra logica de forma optimizada para que se pueda subir al
servidor, cuando es ng build --prod, genera una version comprimida para produccion, 
con archivos mas pequeños. Podemos hacer la prueba con la instruccion *live-server .*

- El live-server . ,se debe instalar de forma global: 
  npm install live-server -g
  - se debe correr el live-server dentro de la carpeta /dist de lo contrario no funara

- La mejor arquitectura escalable es como recomienda google: cada componente tiene que tener
una carpeta.
