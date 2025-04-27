# Sistema de Gestión de Torneos de eSports

## Autor

Yeray Valdepeñas Terrero

@assxavi

## Descripción del Proyecto

Este proyecto implementa un sistema de gestión de torneos de eSports, 
aplicando principios de Programación Orientada a Objetos (POO) y utilizando
diagramas UML para su modelado estructural y funcional.

Link del repositorio 'https://github.com/assxavi/DiagramasUml.git'

Este proyecto implementa un sistema de gestión de torneos de eSports
utilizando UML para el modelado y Java para la implementación.

## Diagramas UML


### Diagrama de Casos de Uso

![Diagrama de casos de uso](diagrams/casos-uso.png)

### Diagrama de Clases

![Diagrama de clases](diagrams/clases.png)

## Estructura del Proyecto


├── diagrams/
│ ├── casos-uso.png
│ ├── clases.png
├── README.md
├── .gitignore

## Justificación del Diseño

El sistema ha sido diseñado siguiendo una arquitectura modular que separa claramente las responsabilidades:

· Modelo (Entidad): Representa las entidades principales del dominio, como Equipo, Jugador y Torneo. Cada entidad 
encapsula sus atributos y comportamientos, respetando el principio de encapsulamiento de la POO.

· Control: Las clases de control (GestorEquipos, GestorTorneos) gestionan la lógica de negocio, coordinando 
las interacciones entre las entidades y la vista.

· Vista: Aunque básica, la vista maneja la interacción con el usuario a través de una interfaz de consola, 
siguiendo el patrón MVC (Modelo-Vista-Controlador).

Se utilizaron diagramas UML para planificar visualmente el sistema antes de su implementación, 
asegurando una estructura robusta y una correcta relación entre las clases (asociaciones, composiciones, herencias).

Además, se aplicaron buenas prácticas de codificación:

· Paquetes bien organizados.

· Métodos y atributos con visibilidad adecuada.

· Convenciones de nomenclatura estándar.

## Conclusiones

Este proyecto ha permitido poner en práctica conceptos esenciales del diseño y desarrollo de software, como:

· El análisis de requisitos a partir de un escenario realista (torneos de eSports).

· La correcta aplicación de los diagramas UML como herramientas de planificación y comunicación.

· El diseño modular, facilitando la mantenibilidad y escalabilidad del sistema.

· El refuerzo de la Programación Orientada a Objetos (POO) con especial atención a la encapsulación, modularidad y reutilización de código.

Gracias a esta actividad, he mejorado mi capacidad para estructurar sistemas software desde su análisis hasta su implementación, preparándome mejor para futuros proyectos de mayor envergadura.
