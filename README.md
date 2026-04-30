# Laboratorio 2 Arquitectura y Organización de Computadores

## INTEGRANTES
* Emilio Moran Jesus Valdebenito  Rol: 202473575-6  Paralelo: 201
* Adrian Alejandro Rangel Morales  Rol: 202373631-7  Paralelo: 201

## Esecificacion de los algoritmos y Desarrollo 

1. Analisis de Estados: Se construyo la tabla de verdad asociando las 16 combinaciones posibles a sus respectivos simbolos de runa (del 0 al 15).
2. Minimizacion: Se emplearon Mapas de Karnaugh de 4 variables para cada segmento del display, extrayendo las funciones minimizadas.
3. Optimizacion de Arquitectura: Se implementa una arquitectura de "logica compartida" en lugar de procesar cada segmento de forma aislada.

## Supuestos Utilizados
* Se asume que el Display de 7 Segmentos opera con logica positiva (1 = HIGH, 0 = LOW).
* Se asume que las entradas del panel siempre enviarán una señal estable de 0 o 1, descartando valores flotantes.
* El circuito se hizo exclusivamente mediante logica combinacional, asumiendo que no se requiere sincronismo ni almacenamiento de estados.

## Instrucciones de Ejecucion
1. Abrir Logisim Evolution(versión 4.1.0).
2. ir a `File` -> `Open...` y seleccionar el archivo `decodificador.circ`.
3. Hacer clic sobre el circuito principal llamado `main`..
5. Haga clic en los pines de entrada (A3, A2, A1, A0) ubicados en la parte izquierda del circuito para alternar sus valores entre `0` y `1`.
