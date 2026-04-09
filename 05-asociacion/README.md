# Asociación

## Definición
La asociación es una relación general entre dos clases que colaboran entre sí,
pero pueden existir de manera independiente. No hay control del ciclo de vida.

## Idea clave
Dos objetos se conectan para interactuar sin depender totalmente uno del otro.

## Clases del ejemplo
- `Profesor`: clase con atributo nombre
- `Curso`: clase que contiene una referencia a un Profesor
- `Main`: crea un profesor y lo asigna a un curso

## Cómo ejecutar
1. Abrir terminal en la carpeta `src`
2. Compilar con: `javac *.java`
3. Ejecutar con: `java Main`

## Salida esperada
Curso: POO en Java
Profesor: Andrés Gómez

## Aprendizaje logrado
El profesor puede existir sin ese curso y el curso podría cambiar de profesor.
Esa independencia caracteriza la asociación.