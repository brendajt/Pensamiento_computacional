   ## PSeInt
   
   Mostrar es Escribir
   
   Asignar es leer
   
   Trunc es la división de piso e PSeInt
   
   Codigo para calcular promedio 
   
     Algoritmo Promedio_1
        nombre<-" "
        cal_1<-0
        cal_2<-0
        cal_3<-0
        cal_4<-0
        promedio<-0
        Escribir "Ingresa tu nombre"
        Leer nombre
        Escribir "Ingresa calificacion 1"
        Leer cal_1
        Escribir "Ingresa calificación 2"
        Leer cal_2
        Escribir "Ingresa calificación 3"
        Leer cal_3
        Escribir "Ingresa calificación 4"
        Leer cal_4
        promedio = (cal_1+cal_2+cal_3+cal_4)/4
        Escribir "El alumno ", nombre, " obtuvo un promedio de ", promedio
      FinAlgoritmo

Codigo para Saludar 

    Algoritmo  parasaludar
      nombre<-" "
      Escribir "Ingresa tu nombre"
      Leer nombre
      Escribir "hola ",nombre
    FinAlgoritmo
    
    
Codigo para leer los nombres de habitantes

      Algoritmo lectura_habitantes
         habitantes<-0
         seg_dia<-60*60*24
         seg_mes<-seg_dia*30
         seg_anio<-seg_dia*365
         anio<-0
         mes<-0
         dia<-0
         Escribir "Ingresa número de habitantes"
         Leer habitantes
         tiempo_total = (habitantes * 1)
         anio = TRUNC(tiempo_total/seg_anio)
         tiempo_total= tiempo_total MOD seg_anio
         mes = TRUNC(tiempo_total/seg_mes)
         tiempo_total = tiempo_total MOD seg_mes
         dia = TRUNC(tiempo_total/seg_dia)
          Escribir "Tardaras ", anio, " años ", mes, " meses y ", dia, " días en leer los nombres de ", habitantes, " habitantes"
      FinAlgoritmo

Código para sumar dos números 

      Algoritmo Suma
         // Entrada
         Definir num1 Como Entero
         Definir num2 Como Entero
         Definir Res Como Entero
         Escribir "Ingresa el primer número"
         Leer num1
         Escribir "Ingresa el segundo número"
         Leer num2
         // Proceso 
         Res<- num1 + num2
         // Salida
         Escribir "La suma de ", num1, " más ", num2, " es ", Res
      FinAlgoritmo
   
   
 Código de un prestamo con interes simple 
 
       Algoritmo Prestamos
         // Programa que calcula el total a pagar y 
         //la mensualidad de un prestamo con una tasa de interes del 8%
         // Entrada de Datos 
         // Ingredientes que necesitamos 
         Definir prestamo Como Real // El dinero que se nos presta
         Definir mensualidad Como Entero // A los meses que se quiere sacar
         Definir total Como Real // El total del prestamo más interes
         Definir interes Como Real // Interes que se cobra
         Definir pago_men Como Real // Los pagos mensuales que me quedara
         // Asignación de valores 
         Escribir "Cual es el prestamo"
         Leer prestamo // Introducir la cantidad que nos prestaran
         Escribir "A cuantas mensualidades se pagara el prestamo"
         Leer mensualidad // Introducir las mensualidades que queremos
         interes<-.08
         total<-(prestamo * interes) + prestamo
         pago_men<-total/mensualidad
         // Salida de Datos
         Escribir "El pago total por un prestamo de ", prestamo, " es de " total, " a ", mensualidad, " mensualidades de ", pago_men
      FinAlgoritmo

 
