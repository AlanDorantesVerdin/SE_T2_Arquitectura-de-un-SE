# Fase 3: Tratamiento del Conocimiento

Esta fase engloba los mecanismos algorítmicos que procesan la información almacenada para generar deducciones, tomar decisiones y justificar los resultados.

## 1. Motor de Inferencia
* *¿Qué es?* Es el algoritmo central de procesamiento simbólico y control lógico del sistema experto.
* *¿Para qué sirve?* Es el encargado de generar nuevas afirmaciones, diagnosticar fallos o emitir decisiones cruzando las variables de la Base de Hechos con las reglas de la Base de Conocimiento.
* *¿Cómo funciona?* Ejecuta estrategias de búsqueda algorítmica estructurada, evaluando iterativamente patrones coincidentes. Aplica principalmente métodos de encadenamiento hacia adelante (forward chaining, guiado por datos) o encadenamiento hacia atrás (backward chaining, guiado por objetivos), aplicando protocolos de resolución de conflictos cuando múltiples reglas son válidas simultáneamente.

## 2. Módulo de Explicaciones
* *¿Qué es?* Es un subsistema de trazabilidad y auditoría algorítmica (Explainable AI).
* *¿Para qué sirve?* Proporciona transparencia a los procesos lógicos del sistema, justificando ante el usuario por qué se ha llegado a un dictamen específico o por qué se solicita un dato particular durante la consulta.
* *¿Cómo funciona?* Rastrea, registra y reconstruye el "árbol de inferencia" (la ruta exacta de nodos y reglas que se activaron durante el procesamiento lógico) y traduce esta traza a un lenguaje comprensible para respaldar sus conclusiones.