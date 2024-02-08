# cvds-lab2
## Integrantes
### Manuel Suarez - Yeltzyn Sierra
## Preguntas
## ¿Cuál fábrica hiciste? y ¿Cuál es mejor?
### En este proyecto, se utiliza el patrón Factory Method para crear instancias de objetos Shape basados en un tipo específico de figura geométrica, como triángulos, cuadriláteros, pentágonos y hexágonos. Aquí hay algunas razones por las que se utiliza el Factory Method en este contexto:
### Abstracción de la creación de objetos: El Factory Method encapsula la lógica de creación de objetos Shape en un único lugar. Esto permite desacoplar el código que utiliza las formas geométricas de los detalles de implementación de cómo se crean esas formas.
### Flexibilidad y extensibilidad: El Factory Method facilita la adición de nuevas implementaciones de formas geométricas en el futuro. Simplemente necesitas agregar una nueva clase que implemente la interfaz Shape y actualizar el Factory Method para que pueda crear instancias de esa nueva clase.
### Centralización del código de creación: Al tener un único punto de creación de objetos Shape, es más fácil mantener y gestionar el código relacionado con la creación de instancias.
### Separación de responsabilidades: El Factory Method promueve la separación de responsabilidades al permitir que las clases que utilizan las formas geométricas se concentren en su funcionalidad principal sin preocuparse por los detalles de cómo se crean las formas.
