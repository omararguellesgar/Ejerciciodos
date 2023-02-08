# sesion04
actividad de clase 04/02/2023
##  Ejercicio 01


## Etapa 01. Descripción del problema
Se requiere un programa en Java para convertir una cantidad de dinero en otros tipos de monedas (al menos a cinco tipos de monedas distintas). 

## Etapa 02. Definición de la solución

~~~
- Entrada
  float cantidad
  String moneda1, moneda2, moneda3, moneda4, moneda5
  double conversion
  
- Proceso
  Solicitar moneda a inicial
  Solicitar cantidad a convertir
  Solicitar moneda para procesar conversión
  
  Si el monto es mayor o igual que cero entonces se convertirá a la moneda deseada
  Si el monto es menor que cero entonces se cancela la operación
 
- Salida
  
  +----------+---------------+---------------------+----------------+
  | CANTIDAD | MONEDA ORIGEN | CANTIDAD CONVERTIDA | MONEDA DESTINO |
  +----------+---------------+---------------------+----------------+
  |       10 |          DLLS |              189.79 |            MXN |
  +----------+---------------+---------------------+----------------+
  |       10 |          DLLS |                8.32 |          LIBRA |
  +----------+---------------+---------------------+----------------+
  |       10 |          DLLS |                9.33 |           EURO |
  +----------+---------------+---------------------+----------------+
  |       10 |          DLLS |               78.38 |        QUETZAL |
  +----------+---------------+---------------------+----------------+
  |       10 |          DLLS |                9.23 |         FRANCO |
  +----------+---------------+---------------------+----------------+

~~~
 
 
 ## Etapa 03. Diseño la solución
 
 ![](https://github.com/edgardegantea/Ejercicio01/blob/master/Diagrama%20de%20clases.png)
 
 ## Etapa 04. Desarrollo de la solución
 
 
 
 
 ## Etapa 05. Depuración pruebas
 
 
 
 ## Etapa 06. Documentación
 
 
 ## Ejercicio 02.
 
 ## Etapa 01. Descripción del problema
 Se requiere un programa en Java para calcular el resultado de la suma, diferencia, producto, módulo y cociente de dos números decimales de cualquier longitud.
 
 ## Etapa 02. Definición de la solución
 
 ~~~
- Entrada
  double num1
  double num2
  double suma
  double diferencia 
  double producto 
  double módulo 
  double cociente

- Proceso
  Solicitar numero 1 y numero 2
  Suma de ambos numeros 
  Resta de ambos numeros 
  Producto de ambos numeros
  Modulo de ambos numeros
  Cociente de ambos numeros
 
- Salida
  El resultado de la suma
  El resultado de la resta 
  El resultado del producto
  El resultado del modulo
  El resultado del cociente
 
 ~~~

 ## Etapa 03. Diseño la solución
 
 ![](https://github.com/omararguellesgar/Ejercicios04-02-2023/blob/master/Diagrama%2004.02.2023.png)

 ## Etapa 04. Desarrollo de la solución
 ~~~
 public class Ejercicio1 {
    double numero1, numero2;

    public Ejercicio1() {
    }

    public Ejercicio1(double numero1, double numero2) {
        this.numero1 = numero1;
        this.numero2 = numero2;
    }

    public double suma() {
        return (this.numero1 + this.numero2);
    }

    public double resta() {
        return (this.numero1 - this.numero2);
    }

    public double multiplicacion() {
        return (this.numero1 * this.numero2);
    }

    public double division() {
        return (this.numero1 / this.numero2);
    }
    public double resto(){
        return (this.numero1%this.numero2);
    }
    @Override
    public String toString() {
        return "Realiza operaciones basicas con 2 numeros cuales quiera" +
                "\n numero1:" + this.numero1
                + "\n numero2:" + this.numero2
                + "\n LA SUMA ES:   " + suma()
                + "\n LA RESTA ES:    " + resta()
                + "\n LA MULTIPLICACION ES:    " + multiplicacion()
                + "\n LA DIVISION ES:    " + division()
                + "\n EL RESTO ES:      "+ resto();


    }
}

 import javax.swing.JOptionPane;
public class Main {

    public static void main(String[] args) {
        Ejercicio1 c = new Ejercicio1(5, 23);
        Ejercicio1 objetoCalculadora = new Ejercicio1();
        objetoCalculadora.numero1 = Double.parseDouble(JOptionPane.showInputDialog("Ingrese un numero;    "));
        objetoCalculadora.numero2 = Double.parseDouble(JOptionPane.showInputDialog("ingrese un numero:    "));

        JOptionPane.showMessageDialog(null, objetoCalculadora.toString());
    }
}
~~~
 
 
 
 ## Etapa 05. Depuración pruebas
 Se verifica que los operadores sean los correctos y realizen la funcion solicitada
 public double suma() {
        return (this.numero1 + this.numero2);
    }

    public double resta() {
        return (this.numero1 - this.numero2);
    }

    public double multiplicacion() {
        return (this.numero1 * this.numero2);
    }

    public double division() {
        return (this.numero1 / this.numero2);
    }
    public double resto(){
        return (this.numero1%this.numero2);
    }
 
 
 ## Etapa 06. Documentación
 
 Mediante el codigo fuente presentado se podran realizar las operaciones artimeticas basicas empleando los metodos implementados, dando como resultado una suma, una   resta, una multiplicación, una division y el modulo de un par de numeros.
 
 
 ##  Ejercicio 03.


## Etapa 01. Descripción del problema
Se requiere un programa en Java para determinar cuál es el número más pequeño, cuál es el número más grande y cuál es el número intermedio de los tres ingresados.

## Etapa 02. Definición de la solución

~~~
- Entrada
  int num1
  int num2
  int num3
  
- Proceso
  Solicitar numero1, numero2 y numero 3
  Si el primer numero ingresado es menor que el tercero y mayor que el segundo entonces el segundo es el intermedio
  Comprobar numero mas pequeño
  Comprobar numero intermedio
  Comprobar numero mas grande

- Salida
  
  
~~~
 
 
 ## Etapa 03. Diseño la solución
 

 
 ## Etapa 04. Desarrollo de la solución
 
 
 
 
 ## Etapa 05. Depuración pruebas
 
 
 
 ## Etapa 06. Documentación
 
 
 ~~~