### Diagrama de flujo de mi código
![image](https://user-images.githubusercontent.com/125502269/220736543-bd768b69-ff97-4cd7-9ab8-168d29175ec8.png)

Código de un prestamo con interes compuesto 

      Algoritmo Interes_compuesto
         Definir prestamo Como Real
         Definir mensualidad Como Entero
         Definir total Como Real
         Definir interes Como Real
         Definir pago_men Como Real
         Escribir "Cual es el prestamo"
         Leer prestamo
         Escribir "A cuantos meses"
         Leer mensualidad
         interes<-0.08
         total<-prestamo * (1+interes) ^ mensualidad
         pago_men<-total/mensualidad
         Escribir 'El pago total por un prestamo de ',prestamo,' es de ',total,' a ',mensualidad,' mensualidades de ',pago_men

      FinAlgoritmo
### Diagrama de Flujo de mi código
![image](https://user-images.githubusercontent.com/125502269/221010158-a1a1eef8-5540-49c9-8265-dff2de753234.png)

Código con conectores Simples y Compuestos

      Algoritmo Cali_simple
         Definir nombre Como Caracter
         Definir espanol Como Real
         Definir mate Como Real
         Definir ciencias Como Real
         Definir promedio Como Real
         Escribir "Cual es el nombre del alumno"
         Leer nombre
         Escribir "Calificación de Español"
         Leer espanol
         //Validar si la calificación es permitida o no.
         // Solo se puede calificaciones de 0-10
         Si espanol > 10 Entonces
            Escribir 	"Calificación invalida"
          Fin Si
         Escribir "Calificación de Matematicas"
         Leer mate
         Si mate > 10 Entonces
            Escribir 	"Calificación invalida"
          Fin Si
         Escribir "Calificación de Ciencias"
         Leer ciencias
         Si ciencias > 10 Entonces
            Escribir 	"Calificación invalida"
          Fin Si
         promedio<-(espanol+mate+ciencias)/3
         Si promedio >= 6 Entonces
            Escribir "El alumno ", nombre, " obtuvo un promedio de :", promedio, " entonces aprobo"
         SiNo
            Escribir "El alumno ", nombre, " obtuvo un promedio de :", promedio, " entonces reprobo"
         Fin Si

      FinAlgoritmo

Realiza el ejercicio de un programa que calcula el promedio, y el estatus (aprobado o reprobado) de un alumno de alguno de los siguientes tres grupos:
Grupo 1:
- Español 
- Matematicas 
- Ciencias
Grupo 2:
- Español
- Matematicas
- Ciencias
- Ingles
Grupo 3:
- Español
- Matemataticas
- Ciencias
- Ingles
- Musica

Codigo para ejercicio "FALTA PROBAR" 

      Algoritmo sin_titulo
         Definir nombre Como Caracter
         Definir espanol Como Real
         Definir mate Como Real
         Definir ciencias Como Real
         Definir ingles Como Real
         Definir musica Como Real
         Definir promedio Como Real
         Definir grupo Como Real
         Escribir "Cual es el nombre del alumno"
         Leer nombre
         Escribir "¿A que grupo pertenece?"
         Leer grupo
         Si grupo = 1 Entonces
            Escribir "Ingresa calificación español"
            Leer espanol
            Si espanol>0 Y espanol <= 10 Entonces
               Escribir  "Ingresa calificación matematicas"
               Leer mate
               Si mate > 0 Y mate <= 10 Entonces
                  Escribir "Ingresa calificación ciencias"
                  Leer ciencias
                  Si ciencias > 0 Y ciencias <= 10 Entonces
                     promedio=(espanol+mate+ciencias)/3
                     Leer promedio
                     Si promedio >= 6 Entonces
                        Escribir "El alumno ", nombre, " del grupo " , grupo, " obtuvo un promedio de :", promedio, " entonces aprobo"
                     SiNo
                        Escribir "El alumno ", nombre, " del grupo " , grupo, " obtuvo un promedio de :", promedio, " entonces reprobo"
                     Fin Si
                  SiNo
                     Escribir "Datos no validos"
                  Fin Si
               SiNo
                  Escribir "Datos no validos"
               Fin Si
            SiNo
               Escribir "Datos no validos"
            Fin Si
         SiNo
            Escribir "Datos no validos"
         Fin Si

         Si grupo = 2 Entonces
            Escribir "Ingresa calificación español"
            Leer espanol
            Si espanol > 0 Y espanol <= 10 Entonces
               Escribir  "Ingresa calificación matematicas"
               Leer mate
               Si mate > 0 Y mate <= 10 Entonces
                  Escribir "Ingresa calificación ciencias"
                  Leer ciencias
                  Si ciencias > 0 Y ciencias <= 10 Entonces
                     Escribir "Ingresa calificación ingles"
                     Leer ingles
                     Si ingles > 0 Y ingles >= 10 Entonces
                        promedio = (espanol+mate+ciencias+ingles)/4
                        Leer promedio
                        Si promedio >= 6 Entonces
                           Escribir "El alumno ", nombre, " del grupo " , grupo, " obtuvo un promedio de :", promedio, " entonces aprobo"
                        SiNo
                           Escribir "El alumno ", nombre, " del grupo " , grupo, " obtuvo un promedio de :", promedio, " entonces reprobo"
                        Fin Si
                     SiNo
                        acciones_por_falso
                     Fin Si

                  SiNo
                     Escribir "Datos no validos"
                  Fin Si
               SiNo
                  Escribir "Datos no validos"
               Fin Si
            SiNo
               Escribir "Datos no validos"
            Fin Si
         SiNo
            Escribir "Datos no validos"
         Fin Si
      FinAlgoritmo



Código PROBADO

         Algoritmo Cali_simple
            Definir nombre Como Caracter
            Definir espanol Como Real
            Definir mate Como Real
            Definir ciencias Como Real
            Definir ingles Como Real
            Definir musica Como Real
            Definir promedio Como Real
            Definir grupo Como Real
            Escribir "Cual es el nombre del alumno"
            Leer nombre
            Escribir "¿A que grupo pertenece?"
            Leer grupo
            Si grupo = 1 Entonces
               Escribir "Calificación de Español"
               Leer espanol
               //Validar si la calificación es permitida o no.
               // Solo se puede calificaciones de 0-10
               Si espanol > 10 Entonces
                  Escribir 	"Calificación invalida"
               Fin Si
               Escribir "Calificación de Matematicas"
               Leer mate
               Si mate > 10 Entonces
                  Escribir 	"Calificación invalida"
               Fin Si
               Escribir "Calificación de Ciencias"
               Leer ciencias
               Si ciencias > 10 Entonces
                  Escribir 	"Calificación invalida"
               Fin Si
            Fin Si
               promedio<-(espanol+mate+ciencias)/3
            Si grupo = 2 Entonces
               Escribir "Calificación de Español"
               Leer espanol
               //Validar si la calificación es permitida o no.
               // Solo se puede calificaciones de 0-10
               Si espanol > 10 Entonces
                  Escribir 	"Calificación invalida"
               Fin Si
               Escribir "Calificación de Matematicas"
               Leer mate
               Si mate > 10 Entonces
                  Escribir 	"Calificación invalida"
               Fin Si
               Escribir "Calificación de Ciencias"
               Leer ciencias
               Si ciencias > 10 Entonces
                  Escribir 	"Calificación invalida"
               Fin Si
               Escribir "Calificación de Ingles"
               Leer ingles
               Si ingles > 10 Entonces
                  Escribir 	"Calificación invalida"
               Fin Si
               promedio<-(espanol+mate+ciencias+ingles)/4
            Fin Si
            Si grupo = 3 Entonces
               Escribir "Calificación de Español"
               Leer espanol
               //Validar si la calificación es permitida o no.
               // Solo se puede calificaciones de 0-10
               Si espanol > 10 Entonces
                  Escribir 	"Calificación invalida"
               Fin Si
               Escribir "Calificación de Matematicas"
               Leer mate
               Si mate > 10 Entonces
                  Escribir 	"Calificación invalida"
               Fin Si
               Escribir "Calificación de Ciencias"
               Leer ciencias
               Si ciencias > 10 Entonces
                  Escribir 	"Calificación invalida"
               Fin Si
               Escribir "Calificación de Ingles"
               Leer ingles
               Si ingles > 10 Entonces
                  Escribir 	"Calificación invalida"
               Fin Si
               Escribir "Calificación de Musica"
               Leer musica
               Si musica > 10 Entonces
                  Escribir 	"Calificación invalida"
               Fin Si
               promedio<-(espanol+mate+ciencias+ingles+musica)/5
            SiNo
               Escribir "El grupo no es valido"
            FinSi
            Si promedio >= 6 Entonces
               Escribir "El alumno ", nombre, " del grupo " , grupo, " obtuvo un promedio de :", promedio, " entonces aprobo"
            SiNo
               Escribir "El alumno ", nombre, " del grupo " , grupo, " obtuvo un promedio de :", promedio, " entonces reprobo"
            Fin Si

         FinAlgoritmo

Diagrama de Flujo de mi Calculadora
![image](https://user-images.githubusercontent.com/125502269/221944463-0b546734-392f-4b3e-948f-d346e5b704cb.png)

Código de una calculadora 

      Algoritmo calculadora
         Definir num1 Como Real
         Definir num2 Como Real
         Definir res Como Real
         Definir operador Como Caracter
         Escribir "Ingresa el primer número"
         Leer num1
         Escribir "Ingresar el segundo número"
         Leer num2
         Escribir "¿Que operación se desea realizar +, -, *, /"
         Leer operador
         Segun operador Hacer
            "+":
               res = (num1+num2)
            "-":
               res = (num1-num2)
            "*":
               res = (num1*num2)
            "/":
               Si num2 = 0 Entonces
                  Escribir "No puedes dividir entre cero"
               SiNo
                  res = num1 / num2
               Fin Si


            De Otro Modo:
               Escribir "Operación no valida"
         Fin Segun
         Escribir res
      FinAlgoritmo

Diagrama PSeInt
![image](https://user-images.githubusercontent.com/125502269/221944628-0a2d1c48-42d7-41a4-acbf-627d3eebce2d.png)


Código Calculadora 2.0

      Algoritmo Cal
         Definir num1 Como Real
         Definir num2 Como Real
         Definir res Como Real
         Definir op Como Caracter
         Leer num1
         Leer op
         Leer num2
         Segun op Hacer
            "+":
               res = (num1+num2)
            "-":
               res = (num1-num2)
            "*":
               res = (num1*num2)
            "/":
               Si num2 = 0 Entonces
                  Escribir "No puedes dividir entre cero"
               SiNo
                  res = num1 / num2
               Fin Si
            "^":
               res = num1^num2
            "%":
               Si num2 = 0 Entonces
                  Escribir "No puedes dividir entre cero"
               SiNo
                  res = num1 % num2
               Fin Si		
            "//":
               Si num2 = 0 Entonces
                  Escribir "No puedes dividir entre cero"
               SiNo
                  res = num1 MOD num2
               Fin Si		

            De Otro Modo:
               Escribir "Operación no valida"
         Fin Segun
         Escribir res
      FinAlgoritmo


Código usando for para imprimir los números pares hasta el 10

      Algoritmo Pares
         Para i<-0 Hasta 100 Con Paso 2 Hacer
            Escribir i
         Fin Para
      FinAlgoritmo


Código para ver las tablas de multiplicar 

      Algoritmo tablas
         Definir num Como Entero
         Definir res Como Entero
         Escribir "Dime de que número"
         Leer num
         Para i<-1 Hasta 10 Con Paso 1 Hacer
            res = i * num
            Escribir num," x ",i," = ",res
         Fin Para
      FinAlgoritmo


Código para imprimir tu nombre n veces 

      Algoritmo nombre_n_veces
         Definir nombre Como Caracter
         Definir veces Como Entero
         Escribir "Ingresa tu nombre"
         Leer nombre
         Escribir "Cuantas veces quieres que imprima"
         Leer veces
         Para i<-1 Hasta veces Con Paso 1 Hacer
            Escribir i, nombre
         Fin Para
      FinAlgoritmo

Código para promediar n materias de un alumno 

      Algoritmo prom_1_alumno
         Definir nombre Como Caracter
         Definir calf Como Real
         Definir prom Como Real
         Definir veces Como Entero
         Definir suma Como Real
         Escribir "Ingresa nombre del alumno"
         Leer nombre
         Escribir "¿Cuántas calificaciones tiene ", nombre
         Leer veces
         Para i<-1 Hasta veces Con Paso 1 Hacer
            Escribir "Ingresa calificación ", i
            Leer calf
            suma = suma + calf
            prom = suma / veces
         Fin Para
         Escribir "El promedio del alumno ", nombre  " es: ", prom
      FinAlgoritmo

Código para promediar n materias de n alumnos (Problema encontrado: Para el alumno 2 se guardaba el promedio del alumno 1. Solución: Reinicializar todos los datos para "limpiar" mis variables como suma, calificacion y promedio y con un nuevo alumno o dato se vuelva a limpiar. Bastaba con reiniciar suma ya que es la variable donde se estaban guardando las calificaciones.) 

      Algoritmo prom_n_alumnos
         Definir nombre Como Caracter
         Definir calf Como Real
         Definir prom Como Real
         Definir veces Como Entero
         Definir suma Como Real
         Definir alumnos Como Entero
         Escribir "¿Cuántos alumnos deseas capturar"
         Leer alumnos
         Para j<-1 Hasta alumnos Con Paso 1 Hacer
            Escribir "Ingresa nombre del alumno ",j
            Leer nombre
            Escribir "¿Cuántas calificaciones tiene ", nombre
            Leer veces
            Para i<-1 Hasta veces Con Paso 1 Hacer
               Escribir "Ingresa calificación ", i
               Leer calf
               suma = suma + calf
               prom = suma / veces
            Fin Para
            Escribir "El promedio del alumno ", nombre  " es: ", prom 
            suma<-0
            
         Fin Para

      FinAlgoritmo
      









