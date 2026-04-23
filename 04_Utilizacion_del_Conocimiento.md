# Fase 4: Utilización del Conocimiento

La última fase detalla la capa de interacción entre el sistema experto computacional y el agente humano que requiere asistencia.

## 1. Interfaz de Usuario
* *¿Qué es?* Es la capa de presentación y comunicación del software. Implementa mecanismos de entrada/salida para la interacción humano-máquina.
* *¿Para qué sirve?* Abstrae la complejidad lógica y algorítmica subyacente, facilitando un entorno ergonómico e intuitivo para el intercambio de información bidireccional.
* *¿Cómo funciona?* Despliega cuestionamientos, requerimientos de datos y conclusiones emitidas por el sistema, a la vez que captura las respuestas, parámetros de entrada o comandos ingresados por el operador, traduciéndolos al subsistema de adquisición o base de hechos.

## 2. Usuario
* *¿Qué es?* Es el operador del sistema o la persona que se enfrenta a un problema o escenario complejo dentro del dominio, pero que carece del grado de especialización del "Experto".
* *¿Para qué sirve?* Desempeña el rol de inicializador del sistema, proveyendo los axiomas de partida, síntomas o condiciones iniciales del problema que no pueden ser automatizados mediante sensores.
* *¿Cómo funciona?* Interactúa de manera guiada con la interfaz, suministrando datos de entrada estructurados en respuesta a las iteraciones del motor de inferencia, hasta que el sistema emite un diagnóstico, sugerencia o dictamen final.