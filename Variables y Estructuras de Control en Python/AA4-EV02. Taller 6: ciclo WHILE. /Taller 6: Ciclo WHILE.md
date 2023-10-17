# ⮚ Taller 6: ciclo WHILE.  

Para la segunda evidencia de esta actividad de aprendizaje 4, codifique en lenguaje Python el Taller 6: ciclo WHILE. Realice lo siguiente: 

A. Digite: “IDLE” en la barra de tareas de su computador, para activar el editor de Python.  

B. Abra un nuevo archivo usando las opciones File - New File o las teclas: CTRL+N  

C. Digite el siguiente código: 

![image](https://github.com/Brayan-Hc11/Variables_Y_Estructuras_De_Control_En_Python/assets/118775234/f49e9f7f-c534-4e17-b948-93e5eaebd035)

D. Guarde el programa digitado usando la opción File – Save o las teclas CTRL+S.  

E. Ejecute el programa con la opción: Run – Run Module o la tecla F5  

F. Verifique los resultados. Modifique el código a sus gustos personales y repita los 3 últimos pasos.  

G. Abra un nuevo documento Word con sus datos personales y el título: AA4-EV2 TALLER 6.  

H. Pegue el código final elaborado con el lenguaje Python.  

I. Capture un pantallazo de los resultados del programa y péguelo en su documento Word.  

J. Almacene el documento de Word con el nombre: AA4-EV2 Taller 6. 

Lineamientos para la entrega de la evidencia:  

● Producto a entregar: Taller 6: ciclo WHILE.  

● Formato: documento PDF 	 

● Para enviar la evidencia desarrollada: ubique el enlace para el envío de la evidencia: AA4-EV02. 		Taller 6: ciclo WHILE. 

## Solución

_Código fuente_

~~~
#Taller 6: ciclo WHILE
#Elaborado por: Brayan Andres Hernandez Colon
#Fecha actual: 17/10/2023

#declaramos la fecha actual
from datetime import date
Hoy = date.today()
print("La fecha actual es: ",Hoy)
print()

#Ejercicio
print("Taller 6 ciclos iterativos con la sentencia WHILE")
print()

num1 = int(input("Ingrese el primer digito: "))
print("*** Ciclo controlado por contador ***")
i = 1
while i <= num1:
    print(i)
    i += 1
print("Se ha finalizado el primer ciclo")
print()
print("*** Ciclo controlador por evento ***")
i = 1
Num1 = 5
Num2 = int(input("Ingrese un número de 1 a 10: "))

while Num2 != Num1:
    i += 1
    Num2 = int(input("Ingrese un número de 1 a 10"))
print("Acertaste en el intento N°.",i)
print("Se ha finalizado el ciclo")
print()
print("*** Ciclo abordado con la sentencia break")
Amis = input("Ingrese el nombre de un amigo: ")
for character in Amis:
    print(character)
    if character=='A':
        break
print("Se ha finalizado el ciclo")
print()
print("Fin de la ejecución del programa")
~~~

![image](https://github.com/Brayan-Hc11/Variables_Y_Estructuras_De_Control_En_Python/assets/118775234/d69641e9-e514-4923-b48b-cd82642597c8)

![image](https://github.com/Brayan-Hc11/Variables_Y_Estructuras_De_Control_En_Python/assets/118775234/f8dd405f-9af8-4b68-b353-32410f4f49b7)

_Resultado final:_

![image](https://github.com/Brayan-Hc11/Variables_Y_Estructuras_De_Control_En_Python/assets/118775234/c65206e6-7b88-450a-b0d1-4b37b86c02b1)
