# 43-ejercicios-
//ejercicio 1
using System;
namespace HelloWorld
{
  class Program
  {
    static void Main(string[] args)
    {
      Console.WriteLine("Hello World!");    
    }
  }
}
//ejercicio 2
Console.WriteLine("Digite su nombre: ");
    string nombre = Console.ReadLine();
    while (string.IsNullOrWhiteSpace(nombre))
    {
        Console.WriteLine("El nombre no puede estar vacio. Intente nuevamente");
        nombre = Console.ReadLine();
    }
    
    Console.WriteLine("Digite su edad: ");
    string edadTexto = Console.ReadLine();
    int edad;
    while (!int.TryParse(edadTexto, out edad))
    {
        Console.WriteLine("La edad debe ser un numero. Intente nuevamente");
        edadTexto = Console.ReadLine();
    }
    
    Console.WriteLine("Digite su direccion: ");
    string direccion = Console.ReadLine();
    while (string.IsNullOrWhiteSpace(direccion))
    {
        Console.WriteLine("La dirección no puede estar vacia. Intente nuevamente ");
        direccion = Console.ReadLine();
    }
    
    Console.WriteLine("Digite su gmail: ");
    string gmail = Console.ReadLine();
    while (string.IsNullOrWhiteSpace(gmail))
    {
        Console.WriteLine(" El gmail no puede estar vacio. Intente nuevamente");
        gmail = Console.ReadLine();
    }
    
    Console.WriteLine("Datos:");
    Console.WriteLine("Nombre: " + nombre);
    Console.WriteLine("Edad: " + edad);
    Console.WriteLine("Direccion: " + direccion);
    Console.WriteLine("Gmail: " + gmail);
    
    int num1 = (2 + 4);
    double num2 = num1 * num1;
    
    int num3 = (4 * 8);
    double num4 = num3 * num3 * num3;
    
    double divi = num2 / num4;
    
    Console.WriteLine("numero 1 " + num2);
    Console.WriteLine("numero 2 " + num3);
    
    Console.WriteLine("Respuesta: " + divi);
    
    double max = Math.Max(5, 10);
    double min = Math.Min(5, 10);
    Console.WriteLine(max);
    Console.WriteLine(min);
    
        double raiz = Math.Sqrt(64);
        Console.WriteLine(raiz);
    
        double abs = Math.Abs(-4.5);
        Console.WriteLine(abs);
    
        double redondeo = Math.Round(0.0010986328125);
        Console.WriteLine(redondeo);
    
        Console.WriteLine("Longitud de direccion: " + direccion.Length);
    
        Console.WriteLine("Nombre: " + nombre.ToUpper());
        Console.WriteLine("gmail: " + gmail.ToLower());
//ejercicio 3
    int myNum = 15;
    myNum = 20; 
    Console.WriteLine(myNum);
//ejercicio 4
    const int myNum = 15;
    myNum = 20; 
// ejercicio 5
    string name = "maria";
    Console.WriteLine("Hello " + name);
//ejercicio 6
    int x = 5;
    int y = 6;
    Console.WriteLine(x + y);
//ejercicio 7
    Console.WriteLine("Dijite el numero 1: ");
    double num1 = Double.Parse(Console.ReadLine());

    Console.WriteLine("Dijite el numero 2: ");
    double num2 = Double.Parse(Console.ReadLine());
    
    Console.WriteLine("Dijite el numero 3: ");
    double num3 = Double.Parse(Console.ReadLine());
    
    Console.WriteLine("Dijite el numero 4: ");
    double num4 = Double.Parse(Console.ReadLine());
    
    double suma = num1 + num2 + num3 + num4;
    double resta = num1 - num2 -num3 - num4;
    double multi = num1 * num2 *num3 * num4;
    double divi = num1 / num2;
    
    Console.WriteLine($"Suma: {num1} + {num2} + {num3} + {num4} = " + suma);
    Console.WriteLine($"Resta:  {num1} - {num2} - {num3} - {num4} ="+ resta);
    Console.WriteLine($"Multiplicacion: {num1} * {num2} * {num3} * {num4} =" + multi);
    Console.WriteLine($"Division: {num1} / {num2} =" + divi);
