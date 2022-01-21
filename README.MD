# Cabecera 1

Underline 1
-----------


Underline 2
===========

*itálica* o **negrita** o ~~tachado~~

1. lista
1. otra lista

[link](http://www.google.com)



<img src="https://cdn5.dibujos.net/dibujos/pintados/201220/monstruo-malvado-monstruos-pintado-por-naxa-9740435.jpg" width="125" height="125">




# Code Snippets 
``` JAVA
//************************
// Archivo: DateExample.java
//************************
 
import java.text.*;
import java.util.*;
import java.util.Date;
 
public class DateExample {
 
   public static void main(String args[]) {
 
     // Obtener la fecha
     Date now = new Date();
 
     // Obtener los formateadores de fecha de los entornos nacionales
     // predeterminados, alemán y francés
     DateFormat theDate = DateFormat.getDateInstance(DateFormat.LONG);
     DateFormat germanDate = DateFormat.getDateInstance(DateFormat.LONG, Locale.GERMANY);
     DateFormat frenchDate = DateFormat.getDateInstance(DateFormat.LONG, Locale.FRANCE);
 
     // Formatear e imprimir las fechas
     System.out.println("Fecha en el entorno nacional predeterminado: " + theDate.format(now));
     System.out.println("Fecha en el entorno nacional alemán: " + germanDate.format(now));
     System.out.println("Fecha en el entorno nacional francés: " + frenchDate.format(now));
   } 
}
```
|titulo1|titulo2|titulo3|
|---------|---------|---------|
|celda   | celda | celda   |

Cita:

>cita loca

Otra cita:

>fdasf