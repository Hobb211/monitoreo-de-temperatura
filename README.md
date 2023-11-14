# Sistema de monitoreo de temperatura para un complejo de departamentos
El proyecto consiste en la creación de un sistema que se alimente de la información recibida por sensores, almacene la información historica y la despliegue en un dashboard que muestre el edificio junto con sus departamentos indicando si su temperatura esta dentro del rango aceptable, junto a esto se veran notificaciones generales relacionadas a los departamentos mostrando solo las mas urgentes
## Arquitectura del proyecto
La arquitectura del proyecto se dividira en 1 frontend, 1 backend y 3 bases de datos por determinar las cuales seran 1 Columnar, 1 Documental y 1 SQL
* Columnar: El proposito de la base de datos columnar sera almacenar las mediciones de temperatura de cada departamento, manteniendo una referencia al documento relacionado al departamento en sus metadatos
* Documental: El proposito de la base de datos documental sera almacenar la información relevante del departamento como son la temperatura minima, maxima y optima, además de los comentarios dejados por el administrador del sistema.
* SQL: Se utilizara una base de datos SQL para almacenar la información de los usuarios admitidos por el sistema
