#Simulaciones con Java
Proyecto realizado para la asignatura 'Modelos de Computación'. Universidad de Cádiz.

Se adjunta un .jar para probar la aplicación sin necesidad de compilar.

**Dependencias:**
El software utiliza una biblioteca llamada JFreeChart que puedes encontrar [aquí](https://github.com/jfree/jfreechart).
Las que he utilizado se encuentrar en el directorio 'Jfreechart' de este mismo proyecto.

**Compilación:**
Se recomienda que se compile bajo Eclipse, importando las bibliotecas externas ya mencionadas (jfreechart). En Esqueleto.java se encuentra 
el main.

Para compilar manualmente se deberá incluir las bibliotecas externas en el path del sistema y compilar en el orden que se establece en
el archivo 'Orden_compilacion'.

**Características:**
El software se compone de:
-Generador de números aleatorios.
-Simulación de autómatas.
-Cifrado de texto mediante autómatas.
-Conway's Game of Life.
-Simulador de reacción química de Belousov-Zhabotinsky.
-Simulador de tumor cerebral.
-Simulación de Mandelbrot.
-Intérprete de URM. (se adjuntan programas de ejemplo en 'Programas URM')

Las simulaciones se ejecutan bajo paralelismo en cpu para mas eficiencia.

**Capturas de ejemplo:**

Autómata.
<p align="center">
	<img width="560" height="400" src="/images/automata.png"
</p>