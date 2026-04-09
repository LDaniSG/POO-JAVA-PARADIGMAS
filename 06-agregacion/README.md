# Agregación

## Definición
La agregación es una relación todo-parte débil. Un objeto contenedor agrupa a
otros objetos, pero esos objetos pueden existir aunque el contenedor desaparezca.

## Idea clave
Diferencia entre una pertenencia flexible (agregación) y una fuerte (composición).

## Clases del ejemplo
- `Jugador`: clase con atributo nombre, existe independientemente
- `Equipo`: clase que agrupa una lista de jugadores
- `Main`: crea jugadores por separado y los agrega al equipo

## Cómo ejecutar
1. Abrir terminal en la carpeta `src`
2. Compilar con: `javac *.java`
3. Ejecutar con: `java Main`

## Salida esperada
Equipo: Tigres
- Luis
- Pedro

## Aprendizaje logrado
Los jugadores se crean antes del equipo. Pertenecen al equipo pero no
dependen de él para existir. Eso es agregación.