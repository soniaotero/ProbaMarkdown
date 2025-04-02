# Diagrama de Clases en UML usando Mermaid

Este es un diagrama de clases que muestra la relación de herencia entre las clases `Animal`, `Perro` y `Gato`.

```mermaid
classDiagram
    class Animal {
        +String nombre
        +int edad
        +hacerSonido()
    }

    class Perro {
        +String raza
        +ladrar()
    }

    class Gato {
        +String color
        +maullar()
    }

    Animal <|-- Perro
    Animal <|-- Gato
mermaid```
