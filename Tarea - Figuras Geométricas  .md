**TAREA 5 FIGURAS GEOMÉTRICAS** 

*C.M.I Flores Dubón 7690-18-2542
V.N Alcantara Mendoza 7690-18-1298*

*W.H Carcamo Santos 7690-20-10779
` `Universidad Mariano Gálvez*

*Análisis de Sistemas I*



**Documentación del Proyecto: Aplicación para el Cálculo del Área y Perímetro de Figuras Geométricas**

**Descripción del Proyecto**

El objetivo de este proyecto es desarrollar una aplicación web en Java que permita calcular el área y perímetro de diferentes figuras geométricas. Para lograrlo, se utilizarán los patrones de diseño Factory Method o Abstract Factory Method y Singleton.

**Patrón de Diseño Utilizado**

**Factory Method o Abstract Factory Method**

El patrón de diseño Factory Method o Abstract Factory Method se utilizará para la creación de objetos de las figuras geométricas. Este patrón permite encapsular la lógica de creación de objetos en una clase base abstracta, delegando la creación concreta de objetos a las clases derivadas.

Al utilizar este patrón, se facilita la incorporación de nuevas figuras geométricas en el futuro, ya que solo será necesario crear una nueva clase derivada e implementar los métodos correspondientes.

**Singleton**

El patrón de diseño Singleton se utilizará para garantizar que solo exista una instancia de la clase encargada de realizar los cálculos de área y perímetro. Esto asegura que los cálculos se realicen de forma consistente y evita la creación de múltiples instancias innecesarias.

**Instrucciones para usar el Proyecto**

- Clona el repositorio del proyecto desde Git utilizando el siguiente comando:

git clone <https://github.com/IsabelFD2020/Tarea-5-Analisis-de-Sistemas.git>

- Abre el proyecto en tu entorno de desarrollo Java (Netbeans)
- Navega hasta el paquete que contiene las clases principales del proyecto.
- Observarás las siguientes clases en el paquete:

1. Figuras: Clase que manda a llamar cada una de las subclases de las figuras geométricas

1. Triangulo, Cuadrado, Rectangulo, y Circulo: Clases concretas que heredan de Figuras y proporcionan implementaciones específicas de los métodos para calcular el área. 

1. FactoryFiguras: Clase que implementa el patrón Factory Method o Abstract Factory Method. Contiene un método estático ObtenerAreaFigura que devuelve una instancia de la figura geométrica solicitada, según el tipo de figura pasado como argumento.

1. App: Clase principal que contiene el punto de entrada del programa. En esta clase, se puede interactuar con el usuario para solicitar el tipo de figura geométrica y mostrar los resultados de los cálculos.

- Ejecuta la clase Main para iniciar la aplicación.
- La aplicación mostrará un menú para que el usuario seleccione el tipo de figura geométrica:

Seleccione una figura geométrica:

1\. Triángulo

2\. Cuadrado

3\. Rombo

4\. Trapecio

5\. Círculo

6\. Rectángulo

- Ingresa el número correspondiente a la figura geométrica deseada y presiona Enter.
- La aplicación solicitará los datos necesarios para el cálculo de área y perímetro de la figura seleccionada.
- Después de ingresar los datos, la aplicación mostrará el resultado del cálculo de área y perímetro.
- Puedes realizar más cálculos seleccionando una nueva figura geométrica o salir del programa ingresando 0.










