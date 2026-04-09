# Abstracción

## Definición
La abstracción representa solo las características esenciales de un objeto,
ocultando los detalles irrelevantes. En Java se logra con clases abstractas o interfaces.

## Idea clave
Modelar ideas generales primero y dejar los detalles concretos para las subclases.

## Clases del ejemplo
- `Figura`: clase abstracta con el método abstracto `calcularArea()`
- `Circulo`: implementa el área con la fórmula π * r²
- `Rectangulo`: implementa el área con base * altura
- `Main`: instancia ambas figuras y muestra sus áreas

## Cómo ejecutar
1. Abrir terminal en la carpeta `src`
2. Compilar con: `javac *.java`
3. Ejecutar con: `java Main`

## Salida esperada
Soy una figura geométrica.
Área del círculo: 78.53981633974483
Soy una figura geométrica.
Área del rectángulo: 24.0

## Aprendizaje logrado
Figura define el concepto general sin imponer una fórmula. Cada subclase
resuelve el detalle. Eso es abstracción.