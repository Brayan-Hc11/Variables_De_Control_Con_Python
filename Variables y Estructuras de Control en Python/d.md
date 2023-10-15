3.2 Actividad de Aprendizaje 2. Codificar instrucciones de entrada y salida de datos siguiendo estándares en Python.  

Elaborado Por: Brayan Andres hernandez Colon. 

Duración: 18 horas  

Fuente de información: https://docs.python.org/3/  

Fuente de información: https://www.w3schools.com/python/python_intro.asp 

 

Una vez revisado el componente formativo dos: Entrada y Salida de Datos con Python, desarrolle las siguientes evidencias de aprendizaje:  

⮚ Foro temático: funciones integradas de Python  

Como primera evidencia a presentar en esta actividad participe en el foro temático denominado “funciones integradas de Python”, dando respuesta al interrogante ¿Cuáles funciones integradas dispone el lenguaje Python para cadenas, números o secuencias? Además de evidenciar manejo del tema debe retroalimentar por lo menos a dos de sus compañeros, demostrando construcción de conocimiento frente a los planteamientos que cada uno proponga. 

 Es importante que, para participar en este foro, leer atentamente el componente formativo 2, en el numeral 3.5 Funciones predefinidas de Python, analice los usos de esas funciones y visite la página https://entrenamiento-python-basico.readthedocs.io/es/latest/ en el enlace 5.6. Funciones integradas. 

Lineamientos para la entrega de la evidencia:  

● Producto a entregar: participación en el foro “Funciones integradas de Python”. 

● Para participar en el foro remítase al área de la actividad correspondiente e ingrese al espacio para acceder AA2-EV01. Foro: funciones integradas de Python. 

 

Solución 

Como primera evidencia a presentar en esta actividad participe en el foro temático denominado “funciones integradas de Python”, dando respuesta al interrogante ¿Cuáles funciones integradas dispone el lenguaje Python para cadenas, números o secuencias? Además de evidenciar manejo del tema debe retroalimentar por lo menos a dos de sus compañeros, demostrando construcción de conocimiento frente a los planteamientos que cada uno proponga. 

Es importante que, para participar en este foro, leer atentamente el componente formativo 2, en el numeral 3.5 Funciones predefinidas de Python, analice los usos de esas funciones y visite la página https://entrenamiento-python-basico.readthedocs.io/es/latest/ en el enlace 5.6. Funciones integradas. 

 

 

 

 

 

¿Cuáles funciones integradas dispone el lenguaje Python para cadenas, números o secuencias?  

Python ofrece una amplia gama de funciones integradas (también conocidas como funciones incorporadas o funciones estándar) que pueden utilizarse para manipular cadenas, números y secuencias. Un ejemplo de ellas es: 

Funciones integradas (Cadenas de caracteres o Stirntgs): 

len(string): Nos permite saber la longitud de la cadena. 

cadena = "Hola, mundo" 

Longitud = len(cadena) 

print("Longitud de la cadena:",longitud) # Salida: Longitud de la cadena: 12 

 

string.upper(): Convierte la cadena a letras mayúsculas. 

cadena = "Hola, mundo" 

mayusculas = cadena.upper() 

print("Cadena en mayúsculas:", mayusculas)  # Salida: Cadena en mayúsculas: HOLA, MUNDO 

 

string.lower(): Convierte la cadena a letras en minúsculas. 

cadena = "Hola, mundo" 

minusculas = cadena.lower() 

print("Cadena en minúsculas:", minusculas)  # Salida: Cadena en minúsculas: hola, mundo 

 

string.strip(): Elimina espacios en blanco que se encuentran en los extremos de la cadena. 

cadena = "   Hola, mundo   " 

sin_espacios = cadena.strip() 

print("Cadena sin espacios en blanco:", sin_espacios)  # Salida: Cadena sin espacios en blanco: Hola, mundo 

 

string.split(sep): Divide la cadena en una lista de substrings(subcadenas) utilizando el separador especificado.(se usa para realizar diccionarios) 

cadena = "Manzana,Plátano,Uva" 

frutas = cadena.split(",") 

print("Lista de frutas:", frutas)  # Salida: Lista de frutas: ['Manzana', 'Plátano', 'Uva'] 

 

string.replace(old, new): Reemplaza todas las ocurrencias de texto de 'old' con 'new'. 

cadena = "Este es un ejemplo" 

nueva_cadena = cadena.replace("ejemplo", "texto") 

print("Nueva cadena:", nueva_cadena)  # Salida: Nueva cadena: Este es un texto 

 

string.find(substring): Encuentra la primera posición de la subcadena(palabra) 'substring' al interior de una cadena. 

cadena = "Python es un lenguaje de programación" 

posicion = cadena.find("lenguaje") 