//ejercicio 8
    int myNum = 100000;
    Console.WriteLine(myNum);
//ejercicio 9
    double myNum = 19.99D;
    Console.WriteLine(myNum);
//ejercicio 10
    int myInt = 9;
    double myDouble = myInt;       
    Console.WriteLine(myInt);     
    Console.WriteLine(myDouble);
//ejercicio 11
    double myDouble = 3.65;
    int myInt = (int) myDouble;    
    Console.WriteLine(myDouble);   
    Console.WriteLine(myInt);
//ejercicio 12
    int myInt = 12;
    double myDouble = 3.24;
    bool myBool = true;

    Console.WriteLine(Convert.ToString(myInt));    
    Console.WriteLine(Convert.ToDouble(myInt));    
    Console.WriteLine(Convert.ToInt32(myDouble));  
    Console.WriteLine(Convert.ToString(myBool));
//ejercicio 13
    Console.WriteLine("Enter your age:");
    int age = Convert.ToInt32(Console.ReadLine());
    Console.WriteLine("Your age is: " + age);
//ejercicio 14
    Console.WriteLine("digite el numero que desee: ");
    int num = int.Parse(Console.ReadLine());
    switch (num)
    {
        case 1:
            Console.WriteLine("Monday");
            break;
        case 2:
            Console.WriteLine("Tuesday");
            break;
        case 3:
            Console.WriteLine("wednesday");
            break;
        case 4:
            Console.WriteLine("thursday");
            break;
        case 5:
            Console.WriteLine("Friday");
            break;
        case 6:
            Console.WriteLine("Saturday");
            break;
        case 7:
            Console.WriteLine("Sunday");
            break;
//ejercicio 15
    class Car
  {
    private string model = "Mustang";
    static void Main(string[] args)
    {
      Car myObj = new Car();
      Console.WriteLine(myObj.model);
    }
  } 
//ejercicio 16
   class Program
  {
    static void Main(string[] args)
    {
      Person myObj = new Person();
      myObj.Name = "Liam";
      Console.WriteLine(myObj.Name);
    }
  }
//ejercicio 17
  Ciudadano c = new Ciudadano("1073232883");
  Console.WriteLine("el dni es: " + c.DNI);
//ejercicio 18
  int day = 7; 
        switch (day)
        {
            case 6:
            Console.WriteLine("today is Saturday. ");
            break;
            case 7:
            Console.WriteLine("today is Saturday. ");
            break;
            default:
            Console.WriteLine("Looking forward to the weekend.");
            break;
        }
    }
}
//ejercicio 18 
  int myInt = 9;
        double myDouble = myInt;
        Console.WriteLine(myInt);
        Console.WriteLine(myDouble);
        }
}
//ejercicio 19
  double myDouble= 9.78;
        int myInt = (int) myDouble;
      
        Console.WriteLine(myDouble);
        Console.WriteLine(myInt);
        }
}
//ejercicio 20
 double myDouble= 5.48;
        int myInt = (int) myDouble;
      
        Console.WriteLine(myDouble);
        Console.WriteLine(myInt);
        }
}
//ejercicio 21
using System;

public class ejercicio2
{
    public static void Main(string[] args)
    {
        int myInt = 10;
        Console.WriteLine(Convert.ToString(myInt));
        }
}
//ejercicio 22
using System;

namespace MyApplication
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.Write("Ingresa tu nombre: ");
            string nombre = Console.ReadLine();

            Console.Write("Ingresa tu edad: ");
            int edad = int.Parse(Console.ReadLine());

            Console.WriteLine("Tu nombre es: " + nombre + " y tienes " + edad + " años.");
        }
    }
}
//ejercicico 23
using System;

public class ejercicio3
{
    public static void Main(string[] args)
    {
      int x = 180 + 60;
      Console.WriteLine(x);
        }
}
//ejercicio 24
using System;

