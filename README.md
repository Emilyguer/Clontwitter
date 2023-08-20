# Clon de Twitter Rails App
Este proyecto es un clon de Twitter desarrollado como parte de la prueba de conocimientos de Introducción al Desarrollo de Aplicaciones Web con Ruby on Rails. El objetivo es simular el comportamiento de Twitter en cuanto a la lógica de implementación y publicación de tweets.


## Descripción
El Clon de Twitter Rails App permite a los usuarios crear, leer, actualizar y eliminar tweets. Aunque en la aplicación original de Twitter los tweets están relacionados con usuarios, en este ejercicio nos enfocaremos en el proceso de gestión de tweets y omitiremos la acción de retweet.

## Detalles a Tomar en Cuenta
- Se utiliza el scaffold de Rails para agilizar el desarrollo.
- Las vistas de la aplicación se mantienen para simular un servicio ya establecido.
- La aplicación se sube a Heroku para su acceso en línea.
- Git y GitHub se utilizan para gestionar versiones y cambios.
- Se utiliza Bootstrap para los estilos de la aplicación.

## Insignias

Insignias que muestran metadatos como el estado de la compilación, la cobertura de las pruebas, el estado de las dependencias, etc.

## Visuales

Capturas de pantalla, videos o GIFs que demuestran lo que hace el proyecto y cómo usarlo.

## Empezando 🚀

Estas instrucciones te guiarán para obtener una copia de este proyecto en funcionamiento en tu máquina local para propósitos de desarrollo y pruebas.

## Prerrequisitos 📋

Lista de software y herramientas, incluyendo versiones, que necesitas para instalar y ejecutar este proyecto:

- Sistema Operativo: Ubuntu 22.04.2, Windows 10.
- Lenguaje de Programación Ruby: 3.2.2
- Framework Rails 7.0.7
- PostgreSQL: 14.8
- Bootstrap: 5

## Instalación 🔧

Una guía paso a paso sobre cómo configurar el entorno de desarrollo e instalar todas las dependencias.

### Paso 1

1. Clona este repositorio: `git clone https://github.com/Emilyguer/Clontwitter`
2. Navega al directorio del proyecto: `cd ClonTwitter`
3. Instala las gemas necesarias: `bundle install`
4. Crea la base de datos y realiza las migraciones: `rails db:create db:migrate`
5. Llena la base de datos con datos ficticios: `rails db:seed`
6. Para ejectuar la aplicacion se inciia el servidor local : `rails s`
7. Para acceder a la aplicacion abre tu navegador web y visita : ` http://localhost:3000`


### Paso 2

Ejecutando las Pruebas ⚙️
Instrucciones y ejemplos para ejecutar el conjunto de pruebas.

### Pruebas de Principio a Fin 🔩
Explica qué cubren estas pruebas, por qué son importantes y cómo interpretar sus resultados.

### Pruebas de Estilo de Código ⌨️
Descripción y ejemplos de las pruebas de estilo que estás utilizando.

## Despliegue 📦

Para desplegar la aplicación en un servidor en vivo, sigue estos pasos:

1. Crea una cuenta en Heroku y configura el Heroku CLI.
2. Crea una nueva aplicación en Heroku: `heroku create`
3. Agrega el complemento de base de datos PostgreSQL: `heroku addons:create heroku-postgresql:hobby-dev`
4. Realiza la migración a la base de datos de Heroku: `heroku run rake db:migrate`
5. Llena la base de datos en Heroku con datos ficticios: `heroku run rake db:seed`

## Construido Con 🛠️

Explica qué tecnologías usaste para construir este proyecto. Aquí algunos ejemplos:

- Ruby - El lenguaje utilizado
- Ruby on Rails - El framework web utilizado
- Ruby gems - Gestión de dependencias
- Postgresql - Sistema de base de datos
- Bootstrap - Framework de diseño

## Contribuyendo 🖇️

Las contribuciones son lo que hacen a la comunidad de código abierto un lugar increíble para aprender, inspirar y crear. Cualquier contribución que hagas es muy apreciada. Por favor, lee el CONTRIBUTING.md para detalles sobre nuestro código de conducta, y el proceso para enviarnos pull requests.

## Wiki 📖

Puedes encontrar mucho más sobre cómo usar este proyecto en nuestra Wiki.

## Soporte

Si tienes algún problema o sugerencia, por favor abre un problema aquí.

## Roadmap

Ideas, mejoras planificadas y actualizaciones futuras para el proyecto actual.

## Versionado 📌

Usamos Git para el versionado. Para las versiones disponibles, ve las etiquetas en este repositorio.

## Autores ✒️

Emily Guerrero - Trabajo inicial - Emily Guerrero
Mira también la lista de contribuidores que han participado en este proyecto.

## Licencia 📄

Este proyecto está bajo la Licencia XYZ - ve el archivo LICENSE.md para detalles.

## Expresiones de Gratitud 🎁

Estamos agradecidos por las contribuciones de la comunidad a este proyecto. Si encontraste cualquier valor en este proyecto o quieres contribuir, aquí está lo que puedes hacer:

- Comparte este proyecto con otros
- Invítanos un café ☕
- Inicia un nuevo problema o contribuye con un PR
- Muestra tu agradecimiento diciendo gracias en un nuevo problema.

