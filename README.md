- [Introducción](#introduccion)
- [Objetivo](#objetivo)
- [Estructura del Curso:](#estrctura-del-curso)
  - [Horas de Clase](#horas-de-clase)
  - [Sitio web de la clase](#sitio-web)
  - [Horas de Oficina](#horas-de-oficina)
- [Evaluación](#evaluacion)
- [Absentismo](#absentismo)
- [Temario](#temario)
- [Slides](#slides)
- [Ejercicios en Python](#ejercicios-en-python)
- [Tareas](#tareas)
- [Libros de Texto](#libros-de-texto)
- [Material Especial requerido para la clase](#material-especial-para-clase)
- [Políticas](#politicas)


# Introduccion

En esta clase estudiaremos la definición de una base de datos. La estructura de una base de datos, así como las operaciones básicas de la misma. Aprenderemos SQL y mySQL.

# Objetivo

Los estudiantes serán capaces de crear y modificar una base de datos, así como de realizar operaciones sencillas sobre las mismas. 

# Estructura del Curso

## Horas de clase

- Martes y Jueves 12:00 - 13:30

## Sitio web

Clases, tareas, temario y políticas de calificaciones se encuentran disponibles en el sitio web: https://leonpalafox.github.io/dbclase_2019/


## Horas de oficina

Estaré disponible antes de la clase en mi oficina (Ingenieria 24), o haciendo una cita al correo electornico lpalafox@up.edu.mx.

# Evaluacion

La evaluación consistirá en:

- El proyecto final será el 40% de la evaluación final.

- El restante 60% será distribuido de la siguiente forma:
  - Dos examenes. 
  - Dos tareas.
  - Participación en clase


# Absentismo
Es obligatorio atender a todas las sesiones.

En caso de alguna situación extraordinaria se deberá platicarlo con la directora de la carrera y el profesor.

# Temario

1. Conceptos Básicos
    1. Estructura de archivos, almacenamiento físico e indexación.
    2. Surgimiento y definición de Bases de Datos.
    3. Clasificación de acuerdo a la consulta, comercialización y localización.
    4. Definición de un Sistema Manejador de Base de Datos  (SMBD).
    5. Estructura y componentes de un SMBD.
    6. Requerimientos operacionales (integridad, independencia, seguridad, concurrencia)
    7. Abstracción de la Información

2. Modelo de Datos y Diseño de una BD
    1. Conceptos generales de un modelo de datos.
    2. Modelo de datos jerárquico y modelo de datos en red
    3. Modelos lógicos basados en objetos 
    4. Modelo de datos relacional
    5. Cardinalidad de Mapeo 
    6. Diagramas Entidad – Relación (E-R)
    7. Entidades, relaciones, atributos y llaves
    8. Consideraciones y pasos en la construcción de diagramas E-R
    9. Matriz de relaciones y solución de la relación muchos a muchos
    10. Relaciones del Modelo Recursivo
    11. Reducción del Modelo E-R a tablas
    12. El Lenguaje de Modelado Unificado UML

3. Consideraciones en el diseño
    1. Operaciones básicas del álgebra relacional 
    2. Concepto de Normalización
    3. Dependencias Funcionales y formas normales
    4. Dependencias Multivalores
    5. Restricciones de dominio e Integridad referencial 

4. Lenguajes comerciales de consulta
    1. Lenguaje SQL, ventajas y desventajas
    2. Estándares de SQL 
    3. Lenguaje de definición de datos y restricciones
    4. Lenguaje de manipulación de datos
    5. Inserción, modificación y borrado de registros
    6. Consultas simples y ordenamiento
    7. Expresiones compuestas y campos calculados
    8. Agrupamientos y funciones de grupo
    9. Consultas avanzadas y subconsultas
    10. Lenguaje de consulta en entorno multiusuario
    11. Optimización de índices y uso de vistas
    12. Disparadores


# Slides

- [Clase 1 - Introducción](https://github.com/leonpalafox/dbclase_2019/blob/master/Slides/Clase_1_2019.pdf)
- [Clase 2 - Modelo Relacional](https://github.com/leonpalafox/dbclase_2019/blob/master/Slides/Clase_2_2019.pdf)
- [Clase 3 - Modelos De Bases de Datos](https://github.com/leonpalafox/dbclase_2019/blob/master/Slides/Clase_3_2019.pdf)
- [Clase 4 - Normalización](https://github.com/leonpalafox/dbclase_2019/blob/master/Slides/Clase_4_2019.pdf)
- [Clase 5 - Ejemplos](https://github.com/leonpalafox/dbclase_2019/blob/master/Slides/Clase_5_2019.pdf)
- [Clase 6 - Ejemplos](https://github.com/leonpalafox/dbclase_2019/blob/master/Slides/Clase_6_2019.pdf)
- [Clase 7 - Entidad Relación](https://github.com/leonpalafox/dbclase_2019/blob/master/Slides/Clase_7_2019.pdf)
- [Clase 8 - Algebra Relacional](https://github.com/leonpalafox/dbclase_2019/blob/master/Slides/Clase_8_2019.pdf)
- [Clase 9 - Algebra Relacional](https://github.com/leonpalafox/dbclase_2019/blob/master/Slides/Clase_8_2019.pdf)
- [Clase 10 - Algebra Relacional](https://github.com/leonpalafox/dbclase_2019/blob/master/Slides/Clase_8_2019.pdf)
- [Clase 11 - Algebra Relacional/SQL](https://github.com/leonpalafox/dbclase_2019/blob/master/Slides/Clase_8_2019.pdf)
- [Clase 12 - SQL](https://github.com/leonpalafox/dbclase_2019/blob/master/Slides/Clase_8_2019.pdf)

# Sets de Datos

- [Estados](https://raw.githubusercontent.com/leonpalafox/dbclase_2019/master/datasets/estados.csv)
- [Indicadores (Recortado)](https://raw.githubusercontent.com/leonpalafox/dbclase_2019/master/datasets/indicadores_short.csv)
- [Equipos](https://raw.githubusercontent.com/leonpalafox/dbclase_2019/master/datasets/euro.sql)

# Ejercicios en Python

- [Cuaderno de Colab para conectar una base de datos SQL](https://colab.research.google.com/drive/1YAutFlSlVB1SSjSHua4WPaM4wQQ_tWOs)


# Tareas


# Forma de Evaluación

- [Forma](https://docs.google.com/forms/d/e/1FAIpQLSchyplaxVM8APNVa9uXnj9Q398i3e9E0sXyAxS0402hMGOGZw/viewform?usp=sf_link)



# Libros de texto

El curso no requiere de libros de texto adjuntos, sin embargo, los siguientes libros son útiles para dar seguimiento al curso:

- Garcia-Molina, Hector. Database systems: the complete book. Pearson Education India, 2008.

# Material especial para la clase


# Politicas

Se pueden utilizar teléfonos y bipers, siempre y cuando no molestén al resto del salón.