public class ejercicio3
{
    public static void Main(string[] args)
    {
      Double x = 4.23 + 2.60;
      Console.WriteLine(x);
        }
}
//ejercicio 25
using System;

public class ejercicio3
{
    public static void Main(string[] args)
    {
        int sum1 = 100+30;
        int sum2 = sum1 + 250;
        int sum3 = sum2 + sum2;
        Console.WriteLine(sum1);
        Console.WriteLine(sum2);
        Console.WriteLine(sum3);
    }
}
//ejercicio 26
using System;

public class ejercicio3
{
    public static void Main(string[] args)
    {
        int sum1 = 100+30;
        double sum2 = sum1 + 534.72;
        double sum3 = sum1 + sum2;
        Console.WriteLine(sum1);
        Console.WriteLine(sum2);
        Console.WriteLine(sum3);
    }
}
//ejercicio 27
using System;

public class ejercicio3
{
    public static void Main(string[] args)
    {
        int x = 10;
        Console.WriteLine(x);
    }
}
//ejercicio 28
using System;

public class ejercicio3
{
    public static void Main(string[] args)
    {
        int x = 10;
        
        x += 5;
        Console.WriteLine(x);
    }
}
//ejercicio 29
using System;

public class ejercicio3
{
    public static void Main(string[] args)
    {
      int x = 5;
      int y = 3;
      Console.WriteLine(x>y);
    }
}
//ejercicio 30

using System;

public class ejercicio2
{
    public static void Main(string[] args)
    {
       int tarifahora = 7900;
       Console.WriteLine("ingrese las horas: ");
       int hotas = int.Parse (Console.ReadLine());
       
       int costot = hotas * tarifahora;
       Console.WriteLine("horas estimadas: " + hotas);
       Console.WriteLine("Tarifa por hora:$"+ tarifahora);
       Console.WriteLine("costo total:"+ costot);
        }
}
//ejercicio 31
using System;

public class Ejercicio31
{
    public static void Main(string[] args)
    {
        string[] productos = { "Arroz", "Leche", "Pan" };
        int[] stock = { 30, 60, 20 };
        double[] precios = { 6000, 5000, 2000};
        Console.WriteLine("INVENTARIO");
        Console.WriteLine(productos[0] + " - Stock: " + stock[0] + " - Precio: " + precios[0]);
        Console.WriteLine(productos[1] + " - Stock: " + stock[1] + " - Precio: " + precios[1]);
        Console.WriteLine(productos[2] + " - Stock: " + stock[2] + " - Precio: " + precios[2]);
        Console.WriteLine("Buscar producto: ");
        string producto = Console.ReadLine();
        Console.WriteLine("El producto no esta disponible: ");
        Console.WriteLine("Cantidad vendida: ");
        int cantidadven = Convert.ToInt32(Console.ReadLine());
        double subtotal = cantidadven * precios[0];
        stock[0] -= cantidadven;
        Console.WriteLine("FACTURA");
        Console.WriteLine("Producto: " + productos[0]);
        Console.WriteLine("Cantidad: " + cantidadven);
        Console.WriteLine("Precio unitario: " + precios[0]);
        Console.WriteLine("Subtotal: " + subtotal);
        Console.WriteLine("Stock restante: " + stock[0]);
    }
}
//ejercicio 32}
using System;

