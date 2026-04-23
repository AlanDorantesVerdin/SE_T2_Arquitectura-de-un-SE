# Investigación: Arquitectura de un Sistema Experto

Este repositorio contiene una investigación documental sobre la estructura y funcionamiento de los Sistemas Expertos. El objetivo es desglosar los elementos teóricos y funcionales que componen la arquitectura de esta rama de la Inteligencia Artificial, explicando qué son, para qué sirven y cómo operan.

## Contenido de la Investigación

El análisis está estructurado en archivos individuales correspondientes a las cuatro fases principales del ciclo de vida del conocimiento dentro del sistema:

* *[Fase 1: Adquisición del Conocimiento](./01_Adquisicion_del_Conocimiento.md)* Define los roles del Experto humano y el Cognimático (Ingeniero del Conocimiento), así como los sensores y el módulo encargado de recopilar la información.

* *[Fase 2: Representación del Conocimiento](./02_Representacion_del_Conocimiento.md)* Explica cómo se almacena de forma permanente la lógica y las reglas (Base de Conocimiento), y cómo el sistema maneja la memoria temporal durante una consulta (Base de Hechos).

* *[Fase 3: Tratamiento del Conocimiento](./03_Tratamiento_del_Conocimiento.md)* Describe el núcleo de procesamiento del sistema: el Motor de Inferencia que cruza los datos para deducir respuestas, y el Módulo de Explicaciones que justifica las conclusiones.

* *[Fase 4: Utilización del Conocimiento](./04_Utilizacion_del_Conocimiento.md)* Detalla la capa final donde ocurre la interacción humano-máquina, compuesta por la Interfaz y el Usuario que requiere resolver un problema.

## Caso Práctico Integrador

Para ilustrar la teoría, la investigación concluye con un caso de estudio:

* *[Ejemplo Práctico: Sistema Akinator de Super Smash Bros](./05_Ejemplo_Practico.md)* Un desglose de cómo todos los elementos arquitectónicos mencionados interactúan entre sí en un escenario real, diseñado para clasificar y adivinar personajes del juego mediante deducciones lógicas.
