# Arquitectura Integrada: Sistema Experto de Clasificación

A continuación, se detalla la integración de los componentes de la arquitectura del sistema experto aplicado a un motor de inferencia y clasificación de personajes del videojuego *Super Smash Bros*.

## Flujo de los Elementos en el Sistema:

1. *Experto:* Un individuo con profundo conocimiento competitivo y estadístico del juego, capaz de categorizar detalladamente a los personajes por atributos (peso, velocidad, uso de proyectiles, franquicia de origen).
2. *Cognimático:* El ingeniero encargado de abstraer la matriz de atributos proporcionada por el experto y estructurarla en un árbol de decisión lógico.
3. *Módulo de Adquisición:* La herramienta que traduce y compila estos atributos en el código de la aplicación.
4. *Base de Conocimiento:* Repositorio estático de reglas booleanas y condicionales. 
   * Ejemplo de regla algorítmica: IF (Usa_Espada == True) AND (Franquicia == "Fire Emblem") AND (Tiene_Counter == True) THEN (Personaje = [Marth, Roy, Ike, Lucina, Chrom, Byleth, Corrin]).
5. *Usuario e Interfaz:* El operador inicia el sistema en su terminal o entorno gráfico. El sistema despliega la primera variable de consulta: ¿Tu personaje utiliza ataques a distancia (proyectiles)?
6. *Base de Hechos:* Memoria en tiempo de ejecución. Si el usuario ingresa una afirmación, la variable temporal se actualiza: Atributo_Proyectil = True.
7. *Motor de Inferencia:* El procesador lee la Base de Hechos y realiza una intersección con la Base de Conocimiento. Ejecuta un descarte lógico, eliminando inmediatamente del arreglo a personajes de ataques cuerpo a cuerpo (ej. Little Mac). Posteriormente, calcula el nodo de entropía más alto para realizar la siguiente pregunta más eficiente (ej. consultar el peso o la velocidad).
8. *Módulo de Explicaciones:* El sistema incluye una función de trazabilidad (log). Si el usuario consulta el estado lógico de la deducción, el sistema imprime la ruta de inferencia: "Se filtraron personajes de cuerpo a cuerpo debido a la afirmación en la variable 'Proyectil', y se descartó a la franquicia de Mario por el atributo ingresado previamente".

---