public class Ejercicio31
{
    public static void Main(string[] args)
    {
       Console.Write("Buscar producto: ");
       string producto = Console.ReadLine();
       Console.WriteLine("El producto " + producto + " no esta disponible en inventario.");
       Console.Write("Cantidad vendida: ");
       int cantidadven = Convert.ToInt32(Console.ReadLine());
       Console.Write("Precio unitario: ");
       double preciouni = Convert.ToDouble(Console.ReadLine());
       double subtotal = cantidadven * preciouni;
       int stockini = 100;
       stockini -= cantidadven;
       Console.WriteLine("FACTURA");
       Console.WriteLine("Producto: " + producto);
       Console.WriteLine("Cantidad: " + cantidadven);
       Console.WriteLine("Precio unitario: " + preciouni);
       Console.WriteLine("Subtotal: " + subtotal);
       Console.WriteLine("Stock restante: " + stockini);
    }
}
//ejercicio 33
using System;
public class HelloWorld
{
    public static void Main(string[] args)
    {
        Console.WriteLine("El destino es: ");
        string destino = Console.ReadLine();
        Console.WriteLine("Numero de pasajeros: ");
        int pasajeros = Convert.ToInt32(Console.ReadLine());
        Console.WriteLine("Costo por persona: ");
        double costoporp = Convert.ToDouble(Console.ReadLine());
        double presupuestov = pasajeros * costoporp;
        bool descuentoa = (pasajeros > 5 && destino == "barcelona");

        if (descuentoa)
        {
            double descuento = presupuestov * 0.10;
            presupuestov -= descuento;
        }

        Console.WriteLine("Presupuesto total del viaje: $" + presupuestov);
    }
}
//ejercicio 34
using System;

public class HelloWorld
{
    public static void Main(string[] args)
    {
        int nota = 85;
        if (nota >=90 ) {Console.WriteLine ("A");}
        else if (nota >=80 ) {Console.WriteLine ("b");}
        else if (nota >=70 ) {Console.WriteLine ("C");}
        else {
                Console.WriteLine ("Necesitas mejorar");}
        
    }
}
//ejercicio 35
using System;

public class HelloWorld
{
    public static void Main(string[] args)
    {
        // Se le pregunta al usuario si tiene licencia
        Console.WriteLine("Tiene licencia");
        string tienelicencia = Console.ReadLine();
        
        // Se solicita la cantidad de años de experiencia
        Console.WriteLine("Años de experiencia");
        int añosExperiencia = int.Parse(Console.ReadLine());
        
        // Se verifica si cumple las condiciones:
        // tener licencia y mínimo 2 años de experiencia
        if(tienelicencia == "si" && añosExperiencia >= 2)
        {
            Console.WriteLine("Puedes aplicar para el puesto");
        }
        else 
        { 
            Console.WriteLine("No puedes aplicar para el puesto");
        }
    }
}
//ejercicio 36
using System;

public class HelloWorld
{
    public static void Main(string[] args)
    {
        int day = 4;
        switch(day)
        {
            case 1 :
                Console.WriteLine("Hoy es Lunes");
                break;
            case 2 :
                Console.WriteLine("Hoy es Martes");
                break;
            case 3 :
                Console.WriteLine("Hoy es Miercoles");
                break;
            case 4 :
                Console.WriteLine("Hoy es Jueves");
                break;
            default :
                Console.WriteLine("Fin de semana : ");
                break;
            
        }
    }
}
//ejercicio 37
using System;

public class HelloWorld
{
    public static void Main(string[] args)
    {
        int i =0;
        while (i<5){
            Console.WriteLine(i);
            i++;
        }
    }
}
//ejercicio 38
using System;

namespace MyApplication
{
  class Program
  {
    static void Main(string[] args)
    {
      string[] cars = {"Volvo", "BMW", "Ford", "Mazda"};
      Console.WriteLine(cars[0]);
    }
  }
}
//ejercicio 39
string[] cars = {"Volvo", "BMW", "Ford", "Mazda"};
cars[0] = "Opel";
Console.WriteLine(cars[0]);
//ejercicio 40
string[] cars = {"Volvo", "BMW", "Ford", "Mazda"};
Console.WriteLine(cars.Length);
//ejercicio 41
string[] cars = {"Volvo", "BMW", "Ford", "Mazda"};
foreach (string i in cars) 
{
  Console.WriteLine(i);
}
//ejercicicio 42
int[,] numbers = { {1, 4, 2}, {3, 6, 8} };

for (int i = 0; i < numbers.GetLength(0); i++) 
{ 
  for (int j = 0; j < numbers.GetLength(1); j++) 
  { 
    Console.WriteLine(numbers[i, j]); 
  } 
}  
//ejercicio 43
int[,] numbers = { {1, 4, 2}, {3, 6, 8} };

foreach (int i in numbers)
{
  Console.WriteLine(i);
}
