# api-rest-boilerplate

Api Rest desarrollando con Django Rest Framework sobre el framework Django 2.0. Se incorporan las siguientes caractersticas:

* está basado en Django 2.0
* Autenticación basada en tokens.
* Pruebas unitarias: coverage run manage.py test general -v 2
* Hemos establecido que el usuario de la API sea un email, midificando el modelo estándar de usuario en Django. Esto nos facilita las cosas para integrar en nuestras aplicaciones a los colaboradores de la correduría.

## ¿Dónde utilizamos esta API REST?

API son unas siglas que significan Application Programming Interface, o Interfaz de Programación de Aplicaciones. Las API pretenden que los desarrolladores de diferentes áreas de nuestra empresa interactúen con los datos de la aplicación de un modo planificado y ordenado. Dicha comunicación se realiza con formato JSON y arquitectura API REST.

REST, siglas de **Transferencia de Estado Representacional** es un estilo de arquitectura que utilizamos para diseñar aplicaciones en red, ya sean aplicaciones web, de escritorio o móviles. API pretende ser una alternativa a REST CORBA, RPC o SOAP. Y para conseguirlo nuestra API REST utiliza el protocolo HTTP.

Un ejemplo de utilización de nuestra API REST lo tenemos en nuestra aplicación para [colaboradores de la correduría](https://www.jlaasociados.es/trabaja-con-nosotros/). Cuando uno de nuestros colaboradores solicita a su aplicación consultar el estado de sus recibos, dicha aplicación envía una petición HTTP desde el navegador (cliente Javascript) a nuestra API. Dicha petición tendrá una respuesta, estableciendo una operación que se ha completado con éxito.

## Cliente Vue.JS 2.0

Vue.js es un framework progresivo. Ésto nos permte usarlo tanto para cosas sencillas como para desarrollos más complejos. Además, tanto el rendimiento como la experiencia de desarrollo son excelentes.
