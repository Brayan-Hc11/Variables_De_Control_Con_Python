# 3.3 Actividad de Aprendizaje 3. Utilizar estructuras de control condicionales en Python cumpliendo requerimientos técnicos.  

## Duración: 12 horas  

Una vez revisado el componente formativo tres: Estructuras de control condicionales, desarrolle las siguientes evidencias de aprendizaje:  

## ⮚ Taller 3: condicionales simples.  

Como primera evidencia a presentar en esta actividad de aprendizaje 3, elabore el Taller 3: condicionales simples. Realice lo siguiente: 	 

A. Digite: “IDLE” en la barra de tareas de su computador, para activar el editor de Python.  

B. Abra un nuevo archivo usando las opciones File - New File o las teclas: CTRL+N  

C. Digite el siguiente código del lenguaje Python: 

![image](https://github.com/Brayan-Hc11/Variables_Y_Estructuras_De_Control_En_Python/assets/118775234/cb225341-aa5a-4f61-9711-68d501852405)

D. Guarde el programa digitado usando la opción File – Save o las teclas CTRL+S.  

E. Ejecute el programa con la opción: Run – Run Module o la tecla F5  

F. Verifique los resultados. Modifique el código a sus gustos personales y repita los 3 últimos pasos. g. Abra un nuevo documento Word con sus datos personales y el título: AA3-EV1 TALLER 3  

H. Pegue el código final elaborado con el lenguaje Python.  

I. Capture un pantallazo de los resultados del programa y péguelo en su documento Word.  

J. Almacene el documento de Word con el nombre: AA3-EV1 Taller 3  

Lineamientos para la entrega de la evidencia:  

● Producto a entregar: Taller 3: Condicionales simples.  

● Formato: documento PDF ● Para enviar la evidencia desarrollada: ubique el enlace para el 		envío de la evidencia: AA3-EV01 Taller 3: condicionales simples.
***

## Solución
_Código fuente:_

~~~
#Taller 3: Condicionales simples
#Elaborado por: Brayan Andres Hernandez Colon
#fecha: 16/10/2023

#Definimos Fecha actual
from datetime import date
Hoy = date.today()
print("Hoy es el dia: ",Hoy)

#Declaramos variables
A = int(input("Digite el valor de A: "))
B = int(input("Digite el valor de B: "))
#iniciamos sentencia condicional (if)

if A>=B:
    print("A es mayor a B")
else:
    print("A es menor a B")
print()
Cur1 = 'Requerimientos'
Cur2 = 'Algoritmos'

print("El curso 1 es: ",Cur1)
print("El curso 2 es: ",Cur2)
#sentencia condicional (if) con sentencias logicas

if Cur1 == 'Requerimientos' and Cur2 == 'Algoritmos':
    print("Usted estudia programación de software")
else:
    print("Usted estudia otro programa diferente a programación de software")
print()
print('*** Final de Análisis del programa de formación SENA ***')
print()

#sentencias condicionales en cadenas de caracteres
Frase = input("Digite una Oracion: ")
print("La frace en Mayúculas es: ",Frase.upper())
Longitud = len(Frase)

print("La longitud de la frase es: ",len(Frase)," Caracteres")
if Longitud>10:
    print("La frase ingresada contiene más de 10 caracteres")
else:
    print("La frase ingresada continte menos de 10 caracteres")
print()
print("Se ha finalizado el programa")
~~~

_Resultado de ejecución:_

![image](https://github.com/Brayan-Hc11/Variables_Y_Estructuras_De_Control_En_Python/assets/118775234/421ed17c-41a7-4391-b3bc-25725fc010ac)

