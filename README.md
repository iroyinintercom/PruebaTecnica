# Prueba Técnica - Programador (Back-end)
La siguiente es una prueba para evaluar a los postulantes a programador **Back-end**.

## INTRODUCCIÓN

Este archivo contiene las especificaciones del caso práctico que se desea desarrollar para evaluar las capacidades técnicas del candidato con relación a las funciones necesarias en el área de Desarrollo de Tracker de Colombia

#### ¿Qué se evaluará?
Principalmente los siguientes aspectos:

1.  El uso de  patrones de diseño como Singleton, Builder, Facade, Observer, Interface, Prototype en los dos frentes backend y frontend. 
2. Orden del código (Buenas prácticas)
3. Creatividad
4. Estandarización de base de datos y optimización de almacenamiento
6. Deseable si puede realizar mapeo de entidades de bases de datos por medio de Hibernate. 
7. Diagrama entidad-relacion (Entregar el diagrama en cualquier IDE de diseño)

## NOTA
1. Recomendamos emplear un máximo de **3 (días)** y enviar todo lo que puedas.
2. Existen 2 opciones para entregar su proyecto:
    * 1) Deseable si puede entregar el proyecto realizando un commit en la rama master a este repositorio https://github.com/DetektorGit/PruebaTecnica.git en donde primero tendría que clonarlo con su cuenta de GitHub y notificar a la siguiente dirección de correo electrónico  [juan.velasquez@detektor.com.gt](mailto:juan.velasquez@detektor.com.gt).
    * 2) Crear un archivo comprimido (_.zip_ o _.rar_) de su proyecto y enviar a la siguiente dirección de correo electrónico  [juan.velasquez@detektor.com.gt](mailto:juan.velasquez@detektor.com.gt).

## EJERCICIO

Crear un sistema para Gestión de Contratistas el cuál debe contar con:

1. Módulo de crud de empleados (Creación, edición, consulta y eliminación de empleados) cuyos campos pueden ser Nombre, apellido, identificación, tipo de contrato, fecha de nacimiento, dirección, teléfono, email
2. Módulo de crud de contratistas (Creación, edición, consulta y eliminación de contratistas) cuyos campos pueden ser Nombre, apellido, identificación, fecha de nacimiento, dirección, teléfono, email, empresa. Este módulo debe tener la capacidad de asociar o desasociar por cada contratista n cantidad de empleados definiendo a esta relación el tiempo en horas o en días que el empleado va a trabajar con el contratista (defina usted los campos para este dato) y el nombre de la obra (No es necesario crud de obras).
3. Un informe cuyo contenido sea el detalle de la relación contratista empleado que contenga los siguientes campos: Nombre Contratista, nombre empleado, tiempo trabajados en horas, horas que faltan para terminar el contrato, nombre de la obra.  Este informe contendrá un acceso para descargar un excel del informe.



