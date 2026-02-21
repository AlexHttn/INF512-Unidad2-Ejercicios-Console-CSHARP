# INF512-Unidad2-Ejercicios-Console-CSHARP

Implementando Encapsulación y Constructores en C#
Proyecto desarrollado como parte de la asignatura INF-512, Unidad 2.

Ejercicio 1 — Encapsulación con la Clase Producto
Este ejercicio implementa el principio de encapsulación, uno de los pilares de la POO.
La clase Producto modela un producto de tienda con los siguientes atributos privados:

id — Identificador único del producto
descripcion — Nombre o descripción del producto
precio — Precio del producto
stock — Cantidad disponible en inventario

¿Que hace?
Los atributos son privados, lo que significa que no pueden ser modificados directamente desde afuera de la clase. Para acceder a ellos se usan getters (para leer) y setters (para escribir), los cuales incluyen validaciones:

El precio no puede ser negativo.
El stock no puede ser menor que 0.
El método DescontarStock(int cantidad) reduce el stock de forma segura, validando que no quede en negativo.

Conceptos aplicados:
Encapsulación con modificador private
Métodos getter y setter con validación de datos
Protección del estado interno del objeto





Ejercicio 2 — Constructores con la Clase Circulo
Este ejercicio demuestra el uso de constructores para inicializar objetos correctamente desde el momento en que son creados.
La clase Circulo representa un círculo geométrico con un único atributo privado:

radio — El radio del círculo (debe ser mayor que 0)

¿Que hace?
La clase cuenta con dos constructores:
Sin argumentos — Crea un círculo con radio por defecto de 1.0
Con argumento — Crea un círculo con el radio indicado, validando que sea mayor que 0. Si el valor es inválido, muestra un error y asigna 1.0 por defecto

Además ofrece dos metodos de cálculo:
CalcularArea() — Calcula el área usando la fórmula π × radio²
CalcularCircunferencia() — Calcula la circunferencia usando 2 × π × radio

Conceptos aplicados:
Constructores sobrecargados (con y sin parámetros)
Validación de datos en el constructor
Uso de Math.PI para cálculos geométricos
