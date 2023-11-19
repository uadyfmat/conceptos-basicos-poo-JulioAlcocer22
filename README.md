## Diferencia entre clase y objeto
La diferencia es que la clase es la idea general de algo, es como una plantilla que contiene como es y como se comporta, y el objeto ya es la "personificación" de essa idea o plantilla, el cual tiene atributos y métodos, y puede interactuar con los demás componentes que hayan.

## Diferencia entre clase e interfaz
Ambas aplican el concepto de programación por contrato, la diferencia radica en que en una interfaz ninguno de los métodos están implementados, y en una clase abstracta pueden haber n métodos y solo uno no está implementado. En ambos casos los métodos se deben de implementar, pero con la interfaz se implementan en aquellas clases que implementen dicha interfaz, y en las clases en aquellas que hereden a la clase padre que es abstracta.

## Qué es polimorfismo
Es la capacidad de una referencia de comportarse como el objeto al que apunta.

## ¿Qué representa la asociación en un Diagrama de Clases?
La asociacion representa la relación entre dos entidades de un todo, en este caso, las clases/interfaces del programa.
Un ejemplo es la asociación puede ser la herencia, en donde la abstracción de clases hace que la clase padre tenga los atributos y métodos más generales, y las clases hijas los hereda. Se representa como una tipo de "subordinación", donde la clase padre esta arriba y las hijas están debajo, uniéndolas con flechas que apuntan a la clase padre.


## Diferencia entre composición vs Agregación
Que en la agregación no hay una relación entre los objetos enlazados (ambos existen sin la necesidad del otro), en cambio en la composición los componentes si estan estrechamente relacionados los unos con los otros


## Encapsulamiento
El encapsulamiento es una propiedad que permite determinar el alcance de los datos en una estrucutura, pudiendo ser manipulados unicamente en la clase en la que están, en dicha clase y en las que la hereden, o en todo el programa. Con esto se evita que se puedan cambiar o acceder datos desde cualquier parte del programa.

## Modularidad
Es que cada pieza de código haga una única tarea, tratando de que sea lo más independiente de las demás.
Un ejemplo sería que si una funcionalidad a implementar es que se limpien datos (Strings), a cada módulo le corresondría una tarea: quitar acentos, quitar mayúsculas, separar oraciones.

## Considerando polimorfismo, diferencia de usar herencia o interfaces
La principal diferencia es que con la herencia podríamos agrupar a los objetos que estén reelacionados y compartan mucho en común, en cambion con las interfaces los objetos pueden no tener ninguna relación, pero tienen alguna funcionalidad compartida, y se pueden agrupar por funcionalidad.