# Prueba Test java actions con IA

Demo de Java, tests unitarios y GitHub Actions.

## Requisitos

- Java 21
- Maven 3.9 o posterior

## Ejecutar los tests

Desde la raíz del proyecto, ejecuta:

```shell
mvn test
```

## Flujo de la demo

La clase `Calculator` implementa operaciones aritméticas y sus tests unitarios verifican los resultados con JUnit 5. GitHub Actions ejecuta `mvn test` al subir cambios a `main` y en cada pull request dirigido a `main`. La demo añade una nueva operación en una rama de funcionalidad y comprueba que el workflow la valida antes de integrarla.
