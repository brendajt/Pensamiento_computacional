## Clase 16/02/23
### ALGORITMO: serie de instrucciones
1,2,3 es la entrada de Datos
4 es el proceso
5,6 Salida de datos
1. Inicio
2. Declarar
3. Asignar
4. Operación
5. Mostrar 
6. Fin 

### Cuantitativo : Calcular la edad con base a la fecha de nacimiento
1. Inicio
2. Declarar ("año_nac", "año_act", "edad")
3. Asignar ("año_act"=2023)
4. Mostrar ("ingresa tu año de nacimiento")
5. Asignar (año_nac)
6. Edad= (año_act - año_nac)
7. Mostrar (edad)
8. FIN

### Cualitativo, levantarme a una hora determinada
1. Inicio
2. Declarar ("Configurar_alarma","sonar_alarma "abrir_ojos", "pararme")
3. Mostrar ("Ingresa la hora de tu alarma"
4. Asignar "Configurar_alarma" 
5. Mostrar("sonar_alarma")
6. escucha alarma = abrir ojos
7. abrir_ojos= pararme
8. Mostrar "pararme"
9. FIN 

### Cuantitativo: Algoritmo que calcula el área de un triangulo 
1. Inicio
2. Declarar ("área", "base", "altura")
3. Mostrar ("ingresa la base")
4. Asignar (base)
5. Mostrar ("ingresa la altura"
6. Asignar (altura)
7. área= (base*altura)/2
8. Mostrar (área)
9. Fin 

TAREA: Algoritmo cuantitativo para obtener cuanto tiempo tardariamos en leer los nombres de todos los habitantes del mundo, considerando que nos tardamos 1 segundo en leer cada nombre

## Tipo de Datos 
### Numericos 
Enteros = int 
reales o flotantes =float, números decimales. 

2. DECLARA edad(int)
           precio(float)
### Caracteres           
Caracter = char ej. "a" , " ", "@" un solo caracter

String = str ej. "hola" más de dos caracter
Los caracteres y los strings van entre comillas siempre.

"55"x5 = 5555555555 por que el 55 entre comillas es un caracter 
### Boleeanos 
Boleanos = true or false 
bol 


## Clase 17/02/23

1. Inicio
2. Declarar (variables) son los datos -Numericos, -Alfanumericos y -Boleanos
Las variables pueden cambiar, ingredientes para los programas 
Tipos de variables:
-Numerica
-Alfanumericas- Lo que este entre comillas, puede ser npuneros o texto pero siempre entre comillas
-Lógicas es decir Boleanas verdadera o falsa. 
Variable de trabajo cuando tiene una operación. 
Variables acumuladoras que adentro tienen otras variables que moveran su valor. 
Variables contador son las que permiten controlar ciclos. Normalmente se representa con las letras "i, j y k" 


## Sintaxis 
No puede iniciar con un número la variable
No puede llevar guiones medios
No puedes dejar espacios
Poner nombre de la varible, signo igual y contenido de la variable 

## Convenciones
snakecase: nombre_alumno
18 caracteres
Contenido: dar nombres en referencia a lo que contiene 
no empezar con mayuscula mi variable ni con caracteres especiales como @,#, etc

# Operadores 
## Aritmeticas
-Suma 
-Resta
-Multiplicación
-División
Dan prioridad de la siguiente forma
()
^ o **  -Pontencia
-Divisiones y multiplicaciones 
-Residuo (%) o división de piso (//) ej. 20/3= 6 y 20%3=2 ya que es lo que sobra
-Sumas y Restas

## Relacionales
< Menor que 
> Mayor que 
== igual que 
!= diferente  o <>
>=
<=
Obtendremos como resultado un boleano. 

## Lógicos
and &&
or  ||
not  ¬ 


## PSINT 
### Para saludar
1. Inicio
2. Declarar (nombre(str))
3. Mostrar ("Escribe tu nombre)
4. Asignar (nombre)
5. Mostrar ("hola",nombre) el texto vaentre comillas, la variable no,para unir una variable y un texto ponemos una coma.

## Clase 21/02/23
1. INICIO
2. Declarar :

           habitantes int
           tiempo total int
           seg_dia int
           seg_mes int
           seg_anio int
           dia int
           mes int
           anio int 

3. Asignar 
 seg_dia = 60 * 60 * 40   --- Variables de trabajo 
4. Asignar 
 seg_mes = seg_dia * 30  --- variable acumulador 
5. Asignar 
 seg_anio = seg_mes * 12 
6. Mostrar "Ingresa el número de habitantes"
7. Asignar  habitantes 
8. tiempo_total = habitantes * 1
9. anio= tiempo_total // seg_anio   --- division de piso para solo tener la parte entera 
10. tiempo_total % seg_anio  --- residuo de piso, muestra lo que sobra en una división
11. mes = tiempo_total // seg_mes
12. tiempo_total % seg_mes
13. dia = tiempo_total // seg_dia
14. Mostrar "Tardaras" anio, "años y ", mes , "meses con ", dias "días"
15. FIN

### Clase 22/02/23

Tipo de Datos:
1. Númericos
           - int --> enteros
           - float --> flotantes o reales 
2. Boleanos 
           - Falso
           - verdadero
3. Tipo de Caracter 
           - char --> caracter
           - string --> cadena

Operadores:
1. Lógigos 
           - and
           - or
2. Aritmeticos (mayor a menor jerarquia
           - () parentesís
           - ^ potensía 
           - * / multiplicación y división 
           - // % división y residuo de piso
           - + - suma y resta  
3. Relacionales 
           - < menor que
           - > mayor que
           - == igual que 
           - <! <> distinto que
           - <= menor o igual que
           - >= mayor o igual que          
           
           
           
### Clase 23/02/23

Condicionales 
- Simple: 
Si --> entonces 
if
*Si se pasa algo, entonces haces algo

-Compuesta 
Si --> entonces
en caso contrario 
if 
else
Si pasa algo entonces haces algo 
Pero si no pasa haces otra cosa

-Añadida 
Si --> entonces
Si --> entonces 
de lo contrario 
if else
elif

Ejemplos:
-Simple:
letra = " "
"Ingresa letra"
Si letra == "a"
entonces "a es vocal y es a"

TERMINA

-Compuesta 
Si vocal == "a"
"Es vocal y es a"
SI No
"no es la a"

-Añadida
Si vocal == "a"
Entonces "Es vocal y es a"
Si no 
Si vocal == "e"
"Es vocal y es e"
Si no .....
























