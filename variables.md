<h1 style="text-align: center;" > Guia de programación en C#</h1>

<div style="text-align: center;" >
  <h2><strong>VARIABLES EN C#</strong></h2>
</div>

---

## 🧠 ¿Qué es entonces una variable?

Una **variable** es como una **cajita** con un nombre, que sirve para guardar datos. Esta caja puede cambiar su contenido a lo largo del tiempo.

Imagina que tienes una caja llamada `edad` donde puedes guardar un número. Puedes abrirla, ver su contenido, cambiarlo o usarlo para hacer cálculos.

---

## 🎯 Propósito de una variable

- **Almacenar datos temporalmente en la memoria del programa.**
- **Facilitar operaciones matemáticas, lógicas o de texto.**
- **Hacer tu código más flexible y dinámico.**
- **Permitir reutilizar valores sin tener que escribirlos múltiples veces.**

---

## 💡 Características clave

- Cada variable tiene:
  - Un **nombre**.
  - Un **tipo de dato** (ej: `int`, `string`, `bool`, etc.).
  - Un **valor** (que puede cambiar).

---

## 🧪 Ejemplos en C#

### 🔹 Declarar una variable
Una cosa es declarar una variable, otra muy diferente inicializarla a continuación miraremos la diferencia.

<div style="text-align: center;" >
  <h6><strong>DECLARAR</strong></h6>
</div>

```csharp
int edad;
```
Como es posible visualizar aquí nuestra variable no posee aún ningun valor, por lo que se peude decir que se encuentra declarada más no **inicializada**

<div style="text-align: center;" >
  <h6><strong>ASIGNAR</strong></h6>
</div>

```csharp
edad = 58;
```
En esta cso lo que se esta realizando es asignar un valor a nuestra varibla antes declarada, en este caso, la edad correspondería a **58**

<div style="text-align: center;" >
  <h6><strong>INICIALIZAR</strong></h6>
</div>

```csharp
int edad= 5;
```

Ya en este otro ejemplo, nuestra variable ha sido declarada e inicializada en la misma linea, esto se ve claramente visible en el valor que le ha sido asignado a nuestra variable.

Donde edad sera igual a **5**.


<div style="text-align: center;" >
  <h4><strong>🔄 Tipos comunes de variables en C#</strong></h4>
</div>




| Tipo de dato | Ejemplo                 | Descripción              |
|--------------|-------------------------|--------------------------|
| `int`        | `int edad = 30;`        | Números enteros          |
| `double`     | `double pi = 3.14;`     | Números decimales        |
| `string`     | `string nombre = "Ana";`| Texto o cadenas de caracteres |
| `bool`       | `bool esEdicion = true;`| Verdadero o falso        |
| `char`       | `char letra = 'A';`     | Un solo carácter         |


<div style="text-align: center;" >
  <h4><strong>🔄 ¿Cómo Usarlo?</strong></h4>
</div>

```csharp

        string studentName = "John Doe";
        int studentID = 15;
        int studentAge = 23;

        // Al flotante se debe agregar la 'f' al final del valor decimal
        float studentFee = 75.25f;

        // Los double no necesitan la 'f'
        double studentDouble = 75.24;

        // Char se declara con comillas simples
        char studentGrade = 'B';

        // Imprimir variables
        Console.WriteLine("Student name: " + studentName);
        Console.WriteLine("Student ID: " + studentID);
        Console.WriteLine("Student age: " + studentAge);
        Console.WriteLine("Student float: " + studentFee);
        Console.WriteLine("Student double: " + studentDouble);
        Console.WriteLine("Student grade: " + studentGrade)
```
