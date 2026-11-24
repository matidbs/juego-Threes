Programación III - Universidad Nacional de General Sarmiento

# Trabajo Práctico 1: Threes!

El objetivo del trabajo práctico es implementar una aplicación para jugar al Threes[^1]:

Se juega en una grilla de 4 × 4, sobre la cual el usuario mueve fichas numeradas para combinarlas entre sí. Los números 1 y 2 se fusionan para formar una única ficha de valor 3, y luego pueden combinarse los múltiplos de tres: dos números 3 se combinan para crear un 6, dos números 6 forman un 12, y así sucesivamente. Al presionar una de las flechas del cursor (arriba, abajo, izquierda o derecha), todas las fichas se desplazan una casilla en esa dirección. Cuando una ficha no pueda moverse, las fichas contiguas de esa fila o columna podrán fusionarse o no (siguiendo la dirección), y luego aparecerá una nueva ficha en una celda libre del borde opuesto, cuyo valor será 1, 2 o 3, aleatoriamente. El juego termina cuando no quedan celdas vacías, y no existen fichas contiguas que puedan combinarse. En ese momento, la aplicación debe mostrar al usuario el puntaje obtenido. Los números 1 y 2 no tienen valor, y el valor de los múltiplos de tres crece exponencialmente[^2].

La aplicación debe contar con una interfaz visual (que no supere la resolución de 1366 × 768 píxeles) y con los elementos adecuados para realizar las acciones del juego. Como objetivos opcionales no obligatorios, se pueden contemplar los siguientes elementos:

1. Mostrar en pantalla la nueva ficha que aparecerá a continuación.
2. Registrar los mejores puntajes, y permitir consultar la tabla de posiciones histórica.
3. Hacer una sugerencia de la próxima jugada.

**Condiciones de entrega:** El trabajo práctico se debe hacer en grupos de cuatro personas (excepcionalmente tres), y el proyecto java se debe entregar en un archivo comprimido por mail a todos los docentes de la comisión. Además del código, se debe incluir un documento en el que se describa la implementación y se detallen las decisiones tomadas durante el desarrollo. El código responsable del funcionamiento de la aplicación debe estar claramente separado del código responsable de la interfaz.

Los aspectos que se evaluarán e influirán en la nota final del trabajo son: que la interfaz gráfica sea amigable para el usuario, que cada clase tenga un buen encapsulamiento y una buena cohesión y se evite el acoplamiento entre clases, que el código sea claro de leer y de entender, y que el informe tenga claridad de contenido y una buena presentación. En él, se debe mencionar y justificar qué arquitectura utilizaron para lograr la correcta separación en capas, y cuáles son las buenas prácticas que lograron aplicar, mostrando ejemplos.

**Fecha de entrega:** Domingo 13 de septiembre.

[^1]: El juego tiene una entrada en la Wikipedia: <https://en.wikipedia.org/wiki/Threes>
[^2]: La aplicación oficial está disponible para iOS y Android. Existen versiones online del juego en <http://play.threesgame.com> y en <https://freeapexgears.com/games/threes>.
