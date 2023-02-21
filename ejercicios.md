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

    
