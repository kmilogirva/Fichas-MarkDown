<h1 style="text-align: center;" > Guia de programación en C#</h1>
<div style="text-align: center;" >
  <h2><strong>OPERADORES EN C#</strong></h2>
</div>

## ➕ ¿Qué son los operadores?

Los operadores son símbolos que nos permiten realizar operaciones sobre variables o valores. Pueden ser matemáticos, lógicos, de comparación, entre otros.

🧮 **Operadores Matemáticos**
Se usan para realizar cálculos básicos como suma, resta, multiplicación, etc.

<div style="text-align: center;" >
  <h4><strong>🔢 Principales operadores matemáticos</strong></h4>
</div>            


| Operador| Descripción| Ejemplo ->Resultado|
|---------|------------|------------|
|`+`|`Suma`|`5 + 3 → 8`|
|`-`|`Resta`|`5 - 3 → 2`|
|`*`|`Multiplicación`|`5 * 3 → 15`|
|`/`|`División`|`15 / 3 → 5`|
|`%`|`Módulo (resto)`|`	9 % 4 → 1`|


<div style="text-align: center;" >
  <h4><strong>🎯 Aplicación práctica operadores matemáticos</strong></h4>
</div>  

```Csharp
Console.WriteLine("Suma: " + (a + b));
Console.WriteLine("Resta: " + (a - b));
Console.WriteLine("Multiplicación: " + (a * b));
Console.WriteLine("División: " + (a / b));
Console.WriteLine("Módulo: " + (a % b));
```
⚖️ **Operadores de Comparación**
Se usan para comparar dos valores. El resultado siempre será true o false.

🔍 **Operadores de comparación**

|Operador|Significado|Ejemplo (true o false)|
|--------|-----------|----------------------|
|==	|Igual a|5 == 5 → true|
|!=	|Diferente de|4 != 3 → true|
|>	|Mayor que|6 > 2 → true|
|<|Menor que|3 < 5 → true|
|>=	|Mayor o igual que|7 >= 7 → true|
|<=|Menor o igual que|2 <= 3 → true|

<div style="text-align: center;" >
  <h4><strong>✏️ Ejemplo práctico:</strong></h4>
</div>       


```Csharp
int x = 5;
int y = 10;

Console.WriteLine(x == y); // false
Console.WriteLine(x != y); // true
Console.WriteLine(x < y);  // true
Console.WriteLine(x >= y); // false

```
🤔 Operadores Lógicos
Se utilizan para combinar condiciones booleanas (true o false).

⚙️ Operadores lógicos comunes
Operador	Nombre	Descripción	Ejemplo
&&	AND lógico	Verdadero si ambas condiciones son verdaderas	(5 > 2 && 3 < 4) → true
`		`	OR lógico
!	NOT lógico	Invierte el valor de verdad	!(5 == 5) → false
✏️ Ejemplo práctico:
csharp
Copiar código
bool esMayor = true;
bool esEstudiante = false;

Console.WriteLine(esMayor && esEstudiante); // false
Console.WriteLine(esMayor || esEstudiante); // true
Console.WriteLine(!esMayor);                // false