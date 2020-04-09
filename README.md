# sakila-maria                                                                         

![MariaBB](https://www.alvarodeleon.net/wp-content/uploads/2019/05/1557823541-a1ef193e6312c17a18bb1fa5d4f9756d.png)

### Introducción

La base de datos sakila es una base de datos utilizada por __Mysql__ para el aprendizaje de conceptos en base de datos relacionales. Específicamente creada para aquel motor, si se trata de ejecutar en un motor basado en __Mariadb__ , se producirán errores de ejecución de script, ya que MariaDB es más estrictamente sensible a la integridad referencial que Mysql. Esta versión, específica para MariaDB, produce una instalación limpia, y permite disfrutar de todas las características de Sakila en el motor MariaDB.    

***

# Instalación

En cualquier tipo de cliente de base de datos para MariaDB(Gráfico o no):

1. Ejecutar el archivo sakila_schema.sql(Te crea la base de datos).
2. Ejecutar el archivo sakila_data.sql(Te inserta los datos de ejemplo de la base de datos).

Algunos clientes recomendados para MariaDB:
- Windows:
    - HeidiSQL
    - SQLYog
- Linux/mac:   
    - DataGrip
    - MysqlWorkbench(Puede generar algunos errores)    
  
***

### Características y Dominio de Problema

>La base de datos de muestra de Sakila fue desarrollada inicialmente por Mike Hillyer, un ex miembro del equipo de documentación de MySQL AB, y está destinada a proporcionar un esquema estándar que puede usarse para ejemplos en libros, tutoriales, artículos, muestras, etc. La base de datos de muestra de Sakila también sirve para resaltar características de MySQL como __Vistas, Procedimientos almacenados y Triggers__.



### Agradecimientos

A Federico Razzoli, de quién hice fork a su proyecto en GitHub. ¡Genial idea!. https://federico-razzoli.com
