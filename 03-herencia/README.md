# Herencia

## Definición
La herencia permite que una clase hija reutilice atributos y métodos de una
clase padre, pudiendo agregar o especializar su comportamiento.

## Idea clave
Reutilizar código y establecer jerarquías entre tipos relacionados para evitar repetición.

## Clases del ejemplo
- `Empleado`: clase padre con nombre, salario y método `mostrarInformacion()`
- `Gerente`: hereda de Empleado, agrega el atributo `area`
- `Desarrollador`: hereda de Empleado, agrega el atributo `lenguaje`
- `Main`: crea instancias de ambas clases hijas

## Cómo ejecutar
1. Abrir terminal en la carpeta `src`
2. Compilar con: `javac *.java`
3. Ejecutar con: `java Main`

## Salida esperada
```
Nombre: María
Salario: 4500000.0
Área: Tecnología
-----
Nombre: Carlos
Salario: 3800000.0
Lenguaje principal: Java
```

## Aprendizaje logrado
Las clases hijas no repiten nombre ni salario. La jerarquía reduce la
repetición y organiza mejor el código.