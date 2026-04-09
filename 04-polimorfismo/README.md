# Polimorfismo

## Definición
El polimorfismo permite usar una misma referencia común para trabajar con objetos
de distintas clases que responden de manera diferente al mismo mensaje.

## Idea clave
Un mismo método produce comportamientos distintos dependiendo del tipo real del objeto.

## Clases del ejemplo
- `Animal`: clase base con el método `hacerSonido()`
- `Perro`: sobrescribe `hacerSonido()` para ladrar
- `Gato`: sobrescribe `hacerSonido()` para maullar
- `Main`: declara variables de tipo Animal y asigna Perro y Gato

## Cómo ejecutar
1. Abrir terminal en la carpeta `src`
2. Compilar con: `javac *.java`
3. Ejecutar con: `java Main`

## Salida esperada
El perro ladra.
El gato maúlla.

## Aprendizaje logrado
Las dos variables son de tipo Animal, pero cada objeto responde según su
clase real. Eso es polimorfismo.