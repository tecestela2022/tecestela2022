Programa  gestion empleados

En esta aplicación, se han creado tres clases: Empleado, Desarrollador y Diseñador. 

La clase Empleado es la clase base que contiene los atributos nombre y sueldo, así como los métodos para obtener el nombre y el sueldo del empleado, y para calcular el salario neto (sueldo después de aplicar descuentos).

La clase Desarrollador extiende la clase Empleado y sobrescribe el método calcularSalarioNeto para retornar el sueldo sin aplicar ningún descuento.

La clase Diseñador también extiende la clase Empleado y sobrescribe el método calcularSalarioNeto para retornar el sueldo con un descuento del 5%.

En el controlador DefaultController, se crean instancias de las clases Empleado, Desarrollador y Diseñador, se utilizan los métodos para obtener el nombre y el salario neto de cada empleado, y se muestra esta información en la pantalla. Además, se está utilizando Symfony para renderizar una plantilla index.html.twig.

En resumen, esta aplicación realiza el cálculo del salario neto de empleados de diferentes categorías (Desarrollador, Diseñador) y muestra esta información en pantalla.
