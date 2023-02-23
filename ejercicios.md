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


Realiza el ejercicio de un programa que calcula el promedio, y el estatus (aprobado o reprobado) de un alumno de alguno de los siguientes tres grupos:
Grupo 1:
- Español 
- Matematicas 
- Ciencias
Grupo 2:
- Español
- Matemtaticas
- Ciencias
- Ingles
Grupo 3:
- Español
- Matemataticas
- Ciencias
- Ingles
- Musica














