# Proyecto de Fundamentos de Programación en Python

Este repositorio contiene las prácticas de lógica algorítmica y programación desarrolladas durante el curso. El trabajo abarca desde la estructuración del pseudocódigo mediante diagramas de flujo hasta su implementación directa utilizando el lenguaje de programación Python.

## Herramientas Utilizadas

* Microsoft Visio: Diseño de diagramas de flujo (ordinogramas) para estructurar la lógica de los algoritmos antes de su codificación.
* Python 3: Lenguaje de programación interpretado para el desarrollo de los scripts.
* Entorno de Desarrollo (IDE) / Editor de texto: Para la escritura, prueba y depuración del código fuente.

---

## Bloques Temáticos y Prácticas

### 1. Lógica de Programación y Diagramas de Flujo
Fase de diseño y planificación de la estructura de los programas:
* Diseño de Ordinogramas: Creación de diagramas de flujo en Microsoft Visio (Prácticas 13, 15, 17 y 19) que representan gráficamente el comportamiento de los algoritmos.
* Pseudocódigo: Planteamiento teórico de las secuencias de instrucciones, condiciones y bucles para establecer una base lógica sólida antes de pasar al código real.

### 2. Estructuras de Control Condicionales
Implementación de la toma de decisiones y bifurcaciones en el flujo del programa:
* Condicionales Clásicos: Uso de las sentencias if, elif y else para evaluar rangos numéricos y condiciones lógicas (ejemplo: sistema de evaluación y clasificación de notas).
* Selección Múltiple: Implementación de la estructura match-case para evaluar variables contra múltiples valores posibles, optimizando el código frente a largas cadenas de if-elif.
* Manejo de Excepciones: Integración de bloques try-except (ej. ValueError) para validar las entradas del usuario y evitar interrupciones por errores de formato.

### 3. Estructuras Iterativas y Bucles
Control de flujos repetitivos y recorrido de elementos:
* Bucles For y For-Else: Construcción de iteraciones finitas utilizando range(). Implementación de la cláusula else en bucles for para ejecutar acciones específicas si el bucle termina de forma natural sin ser interrumpido por un break (útil en sistemas de intentos de contraseña).
* Iterables y Ficheros: Uso de bucles para recorrer cadenas de texto carácter por carácter y para la escritura secuencial de datos en archivos externos de texto (.txt).
* Bucles While y Control Infinito: Creación de bucles while True controlados internamente mediante evaluación de condiciones del usuario y sentencias break para salir del ciclo de manera segura.

### 4. Módulos Nativos y Operaciones Matemáticas
Uso de librerías estándar de Python para extender la funcionalidad básica:
* Módulo Math: Importación y aplicación de funciones matemáticas avanzadas como math.ceil (redondeo al alza), math.floor (redondeo a la baja), math.pow (potencias) y math.sqrt (raíces cuadradas).
* Tipos de Redondeo: Análisis y aplicación de la función nativa round(), estudiando su comportamiento de "redondeo bancario" (redondeo al número par más próximo cuando el decimal es exacto a la mitad).
