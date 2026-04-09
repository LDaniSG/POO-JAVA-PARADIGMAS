# Encapsulación

## Definición
La encapsulación protege los datos internos de un objeto y obliga a modificar
su estado únicamente a través de métodos controlados, evitando cambios incorrectos.

## Idea clave
Evitar que otros objetos modifiquen directamente los atributos. Toda la lógica
de validación queda centralizada dentro de la misma clase.

## Clases del ejemplo
- `CuentaBancaria`: contiene los atributos privados y los métodos de validación
- `Main`: instancia la cuenta y prueba las operaciones

## Cómo ejecutar
1. Abrir terminal en la carpeta `src`
2. Compilar con: `javac *.java`
3. Ejecutar con: `java Main`

## Salida esperada
```
Titular: Laura
Saldo inicial: 500000.0
Depósito realizado correctamente.
Retiro realizado correctamente.
Saldo final: 540000.0
```

## Aprendizaje logrado
El saldo nunca se modifica directamente desde Main. Todo pasa por métodos
que validan la operación, eso es encapsulación.