---
layout: post
title: El sistema numérico binario explicado de manera sencilla
subtitle: Un viaje al mundo de los ceros y unos
categories: [Informatik, Zahlensystem]
tags: [binär, dezimal, zahlensystem, umrechnung, bits, bytes, ascii, unicode]
---

# El sistema numérico binario explicado de manera sencilla
En el fascinante mundo de las computadoras, utilizamos el sistema numérico binario. Puede sonar complicado, ¡pero no te preocupes, lo explicaremos de forma muy sencilla!

## El sistema decimal: números que conocemos
Primero, veamos el sistema decimal que utilizamos en nuestra vida cotidiana. Consiste en los números del 0 al 9. Cuando escribimos un número, como por ejemplo 123, cada dígito tiene un valor específico según su posición. El primer dígito de la derecha es el lugar de las unidades, el segundo es el lugar de las decenas, el tercero es el lugar de las centenas y así sucesivamente.

## El sistema numérico binario: un mundo de ceros y unos
En el sistema numérico binario, solo tenemos dos números: el 0 y el 1. Puede parecer poco, ¡pero es increíblemente poderoso! En el mundo binario, no tenemos lugar de las decenas o lugar de las centenas, solo tenemos lugar de las unidades y lugar de los dobles.

## Bits y bytes: los componentes de los datos
En el mundo de las computadoras, las unidades más pequeñas para los datos son los llamados "bits". Un bit puede ser 0 o 1. Varios bits se agrupan para formar "bytes". Un byte está compuesto por 8 bits. Con los bytes podemos almacenar y procesar letras, números y otra información.

## ASCII y Unicode: la codificación de caracteres
Las computadoras almacenan texto y caracteres en forma de números. Anteriormente se utilizaba ASCII (Código Estándar Estadounidense para el Intercambio de Información). Era una codificación de caracteres que asignaba un número único a cada carácter (letras, números, caracteres especiales). De esta manera, una computadora podía convertir y almacenar los caracteres en números binarios. Pero ASCII tenía un problema: solo podía representar un número limitado de caracteres, por ejemplo, solo las letras del alfabeto inglés y algunos caracteres especiales.

Para resolver este problema, ¡se desarrolló Unicode! Unicode es como un gran diccionario de caracteres de muchos idiomas y escrituras diferentes. Puede representar miles de caracteres, incluyendo letras de casi todos los idiomas del mundo, símbolos matemáticos, emojis y mucho más.

### ASCII: Código Estándar Estadounidense para el Intercambio de Información
Hablemos sobre la codificación de caracteres, cómo almacenamos letras y caracteres en las computadoras. En el pasado, cuando las computadoras eran bastante jóvenes, existía ASCII, que significaba 'Código Estándar Estadounidense para el Intercambio de Información'. Era como un libro de magia para las computadoras, asignando un número específico a cada carácter.

ASCII usaba 7 bits para representar 128 caracteres. Y estos caracteres incluían letras (mayúsculas y minúsculas), números, signos de puntuación y algunos caracteres especiales. Así que, por ejemplo, si teníamos la letra 'A', se representaba como 01000001. La 'a' era 01100001, y el número '5' era 00110101. Era bastante sencillo.

Pero aquí está el problema: ASCII solo podía representar un número limitado de caracteres y estaba limitado al inglés y algunos caracteres especiales. Esto significaba que no era tan bueno para escribir textos en otros idiomas o con caracteres especiales.

### Unicode: la codificación global de caracteres
¡Pero luego llegó Unicode! Unicode es como un gran libro mágico que contiene muchos, muchos caracteres diferentes de muchos idiomas y escrituras diferentes. ¿Y sabes cuántos caracteres puede representar Unicode? ¡Más de un millón! Es realmente como un truco de magia que permite representar letras, números, símbolos, emojis y casi cualquier otra cosa que puedas imaginar.

Con Unicode, ahora podemos escribir textos en casi cualquier idioma y usar muchos otros símbolos geniales. Hay caracteres especiales para matemáticas, monedas, flechas y mucho más. ¡Es realmente fantástico!

## Conversión de decimal a binario
Ahora queremos saber cómo convertir un número decimal a un número binario. ¡No es tan difícil! Tomamos el número decimal y lo dividimos repetidamente entre 2. Mientras tanto, recordamos el residuo. Luego, escribimos los residuos de abajo hacia arriba.

Conviertamos el número 13 a binario.

1. 13 ÷ 2 = 6. Residuo = 1
2. 6 ÷ 2 = 3. Residuo = 0
3. 3 ÷ 2 = 1. Residuo = 1
4. 1 ÷ 2 = 0. Residuo = 1

Ahora escribimos los residuos de abajo hacia arriba: 1101.

¡Eso es todo! El número binario para 13 es 1101.

## Conversión de binario a decimal
Ahora queremos saber cómo convertir un número binario a un número decimal. ¡Tampoco es difícil! Tomamos cada lugar binario, de derecha a izquierda, y lo multiplicamos por la potencia correspondiente de 2.

Conviertamos el número binario 1101 a decimal.

1. 1 * 2⁰ = 1
2. 0 * 2¹ = 0
3. 1 * 2² = 4
4. 1 * 2³ = 8

Ahora sumamos estos resultados: 1 + 0 + 4 + 8 = 13.

¡Eso es todo! El número decimal para el número binario 1101 es 13.

El sistema numérico binario nos permite almacenar y procesar datos de manera sencilla en una computadora. ¡Con el conocimiento de cómo convertir de binario a decimal, podemos entender mejor el fascinante mundo de los ceros y unos!