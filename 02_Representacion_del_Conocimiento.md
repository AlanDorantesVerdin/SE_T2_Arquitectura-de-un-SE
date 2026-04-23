# Fase 2: Representación del Conocimiento

En esta etapa, el conocimiento adquirido se estructura lógicamente y se almacena en las estructuras de memoria del sistema para su posterior consulta.

## 1. Base de Conocimiento
* *¿Qué es?* Es el núcleo estructural no volátil del sistema experto. Consiste en un corpus rigurosamente organizado que contiene la ontología del dominio, construido utilizando formalismos lógicos como reglas de producción (SI-ENTONCES), marcos (frames) o lógica difusa.
* *¿Para qué sirve?* Almacena de manera permanente las "leyes", heurísticas y todas las posibles rutas de decisión y resolución de problemas validadas por el experto. 
* *¿Cómo funciona?* Opera como una biblioteca estática de axiomas y reglas lógicas. No sufre modificaciones durante la ejecución de una consulta o resolución de un problema particular; únicamente es leída e iterada por el motor de inferencia.

## 2. Base de Hechos
* *¿Qué es?* Es una estructura de memoria volátil y dinámica asignada durante el tiempo de ejecución (runtime).
* *¿Para qué sirve?* Su función es retener los datos específicos y temporales del problema actual que se está evaluando, incluyendo las premisas iniciales, lecturas de sensores y conclusiones parciales.
* *¿Cómo funciona?* Se actualiza de forma constante durante la sesión. Conforme el sistema recaba nueva información del usuario, del entorno, o deduce nuevos postulados a través de sus reglas, estos estados temporales se escriben en esta memoria para contextualizar el análisis en curso.