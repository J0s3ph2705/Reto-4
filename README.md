# Reto-4
No me funciona VisualCode en mi computador, no se aún por qué, y no entendí cómo hacer un notebook :/. Pero el código esta ahí :)


1. Dado un número entero, determinar si ese número corresponde al código ASCII de una vocal minúscula.
```python
 number=input("Número? ")
if int(number)>=97 and int(number)<=122:
    print("El número pertenece a una letra minúscula")
else:
    print("El número no pertenece a una letra minúscula")
```
2. Dada una cadena de longitud 1, determine si el código ASCII de primera letra de la cadena es par o no.
```python

caracter=input("Cáracter? ")
codigo=ord(caracter)
if int(codigo)%2==0:
    print("El cáracter tiene un código ASCII par")
else:
    print("El cáracter no tiene un código ASCII par")
```
3. Dado un carácter, construya un programa en Python para determinar si el carácter es un dígito o no.
```python
caracter=input("Cáracter? ")
if ord(caracter)>= 48 and ord(caracter)<= 57:
    print("El cáracter es dígito")
else:
    print("El cáracter no es dígito")

```
4. Dado un número real x, construya un programa que permita determinar si el número es positivo, negativo o cero. Para cada caso de debe imprimir el texto que se especifica a continuación:

Positivo: "El número x es positivo"
Negativo: "El número x es negativo"
Cero (0): "El número x es el neutro para la suma"
Dado el centro y el radio de un círculo, determinar si un punto de R2 pertenece o no al interior del círculo.
```python
numero=input("Número? ")
if int(numero)>0: 
    print("El número "+str(numero)+ " es positivo")
elif int(numero)==0:
    print("El número 0 es el neutro para la suma")
else:
    print("El número "+str(numero)+" es negativo")

```
5. Dadas tres longitudes positivas, determinar si con esas longitudes se puede construir un triángulo.
```python
lado1=input("Lado 1? ")
lado2=input("Lado 2? ")
lado3=input("Lado 3? ")
if int(lado1)+int(lado2)>int(lado3)and int(lado1)+int(lado3)>int(lado2): 
    print("Se puede formar el triángulo")
else:
    print("No se puede formar el triángulo")
```
