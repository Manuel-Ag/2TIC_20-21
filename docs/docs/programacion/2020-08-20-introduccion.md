---
layout: post
title:  "Introducción a la programación"
date:   2020-10-01 14:30:00 +0200
categories: Programacion
order: 1
parent: Bloque 1 Programación
---

# ¿Qué es un programa?

Un programa es una secuencia de instrucciones que especifican cómo ejecutar una computación. La computación puede ser algo matemático, como solucionar un sistema de ecuaciones o determinar las raíces de un polinomio, pero también puede ser una computación simbólica, como buscar y reemplazar el texto de un documento o (aunque parezca raro) compilar un programa.
Las instrucciones (comandos, ordenes) tienen una apariencia diferente en lenguajes de programación diferentes, pero existen algunas funciones básicas que se presentan en casi todo lenguaje:

__entrada:__ Recibir datos del teclado, o un archivo u otro aparato.

__salida:__ Mostrar datos en el monitor o enviar datos a un archivo u otro aparato.

__matemáticas:__ Ejecutar operaciones básicas de matemáticas como la adición y
la multiplicación.

__operación condicional:__ Probar la veracidad de alguna condición y ejecutar una secuencia de instrucciones apropiada.

__repetición:__ Ejecutar alguna acción repetidas veces, normalmente con alguna variación.

Todos los programas que existen, por complicados que sean, están formulados exclusivamente con tales instrucciones. Así, una manera de describir la programación es: El proceso de romper una tarea en tareas cada vez más pequeñas hasta que estas tareas sean suficientemente simples para ser ejecutadas con una de estas instrucciones simples.


# ¿Qué es un lenguaje de programación?

Un lenguaje de programación es un lenguaje artificial que permite escribir una serie de instrucciones para que la máquina realice las tareas definidas. Todas estas instrucciones forman el programa.

## Tipos de lenguajes de Programación

__Bajo nivel:__ Proporciona un control directo del hardware y, dependiendo de dónde se ejecute, variarán las instrucciones que se utilicen. Un ejemplo son el lenguaje máquina y el lenguaje ensamblador.

_Lenguaje máquina_: Las CPUs reciben instrucciones con las que realizan los cálculos. Estas instrucciones son específicas de cada tipo de máquina. Es el lenguaje de programación de nivel más bajo donde las instrucciones se ejecutan directamente por la CPU. Las instrucciones están formadas por 0's y 1's y es difícilmente entendible para un humano.
_Lenguaje ensamblador_: Es un conjunto de mnemónicos que representan las instrucciones del lenguaje máquina. Es único para cada arquitectura de procesador. Por ejemplo, un procesador de arquitectura MIPS:

{:refdef: style="text-align: center;"}
![Imagen]({{ site.baseurl }}/assets/post_introduccion/img1.png)
{:refdef}

Deberíamos de programar el siguiente código:

{:refdef: style="text-align: center;"}
![Imagen]({{ site.baseurl }}/assets/post_introduccion/img2.png)
{:refdef}

Al final, el lenguaje ensamblador se transforma en lenguaje máquina para que ésta pueda ejecutar las instrucciones.

{:refdef: style="text-align: center;"}
![Imagen]({{ site.baseurl }}/assets/post_introduccion/img3.png)
{:refdef}

__Alto nivel:__ Están más próximos al lenguaje humano. Algunos serían Java, Python, Ruby, etc.).


#### Bibliografía

_Downey, A., Elkner, J., & Meyers, C. (2002). Aprenda a Pensar como un Programador con Python. Traducido por Vilella M., A., Arnal, A., Juanes, I., Amurrio, L., Andia, E., y Balladini, C. Recuperado de <https://argentinaenpython.com/quiero-aprender-python/aprenda-a-pensar-como-un-programador-con-python.pdf>_
