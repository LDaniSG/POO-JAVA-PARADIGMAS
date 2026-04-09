# Composición

## Definición
La composición es una relación todo-parte fuerte. Las partes se crean y gestionan
dentro del objeto principal y su ciclo de vida depende completamente de él.

## Idea clave
Los componentes no tienen sentido aislados del objeto contenedor. Si el todo
desaparece, las partes también.

## Clases del ejemplo
- `Habitacion`: clase que representa una parte de la casa
- `Casa`: clase principal que crea y administra sus habitaciones internamente
- `Main`: crea una casa y le agrega habitaciones desde adentro

## Cómo ejecutar
1. Abrir terminal en la carpeta `src`
2. Compilar con: `javac *.java`
3. Ejecutar con: `java Main`

## Salida esperada
```
Casa ubicada en: Calle 10 # 15-20
- Sala
- Cocina
- Habitación principal
```

## Aprendizaje logrado
Las habitaciones nacen dentro de la clase Casa y no existen por fuera de ella.
Esa dependencia fuerte es la composición.