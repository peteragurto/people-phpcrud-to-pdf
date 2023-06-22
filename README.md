# Introducción
Este pequeño proyecto web construido en MVC permite realizar acciones **CRUD** con registros de ventas, además de poder generar **documentos PDF** para esas tablas de registros. Puedes modificar el código a tu conveniencia ya que el código es bastante sencillo. 

# Creación de BD Default
Primero debes crear una DB llamada `persona_pdf`(**recomiendo MariaDB**) y luego dentro de esta insertar este código para crear la tabla con la que se trabajará(**Si quieres modificar el tipo de registro recuerda que también tienes que cambiar el código PHP**):
```sql
CREATE TABLE `persona_pdf`.`ventas` (`id` INT NOT NULL AUTO_INCREMENT , `nombres` VARCHAR(255) NOT NULL , `dni` VARCHAR(10) NOT NULL , `producto` VARCHAR(255) NOT NULL , `precio_unit` FLOAT NOT NULL , `cantidad` INT(255) NOT NULL , `precio_total` FLOAT NOT NULL , PRIMARY KEY (`id`)) ENGINE = InnoDB;
```
# Tecnologías usadas
- PHP 🐘
- SQL ➡️
- Bootstrap 5 🎨
- Librerías FPDF 🔴

# Recomendaciones
Conocer de tecnologías PHP, SQL y algo de FPDF para que puedas modificar el código a tu gusto.

# Vistas previas del programa

![WhatsApp Image 2023-06-22 at 11 03 00 AM](https://github.com/peteragurto/people-phpcrud-to-pdf/assets/130622718/a6015f1c-7e23-4b8c-b968-94057461c5c2)
***
![WhatsApp Image 2023-06-22 at 11 04 10 AM](https://github.com/peteragurto/people-phpcrud-to-pdf/assets/130622718/f19886cc-60f5-4d70-b5d3-0417153f07ff)
***
![WhatsApp Image 2023-06-22 at 11 07 08 AM](https://github.com/peteragurto/people-phpcrud-to-pdf/assets/130622718/3b293425-4519-42c4-94f8-883c613cdd19)
***
![WhatsApp Image 2023-06-22 at 11 07 34 AM](https://github.com/peteragurto/people-phpcrud-to-pdf/assets/130622718/105a22b7-7dbc-4694-8b23-d280c15f689b)