print("Posición de 'lenguaje':", posicion)  # Salida: Posición de 'lenguaje': 11 

 

string.count(substring): Cuenta cuántas veces aparece 'Una palabra' en la cadena. 

cadena = "Python es un lenguaje de programación, y Python es genial" 

conteo = cadena.count("Python") 

print("Número de veces que 'Python' aparece:", conteo) # Salida: Número de veces que 'Python' aparece: 2 

 

string.startswith(prefix): Comprueba si la cadena comienza con el prefijo especificado. 

cadena = "Python es un lenguaje de programación"(el valor se da en dato booleano) 

comienza_con_python = cadena.startswith("Python") 

print("¿La cadena comienza con 'Python'?", comienza_con_python)  # Salida: ¿La cadena comienza con 'Python'? True(verdadero) 

 

string.endswith(suffix): Comprueba si la cadena termina con el sufijo especificado.(el valor se da en valor booleano) 

cadena = "Python es un lenguaje de programación" 

termina_con_programacion = cadena.endswith("programación") 

print("¿La cadena termina con 'programación'?", termina_con_programacion)  # Salida: ¿La cadena termina con 'programación'? True(Verdadero). 

 

Funciones integradas (Elementos Númericos): 

abs(x): Devuelve el valor absoluto de x. 

numero = -5 

valor_absoluto = abs(numero) 

print("Valor absoluto:", valor_absoluto)  # Salida: Valor absoluto: 5 

 

int(x): Convierte x a un entero.  

numero = 3.5 

entero = int(numero) 

print("Entero:", entero)  # Salida: Entero: 3 

 

float(x): Convierte x a un número de punto flotante.  

numero = 5 

flotante = float(numero) 

print("Flotante:", flotante)  # Salida: Flotante: 5.0 

 

round(x, ndigits): Redondea x a 'ndigits' decimales.  

numero = 3.14159 

redondeado = round(numero, 2) 

print("Redondeado a 2 decimales:", redondeado)  # Salida: Redondeado a 2 decimales: 3.14 

 

max(iterable): Devuelve el valor máximo en el iterable.  

numeros = [10, 5, 8, 20, 3] 

maximo = max(numeros) 

print("Valor máximo:", maximo)  # Salida: Valor máximo: 20 

 

min(iterable): Devuelve el valor mínimo en el iterable.  

numeros = [10, 5, 8, 20, 3] 

minimo = min(numeros) 

print("Valor mínimo:", minimo)  # Salida: Valor mínimo: 3 

 

sum(iterable): Calcula la suma de los elementos en el iterable. 

 

numeros = [1, 2, 3, 4, 5] 

suma = sum(numeros) 

print("Suma de los números:", suma)  # Salida: Suma de los números: 15 

 

Funciones integradas (Elementos: Tuplas y listas): 

len(sequence): Devuelve la longitud de la secuencia.  

secuencia = [1, 2, 3, 4, 5] 

longitud = len(secuencia) 

print("Longitud de la secuencia:", longitud)  # Salida: Longitud de la secuencia: 5 

 

sequence.count(element): Cuenta cuántas veces aparece 'element' en la secuencia.  

secuencia = [1, 2, 2, 3, 4, 2, 5] 

conteo = secuencia.count(2) 

print("Número de veces que '2' aparece:", conteo)  # Salida: Número de veces que '2' aparece: 3 

 

sequence.index(element): Devuelve la primera posición de 'element' en la secuencia.  

secuencia = [10, 20, 30, 40, 50] 

posicion = secuencia.index(30) 

print("Primera posición de '30':", posicion)  # Salida: Primera posición de '30': 2 

 

sorted(sequence): Devuelve una nueva lista ordenada a partir de la secuencia.  

secuencia = [3, 1, 4, 1, 5, 9, 2, 6, 5, 3, 5] 

ordenada = sorted(secuencia) 

print("Secuencia ordenada:", ordenada)  # Salida: Secuencia ordenada: [1, 1, 2, 3, 3, 4, 5, 5, 5, 6, 9] 

 

max(sequence): Devuelve el elemento máximo en la secuencia.  

secuencia = [10, 5, 8, 20, 3] 

maximo = max(secuencia) 

print("Elemento máximo:", maximo)  # Salida: Elemento máximo: 20 

 

min(sequence): Devuelve el elemento mínimo en la secuencia.  

secuencia = [10, 5, 8, 20, 3] 

minimo = min(secuencia) 

print("Elemento mínimo:", minimo)  # Salida: Elemento mínimo: 3 

 

sum(sequence): Calcula la suma de los elementos en la secuencia. 

secuencia = [1, 2, 3, 4, 5] 

suma = sum(secuencia) 

print("Suma de los elementos:", suma)  # Salida: Suma de los elementos: 15 

 

 
