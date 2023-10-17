# ⮚ Taller 4: condicionales anidadas. 

Para la segunda evidencia de esta actividad de aprendizaje 3, codifique en lenguaje Python el Taller 4: Condicionales anidadas. Realice lo siguiente:  

A. Digite: “IDLE” en la barra de tareas de su computador, para activar el editor de Python.  

B. Abra un nuevo archivo usando las opciones File - New File o las teclas: CTRL+N  

C. Digite las siguientes sentencias: 

![image](https://github.com/Brayan-Hc11/Variables_Y_Estructuras_De_Control_En_Python/assets/118775234/a718180f-8f20-47a3-af14-9f016a9ce34d)

D. Guarde el programa digitado usando la opción File – Save o las teclas CTRL+S.  

E. Ejecute el programa con la opción: Run – Run Module o la tecla F5  

F. Verifique los resultados. Modifique el código a sus gustos personales y repita los 3 últimos pasos. g. Abra un nuevo documento Word con sus datos personales y el título: AA3-EV2 TALLER 4.  

H. Pegue el código final elaborado con el lenguaje Python.  

I. Capture un pantallazo de los resultados del programa y péguelo en su documento Word. 

J. Almacene el documento de Word con el nombre: AA3-EV2 Taller 4. 

Lineamientos para la entrega de la evidencia:  

● Producto a entregar: Taller 4: condicionales anidadas.  

● Formato: documento PDF  

● Para enviar la evidencia desarrollada: ubique el enlace para el envío de la evidencia: AA3-		EV02. Taller 4: condicionales anidadas. 









***
## solución
_Código fuente:_

~~~
#Taller 4 Condicionales Anidadas
#Elaborado por: Brayan Andres Hernandez Colon
#17/10/2023

#Declaramos la fecha actual
from datetime import date
Hoy = date.today()
print("La fecha actual corresponde a: ",Hoy)
print()

#Ejercicios
print("Ejercicio con las clases de triangulos")
A = int(input("Digite el valor de A: "))
B = int(input("Digite el valor de B: "))
C = int(input("Digite el valor de C: "))

#Declaramos sentencias condicionales
if A==B and A==C and B==C:
    print("El triangulo es equilatero")
else:
    if A==B or B==C or A==C:
        print("El triangulo es isoseles")
    else:
        print("El triangulo es escaleno")
print()
#Ejercicio de condicionales anidadas
Animal = input("Ingrese el nombre de un animal: ")
Animal = Animal.upper()

if Animal=="PERRO":
    print("Este animal es el mejor amigo del hombre: ",Animal)
elif Animal=="GATO":
    print("Este animal persigue a los ratones: ",Animal)
elif Animal=="OSO":
    print("Este animal vive en el polo norte: ",Animal)
else:
    print("El animal no es un PERRO, no es un GATO, ni es OSO.... es: ",Animal)
print()
print("Se ha finalizado el programa")
~~~

![image](https://github.com/Brayan-Hc11/Variables_Y_Estructuras_De_Control_En_Python/assets/118775234/482db98c-29ee-4369-b9ab-0b6e4e025d49)

![image](https://github.com/Brayan-Hc11/Variables_Y_Estructuras_De_Control_En_Python/assets/118775234/8d502489-69de-409c-8bc3-1ea8e341b67c)

_Resultado final:_

![image](https://github.com/Brayan-Hc11/Variables_Y_Estructuras_De_Control_En_Python/assets/118775234/a7c1803a-e645-42b8-9821-cd6d0f648c40)






