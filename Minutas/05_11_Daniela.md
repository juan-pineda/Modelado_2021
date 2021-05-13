# Clase Mayo 11, 2021
**Notas hechas por:** Daniela Jaimes G


### Temas discutidos:

Se continúa con el estudio del notebook orientado a [Objetos](https://laconga.redclara.net/courses/modulo-datos/claseMD07/materialesMD07/objetos.html)

* Se explica la diferencia entre colocar 

` def __init__(self):` y `def __init__(self, carga, masa, posicion): `. En el primer caso se define el constructor **init** sin tener en cuenta ningún atributo a la hora de ser llamado, en cambio, en el segundo caso se define con los atributos **masa, carga y posición**, los cuales OBLIGATORIAMENTE tienen que ser especificados a la hora de utilizar el constructor.
    
* Con el ejemplo anterior, si la **posición** se define como un diccionario, pero al constructor **init** se le agrega algo diferente, como una lista o tupla, se genera un **Duck Typing** y el constructor lo va recibir. El problema va ser más adelante cuando se requiera utilizar ese atributo en los métodos.

* Se explica el concepto de **self**, el cual va asociado con los objetos y es necesario agregarlo al principio de los constructores y métodos para hacer referencia a la inicialización de los atributos de ese objeto, así:
`self.atributo = algoritmo relacionado con el atributo` 

* El método estático (`@staticmethod`) consiste en un método donde al crear la instancia de la clase, ese objeto trae consigo las funciones definidas en el método, donde esa función puede o no depender de ciertos atributos.


*** 
### Tareas:
* Quiz de lo visto para la siguiente clase.

***

### [Video-clase](https://drive.google.com/drive/u/0/folders/1I_fhj4_ps6eDI6ejYq5IN1Lg_3UyOzxM)

