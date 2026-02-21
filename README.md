# INF512-Unidad2-Ejercicios-Console-CSHARP

Implementando Encapsulación y Constructores en C#
Proyecto desarrollado como parte de la asignatura Lenguaje de Programacion-INF-5120, Unidad 2.

**Ejercicio 1 — Encapsulación con la Clase Producto** <br>
Este ejercicio implementa el principio de encapsulación, uno de los pilares de la POO.
La clase Producto modela un producto de tienda con los siguientes atributos privados:

Id — Identificador único del producto <br>
Descripcion — Nombre o descripción del producto <br>
Precio — Precio del producto <br>
Stock — Cantidad disponible en inventario

¿Que hace? <br>
Los atributos son privados, lo que significa que no pueden ser modificados directamente desde afuera de la clase. Para acceder a ellos se usan getters (para leer) y setters (para escribir), los cuales incluyen validaciones: <br>

El precio no puede ser negativo. <br>
El stock no puede ser menor que 0. <br>
El método DescontarStock(int cantidad) reduce el stock de forma segura, validando que no quede en negativo.

Conceptos aplicados:
Encapsulación con modificador private <br>
Métodos getter y setter con validación de datos <br>
Protección del estado interno del objeto <br>
<br>
<br>
**Ejercicio 2 — Constructores con la Clase Circulo** <br>
Este ejercicio demuestra el uso de constructores para inicializar objetos correctamente desde el momento en que son creados.
La clase Circulo representa un círculo geométrico con un único atributo privado:

radio — El radio del círculo (debe ser mayor que 0)

¿Que hace?
La clase cuenta con dos constructores: <br>
Sin argumentos — Crea un círculo con radio por defecto de 1.0 <br>
Con argumento — Crea un círculo con el radio indicado, validando que sea mayor que 0. Si el valor es inválido, muestra un error y asigna 1.0 por defecto

Además ofrece dos metodos de cálculo: <br>
CalcularArea() — Calcula el área usando la fórmula π × radio² <br>
CalcularCircunferencia() — Calcula la circunferencia usando 2 × π × radio

Conceptos aplicados: <br>
Constructores sobrecargados (con y sin parámetros) <br>
Validación de datos en el constructor <br>
Uso de Math.PI para cálculos geométricos
