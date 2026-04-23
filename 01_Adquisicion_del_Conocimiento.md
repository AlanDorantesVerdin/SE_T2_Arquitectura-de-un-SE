# Fase 1: Adquisición de Conocimiento

Esta fase comprende los elementos y procesos mediante los cuales el sistema obtiene la heurística, los datos y las reglas del dominio específico.

## 1. Experto
* *¿Qué es?* Es un individuo que posee pericia, heurísticas especializadas y habilidades avanzadas de resolución de problemas en un dominio de aplicación muy acotado. Este experto domina tanto el conocimiento explícito (teoría, fórmulas, estándares) como el conocimiento tácito (intuición y juicios basados en experiencia empírica).
* *¿Para qué sirve?* Constituye la fuente primaria de la lógica y las reglas de decisión que gobernarán el sistema. Su función es proveer la materia prima cognitiva que el modelo intentará emular.
* *¿Cómo funciona?* Transfiere su base de conocimiento empírico al ingeniero del conocimiento mediante protocolos de educción, entrevistas estructuradas, análisis de casos de estudio y revisión de documentación técnica.

## 2. Cognimático
* *¿Qué es?* Es un especialista en ciencias computacionales e inteligencia artificial responsable del proceso de educción (extracción), estructuración y formalización del conocimiento. Aplica metodologías cognitivas para modelar la forma en que el experto piensa y toma decisiones.
* *¿Para qué sirve?* Actúa como la interfaz de traducción entre el razonamiento humano no estructurado y la lógica computacional rigurosa requerida por el sistema.
* *¿Cómo funciona?* Extrae la heurística del experto, diseña la arquitectura conceptual del problema y codifica esta información en formalismos lógicos (como reglas de producción o redes semánticas) procesables por la máquina.

## 3. Sensores / Bases de Datos
* *¿Qué es?* Son subsistemas de telemetría y repositorios de información estructurada. Los sensores proporcionan variables físicas dinámicas del entorno, mientras que las bases de datos aportan registros históricos y tablas de consulta preexistentes.
* *¿Para qué sirve?* Permiten la ingesta automática de datos del entorno o del contexto histórico, alimentando al sistema con parámetros cuantitativos y cualitativos sin requerir intervención humana directa o entrada manual.
* *¿Cómo funciona?* Los sensores envían señales o métricas en tiempo real, y las bases de datos ejecutan consultas (queries) programadas, enviando esta información directamente al módulo de adquisición para actualizar el estado del problema analizado.

## 4. Módulo de Adquisición de Conocimiento
* *¿Qué es?* Es una herramienta de software (que puede incluir editores de reglas, analizadores sintácticos o algoritmos de aprendizaje) que sirve como entorno de desarrollo e integración.
* *¿Para qué sirve?* Su propósito técnico es validar, compilar y formatear los modelos de conocimiento crudo y los datos externos al lenguaje formal del sistema.
* *¿Cómo funciona?* Recibe la lógica estructurada por el cognimático o los datos emitidos por los sensores/bases de datos, los codifica bajo la sintaxis del sistema y los transfiere a la Base de Conocimiento o a la Base de Hechos según corresponda.