Informe de Práctica: Operaciones Básicas en PHP
1. Objetivo
El propósito de la práctica fue aplicar conceptos básicos de programación en PHP para realizar operaciones aritméticas simples (suma, resta y multiplicación) y mostrar los resultados en una página web.

2. Entorno de Desarrollo
Editor de código: Visual Studio Code

Lenguaje utilizado: PHP

Archivos creados:

Suma.php

Resta.php

Multiplicacion.php

Cada archivo corresponde a una operación matemática específica.

3. Procedimiento
Creación de archivos PHP:  
Se generaron tres scripts independientes, cada uno con la estructura básica de PHP (<?php ... ?>).

Definición de variables:

Se declararon dos variables ($numero1 y $numero2) con valores numéricos fijos.

Ejemplo en Resta.php:

php
$numero1 = 10;
$numero2 = 4;
Operación aritmética:

Se aplicó el operador correspondiente a cada archivo (+, -, *).

En el caso de la resta:

php
$resultado = $numero1 - $numero2;
Impresión del resultado:

Se utilizó la función echo para mostrar el resultado en el navegador con un mensaje descriptivo:

php
echo "La resta de $numero1 - $numero2 es: $resultado";
4. Ejecución en la Web
Los archivos fueron preparados para ejecutarse en un servidor local (ej. XAMPP/WampServer).

Al acceder mediante la URL http://localhost/PRACTICA SUMATIVA/Resta.php, el navegador muestra:

Código
La resta de 10 - 4 es: 6
5. Resultados
Se logró implementar correctamente las tres operaciones básicas en PHP.

Los scripts muestran mensajes claros y permiten verificar la lógica de cada cálculo.

La práctica refuerza el uso de variables, operadores y salida de datos en PHP.

6. Conclusiones
PHP es un lenguaje sencillo para comenzar a trabajar con lógica de programación en entornos web.

La práctica permitió comprender cómo estructurar scripts básicos y cómo integrarlos en un servidor local.

Este ejercicio constituye la base para proyectos más complejos, como el uso de formularios HTML para recibir datos dinámicos del usuario.
