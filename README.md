# Ejercicios Python 

Docente: Estefanía Arias Torres

Escuela Superior Politécnica del Litoral

:exclamation:Para obtener la versión mas actualizada de esta página, presione CRTL + F5


Recuerde que puede encontrar examenes anteriores en la página Oficial de [Fundamentos de Programación](http://programacion.espol.edu.ec/). Para ingresar deberá ingresar usando sus credenciales. 

Contenido:

[A. Strings y tipos de datos nativos](#a-strings-y-tipos-de-datos-nativos)  
[B. Aleatorios](#b-aleatorios)  
[C. Listas y Estructuras de Control](#c-listas-y-estructuras-de-control)




**Para las secciones A, B y C, se asume que el usuario ingresa exactamente lo que se le solicita.**
### A. Strings y tipos de datos nativos

1. Escriba un programa que solicite una palabra al usuario, y luego muestre **True** si la palabra es palíndrome, sino deberá mostrar **False**

2. Usted trabaja en una empresa de telefonía, y requiere calcular el tiempo de una llamada y el costo de la misma. El valor de la llamada por segundo es $0.002 . Escriba un programa que solicite al usuario, la hora de inicio y fin de la llamada, y le muestre por pantalla el tiempo en segundos que ha durado la llamada y el costo total a pagar.

Ejemplo:

```
Calculadora de Costo de Llamada:

Ingrese hora de inicio (hh:mm:ss): 09:08:08
Ingrese hora de fin (hh:mm:ss): 10:09:15

Su llamada duró 3667 segundos y su valor a pagar es $ 7.33

```
3. Escriba un programa de Python que le solicite una palabra al usuario y luego haga el siguiente cambio:

- Cambiar todas las ocurrencias de la primera letra de la cadena por un `$` **a excepción de la primera letra.**

Ejemplos:
```
Ingrese una palabra: restart
Salida: resta$t
```

```
Ingrese una palabra: amapolas amarillas
Salida: am$pol$s $m$rill$s
```

4. Escriba un programa que remueva todos los caracteres que se encuentren en posición par. 
Ejemplo:

```
Ingrese una palara: marioneta
Salida: aint
```

### B. Aleatorios

1. Genere una fecha aleatoria. Es decir un número que corresponda a los meses y otro para el año (1900-2100). 
Muéstrelo en pantalla y además indique el número de meses que faltan o que han transcurrido desde dicha fecha. Puede tomar como referencia el mes actual 06/2023.

2. Dada la siguiente lista de cartas:
```
cartas = [“AS”, 2, 3, 4, 5, 6, 7, 8 , 9, 10, “J”, “Q”, “K”]
```

Generar una carta aleatoria, y luego solicitar al usuario el ingreso de otra carta. Si el usuario adivina la carta que sacó el computador, entonces gana el juego. Mostrar los mensajes correspondientes. **No modificar la lista de cartas.**

3. Escriba un programa que intercambie 2 letras en una palabra. Para esto deberá escoger 2 indices aleatorios y luego intercambiarlos. 


### C. Listas y Estructuras de Control
Los siguientes ejericios requieren uso de Estructuras de Control como for y while. 

1. Concatenar 2 litas índice por índice. 

Ejemplo:

```
list1 = [“Ho” , “m”, “nom”,”e”, “Ju”] 
list2 = [“la”, “i”, “bre”, “s”, “lia”]

Salida: 

[“Hola”, “mi”, “nombre”, “es”, ”Julia”]


```
2. Dada 2 listas, recorrer y mostrar por pantalla como se muestra a continuación. **(No usar la función reserve)**

```
L1 = [10, 20, 30, 40]
L2 = [100, 200, 300, 400]

Salida:

10 400
20 300
30 200
40 100
```

3. Remover los string vacíos de una lista.

```
L3 = [“hola”, “”, “soy” , “”, “una”, “”, “”, “lista”]

Salida:
L4 = [“hola”, “soy”, “una”, “lista”]
```

4. Dado un párrafo, mostrar el texto sin tildes y a su vez mostrar la cantidad de vocales totales que contiene dicho texto. (Ej. 25 vocales en total, no es necesario que indiquen cuántas a,e, etc. )

5. Escriba un programa que dado una lista L, imprima por pantalla cuantos elementos de cada lista son números enteros y cuantos son sólo letras. 
Ejemplo:

```
L = ["hola", "1.25","1500","fundamentos", "20 años","2.5", "100", "ESPOL"]

Salida:
Existen 3 palabras en su lista.
Existen 2 números enteros en su lista.
```

6. Continuando con el ejercicio anterior, ahora muestre qué elementos de la lista con sólo número enteros, sólo letras y cuáles son otros tipos de datos. Adicional mostrar la suma de los números encontrados. Ejemplo:

```
L = ["hola", "1.25","1500","fundamentos","20 años","2.5","100","ESPOL"] 

Salida de su programa:
Letras: ['hola', 'fundamentos', 'ESPOL'] 
Números enteros: [1500, 100], 
Suma: 1600 
Otros: ['1.25', '20 años', '2.5']
```
7. Escriba un programa que solicite varios números al usuario, **hasta** que la suma de dichos números sea igual o mayor a 1000. Además, mostrar la suma final de todos los numeros ingresados y el número de intentos. 
 
Ejemplo:

```
Ingrese un número: 23
Ingrese un número: 561
Ingrese un número: 25
Ingrese un número: 96
Ingrese un número: 152
Ingrese un número: 32
Ingrese un número: 56
Ingrese un número: 74

Gracias! Ha completado 1019 en 8 intentos.
```
8. Escriba un programa que le solicite un número al usuario y luego muestre la cuenta regresiva hasta llegar al mismo número, pero negativo. Ejemplo:
```
Ingrese un número: 6

Salida:
-6   -5  -4  -3  -2  -1  0  1  2  3  4  5  6
```

Tip: Para imprimir modifique el argumento “end” de la función print. [Ver Video](https://www.youtube.com/watch?v=vOeJqv1kGpo)

9. Escriba un programa que le solicite un número al usuario y luego muestre una pirámide de acuerdo al número ingresado. Ejemplo:

```
Ingrese un número: 6

*
**
***
****
*****
******
*****
****
***
**
*
```

10. Implementar un programa que agregue `*` antes y despues de cada vocal de una palabra ingresada por el usuario. 
En caso de haber 2 vocales juntas, se deberá mostrar sólo 1 asterisco. Ejemplos:

```
Ingrese una palabra: mercado 
Salida: m*e*rc*a*d*o*

Ingrese una palabra: continuar 
Salida: c*o*nt*i*n*u*a*r

```




