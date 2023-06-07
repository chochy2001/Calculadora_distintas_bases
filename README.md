# Documentación del Programa de Calculadora de Programador en Ensamblador x86

Este documento describe el funcionamiento de un programa de calculadora de programador diseñado para arquitecturas Intel x86. Este programa opera a través de una interfaz gráfica y permite al usuario realizar cálculos en base decimal, hexadecimal y binaria.

## Funcionalidades

El programa presenta una interfaz gráfica con tres conjuntos de botones:

1. **Botones de base numérica (3):** Permiten seleccionar la base numérica con la que el usuario desea trabajar. Los botones son 'Dec' para decimal, 'Hex' para hexadecimal y 'Bin' para binario.

2. **Botones de dígitos (16):** Proporcionan los dígitos que el usuario puede introducir, limitados a las bases numéricas seleccionadas.

3. **Botones de operadores aritméticos (6):** Permiten realizar las operaciones de suma (+), resta (-), multiplicación (*), cociente de la división (/), residuo de la división (%) y obtener el resultado (=).

El programa permite introducir un máximo de 4 dígitos por operador para cualquier base numérica. Tras introducir el primer número, el usuario selecciona un operador, luego introduce el segundo número que se muestra en la siguiente línea de la interfaz. Una vez introducidos ambos números, el usuario puede presionar el botón de igual ('=') para obtener el resultado, que se muestra en la base seleccionada.

## Resultados y Excepciones

Los resultados de las operaciones pueden tener diferentes tamaños de dígitos, dependiendo de la operación:

- La suma puede tener de 1 a 5 dígitos,
- La resta puede tener de 1 a 4 dígitos,
- La multiplicación puede tener de 1 a 8 dígitos,
- El cociente de la división puede tener de 1 a 4 dígitos,
- El residuo de la división puede tener de 1 a 4 dígitos.

En el caso de una resta que resulta en un número negativo, el programa muestra el resultado con un signo negativo.

Para el caso de una división por cero, el programa muestra un mensaje de error o 'NaN' (no es un número), o cualquier otra indicación que el programador considere apropiada.

Cuando se selecciona una base numérica, el programa indica de alguna manera que esa base ha sido seleccionada. Además, el programa limita los dígitos que el usuario puede introducir a aquellos permitidos por la base seleccionada.# Calculadora_distintas_bases
