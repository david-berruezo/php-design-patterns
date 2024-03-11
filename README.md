# Collection of php design_patterns

## 01.- Abstract Factory 
## 02.- Adapter
## 03.- Bridge
## 04.- Builder
## 05.- Chain of responsibility
![Screenshot](/ChainOfResponsibility/uml/uml.png)<br>
## 06.- Command
## 07.- Composite
## 08.- Composition
## 09.- Decorator
## 10.- Facade
## 11.- Factory Method
## 12.- Flyweight
## 13.- Interpreter
## 14.- Iterator
## 15.- Mediator
## 16.- Memento
## 17.- Ejemplos de Objetos
## 18.- Observer
## 19.- Prototype
## 20.- Proxy
## 21.- Singleton
## 22.- State
## 23.- Strategy
## 24.- Template method
## 25.- Visitor


# Introducción a PHP

Esta guía está diseñada para poder obtener el código del curso de **PHP 7** de una forma amigable y en español.

::: warning Aviso
Esta guía está en constante actualización, podría no estar completa.
:::

## ¿Qué es PHP?
PHP (acrónimo recursivo de PHP: Hypertext Preprocessor) es un lenguaje de programación de código abierto muy popular especialmente adecuado para el desarrollo web y una de sus gracias es que puede ser incrustado en HTML. Actualmente puedes probar la versión 7.

## PHP y HTML
Una de las ventajas de PHP es que puedes mezclar tus códigos HTML y PHP sin ningún problema, solo tienes que utilizar las etiquetas de apertura `<?php` y cierre `?>` correctamente.

``` php
<!DOCTYPE HTML>
<html>
    <head>
        <title>Ejemplo</title>
    </head>
    <body>

        <?php
            echo "¡Hola, soy un script de PHP!";
        ?>

    </body>
</html>
```

## PHP en el servidor
PHP es ejecutado en el servidor, generando HTML y enviándolo al cliente. El cliente recibirá el resultado de ejecutar el script, aunque no se sabrá el código subyacente que era. Por lo tanto el cliente no tendrá acceso al código PHP.

## Instalación
Para realizar proyectos de forma local (sin necesidad de un hosting), podemos instalar un servidor que ejecutará todas las configuraciones por nosotros (Apache + MariaDB + PHP). Uno de los mejores programas y el que yo recomiendo es **XAMPP**, puedes descargarlo [aquí](https://www.apachefriends.org/es/index.html).

## htdocs
Una vez instalado **XAMPP** tienes que viajar al directorio donde alojaste el programa, adentro encontrarás la carpeta `htdocs`. Esta carpeta es muy importante porque es aquí donde nosotros guardaremos cada uno de nuestros proyectos.

## Hola mundo!
Cómo es un clásico, realizaremos nuestro primer hola mundo con PHP. Para esto crearemos dentro del directorio htdocs una carpeta llamada fundamentos y dentro crea un archivo con el siguiente código, la extensión de este archivo tiene que ser `nombreArchivo.php`

``` php
<?php
  echo 'Hola mundo con php';
?>
```

::: tip Nombre de archivos
Los nombres de los archivos limítalos a la lengua inglesa, no coloques carácteres como `ñ`, `tildes`, `espacios`, u otros raros.
:::

Para ejecutar tu script de php tienes que ir a `http://localhost/fundamentos/nombreArchivo.php`, en este momento deberías estar viendo tu `Hola mundo con php`, Felicitaciones! :clap:

::: tip Cierre PHP
Cuando creamos archivos explicitamente con PHP, puedes omitir la etiqueta de cierre `?>`, más adelante veremos algunos ejemplos con HTML donde explícitamente tenemos que cerrar con esta etiqueta.
:::

## 01 Tarea HMTL y PHP
Te reto a crear un archivo que mezcles HTML y PHP.

***Pista**: tienes que seguir utilizando la extesión `.php` en tu archivo.*

[Ver respuesta aquí](/tareas/#_01-tarea-hmtl-y-php)

