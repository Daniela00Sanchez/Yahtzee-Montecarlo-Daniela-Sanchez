# Simulación del juego Yahtzee utilizando Montecarlo

**Estudiante:** Daniela Sánchez 
**Grupo**: 02
**Materia:** Simulación  
**Lenguaje de programación:** Python  
**Herramienta:** Google Colab

## Introducción

En esta actividad se desarrolla una simulación del juego Yahtzee para dos jugadores, utilizando Python y el método de Montecarlo.

El objetivo es comprender cómo funcionan los números aleatorios, calcular probabilidades y observar el comportamiento de los resultados cuando aumentamos la cantidad de simulaciones.

## Metodología USA, MODIFICA y CREA

**USA:** Tomé como referencia el código trabajado por el profesor, que utiliza Montecarlo para aproximar el valor de π mediante números aleatorios.

**MODIFICA:** Adapté la lógica de la simulación para generar lanzamientos de cinco dados, contar las veces que aparecen cinco valores iguales y calcular su probabilidad.

**CREA:** Se incorporó un juego interactivo de Yahtzee para dos jugadores, con hasta tres lanzamientos por turno, selección de dados y registro de puntuaciones.

## Resultados

Se realizaron simulaciones con diferentes cantidades de experimentos.

Con 100.000 pruebas se obtuvieron 74 Yahtzees en la primera tirada, equivalentes al 0,074 %.

La probabilidad teórica es aproximadamente 0,07716 %.

El promedio observado de los dados fue 3,49882, cercano al promedio teórico de 3,5.

## Conclusiones

Con esta actividad pude observar que el método de Montecarlo permite estudiar situaciones aleatorias mediante muchas repeticiones.

También comprendí que, al aumentar la cantidad de experimentos, los resultados tienden a acercarse a los valores teóricos, de acuerdo con la Ley de los Grandes Números.

## Ejecución

El programa está desarrollado en Python y puede ejecutarse desde Google Colab abriendo el archivo `Sanchez_Daniela_Yahtzee_Montecarlo.ipynb` y ejecutando sus celdas.

Para iniciar el juego interactivo se utiliza la función `jugar_yahtzee()`.
