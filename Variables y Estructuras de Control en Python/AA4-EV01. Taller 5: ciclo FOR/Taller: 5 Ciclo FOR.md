# 3.4 Actividad de aprendizaje 4. Usar estructuras de control iterativas en Python considerando los requerimientos del cliente 

## Duración: 12 horas  

Una vez revisado el componente formativo 4: Ciclos Iterativos con Python., desarrolle las siguientes evidencias de aprendizaje:  

⮚ Taller 5: ciclo FOR  

Como primera evidencia a presentar en esta actividad de aprendizaje 4, elabore el Taller 5: ciclo FOR. Realice lo siguiente:  

A. Digite: “IDLE” en la barra de tareas de su computador, para activar el editor de Python.  

B. Abra un nuevo archivo usando las opciones File - New File o las teclas: CTRL+N  

C. Digite el siguiente código del lenguaje Python: 

![image](https://github.com/Brayan-Hc11/Variables_Y_Estructuras_De_Control_En_Python/assets/118775234/ff4cbf42-7241-429c-8052-55b14c3803b5)

D. Guarde el programa digitado usando la opción File – Save o las teclas CTRL+S.  

E. Ejecute el programa con la opción: Run – Run Module o la tecla F5  

F. Verifique los resultados. Modifique el código a sus gustos personales y repita los 3 últimos 	pasos.  

G. Abra un nuevo documento Word con sus datos personales y el título: AA4-EV1 TALLER 5.  

H. Pegue el código final elaborado con el lenguaje Python.  

I. Capture un pantallazo de los resultados del programa y péguelo en su documento Word.  

J. Almacene el documento de Word con el nombre: AA4-EV1 Taller 5 

Lineamientos para la entrega de la evidencia:  

● Producto a entregar: Taller 5: ciclo FOR  

● Formato: documento PDF  

● Para enviar la evidencia desarrollada: ubique el enlace para el envío de la evidencia: AA4-		EV01. Taller 5: ciclo FOR. 

## Solución 

_Código fuente:_

~~~
#Taller 5 ciclo FOR
#Elaborado por: Brayan Andres Hernandez Colon
#Fecha Actual: 17/10/2023

#Establecemos la fecha actual

from datetime import date
Hoy = date.today()
print("La fecha actual es: ",Hoy)
print()

#Ejercicio
print("Taller 5: ciclos iterativos con la sentencia FOR")
print()

#Entradas de teclado

num1 = int(input("Ingrese el primer digito: "))
num2 = int(input("Ingrese un digito mayor al anterior: "))
print("Ciclo para el primer digito")

#declaramos ciclo for
for i in range(num1):
    print(i)
print("Se ha finalizado el primer ciclo")
print()
##
print("Ciclo que recorrera desde el primer digito hasta el número mayor")
for i in range(num1,num2, 1):
    print(i)
print("Se ha finalizado el segundo ciclo")
print()

##
Emp = input("Ingrese el nombre de la empresa: ")
Emp = Emp.lower()

for character in Emp:
    print(character)
print("Se ha finalizado el tercer ciclo")
~~~

![image](https://github.com/Brayan-Hc11/Variables_Y_Estructuras_De_Control_En_Python/assets/118775234/407b338c-27b0-48ea-98ff-3da7f3c020f3)

![image](https://github.com/Brayan-Hc11/Variables_Y_Estructuras_De_Control_En_Python/assets/118775234/e5d1d3f3-da6a-407f-a5fb-e348c40952c2)

_Resultado final:_

![image](https://github.com/Brayan-Hc11/Variables_Y_Estructuras_De_Control_En_Python/assets/118775234/777a1118-a37c-43b1-9819-f7602f823b99)



 
