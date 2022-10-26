**DIAGRAMA 1**

**contar del 1 al 10 e imprimir los valores**

**ANALISIS**

**un contador empiece contando en 0 y me muestre todos los numeros contados en pantalla (FOR,DO WHILE,WHILE)**

[![diagrama-1-d.jpg](https://i.postimg.cc/PfyhqvbR/diagrama-1-d.jpg)](https://postimg.cc/mhPKXD5Y)

[![diagrama-1-w.jpg](https://i.postimg.cc/Y0nJzgb2/diagrama-1-w.jpg)](https://postimg.cc/5Qz7xXhD)

[![diagrama-1-for.jpg](https://i.postimg.cc/bJ8cyqZP/diagrama-1-for.jpg)](https://postimg.cc/wtWbF854)


**CODIGO**

//Contar los numeros del 1 al 10 DoWhile

void main() {
  int cont = 1;
  do {
    print(cont);
    cont = cont + 1;
  } while (cont <= 10);
}




//Contar los numeros del 1 al 10 For

void main() {
  for (var i = 1; i <= 10; i++) {
    print(i);
  }
}



//Contar los numeros del 1 al 10 While

void main() {
  int cont = 1;

  while (cont <= 10) {
    print(cont);
    cont = cont + 1;
  }
}




**DIAGRAMA 2**

**Contar del 1 hasta el 10 y sumar los valores. (FOR,WHILE,DO-WHILE)** 

**ANALISIS**

**un contador empiece contando en 0 hasta el 10 y sume los numeros y el resultado lo muestre en pantalla**

[![2-dig-for.jpg](https://i.postimg.cc/MKjSm32h/2-dig-for.jpg)](https://postimg.cc/BXskqgvg)

[![2-dif-while.jpg](https://i.postimg.cc/mrVfg0CF/2-dif-while.jpg)](https://postimg.cc/p9910c02)

[![2-dig-do.jpg](https://i.postimg.cc/KzRGSZwY/2-dig-do.jpg)](https://postimg.cc/tZGQFHX0)


**CODIGO**

//Contar del 1 al 10 y sumar los valores DoWhile

void main() {
  var suma = 0;
  int cont = 1;

  do {
    suma = suma + cont;
    cont = cont + 1;
  } while (cont <= 10);

  print(suma);
}


//Contar del 1 al 10 y sumar los valores FOR

void main() {
  var Suma = 0;
  for (var i = 1; i <= 10; i++) {
    Suma = Suma + i;
  }
  print(Suma);
}

//Contar del 1 al 10 y sumar los valores While

void main() {
  int suma = 0;
  int cont = 1;

  while (cont <= 10) {
    suma = suma + cont;
    cont = cont + 1;
  }

  print(suma);
}




**DIAGRAMA 3**

**Obtenga la suma de los primeros 5 numeros pares. (FOR, WHILE, DO-WHILE)**

**ANALISIS**

**De una cantidad de numeros ingresados hasta que se capturen 5 numeros pares se van a extraer los 5 numeros pares se van a sumar y se mostrara en pantalla**

[![dfd3for.jpg](https://i.postimg.cc/jjy66bZL/dfd3for.jpg)](https://postimg.cc/QBxWsRL3)

[![dfd3dowhile.jpg](https://i.postimg.cc/Bb72ZQQw/dfd3dowhile.jpg)](https://postimg.cc/RJfWXmtc)

[![dfd3while.jpg](https://i.postimg.cc/yNCc8GsB/dfd3while.jpg)](https://postimg.cc/jDvL8ZDk)

**CODIGO**

//calcular la suma de los primeros 5 numeros pares DoWhile

void main() {
  int suma = 0;
  int cont = 1;

  do {
    suma = suma + cont * 2;
    cont = cont + 1;
  } while (cont <= 5);

  print(suma);
}


//Obtenga la suma de los primeros 5 numeros pares For

void main() {
  int suma = 0;

  for (var i = 2; i <= 10; i += 2) {
    suma = suma + i;
  }

  print(suma);
}



//Calcular la suma de los primeros 5 numeros pares While

void main() {
  int suma = 0;
  int cont = 1;

  while (cont <= 5) {
    suma = suma + cont * 2;
    cont = cont + 1;
  }

  print(suma);
}




**DIAGRAMA 4**

**Almacene en un array el numero n leido del teclado, el tamaño del array es de 10.(FOR, WHILE, DO-WHILE)**

**ANALISIS**

**guarda  un numero del teclado, el numero maximo que puedes tener es hasta el 10**

[![dfd4dowhile.jpg](https://i.postimg.cc/85V2wTG3/dfd4dowhile.jpg)](https://postimg.cc/zL02GZVS)

[![dfd4for.jpg](https://i.postimg.cc/DwhFBQc5/dfd4for.jpg)](https://postimg.cc/vc0pmVk6)

[![dfd4while.jpg](https://i.postimg.cc/cJjb50SZ/dfd4while.jpg)](https://postimg.cc/PLWyCGJF)


**CODIGO**

//Almacena en un array el numero N leido del teclado, el tamaño del array es 10 FOR
import 'dart:io';
import 'dart:async';

void main() {
  var cont = 0;
  var array = [];
  int n = int.parse(stdin.readLineSync()!);
  do {
    array.add(n);
    cont = cont + 1;
  } while (cont <= 9);

  print(array);
}


//Almacena en un array el numero N leido del teclado, el tamaño del array es 10 FOR
import 'dart:io';
import 'dart:async';

void main() {
  var array = [];
  int n = int.parse(stdin.readLineSync()!);
  for (var i = 0; i < 10; i++) {
    array.add(n);
  }
  print(array);
}


//Almacena en un array el numero N leido del teclado, el tamaño del array es 10 FOR
import 'dart:io';
import 'dart:async';

void main() {
  var cont = 0;
  var array = [];
  int n = int.parse(stdin.readLineSync()!);
  while (cont <= 9) {
    array.add(n);
    cont = cont + 1;
  }

  print(array);
}



**DIAGRAMA 5**

**ALMACENE LOS N NUMEROS LEIDOS DEL TECLADO EN UN VECTOR DE 10 ELEMENTOS (FOR, WHILE, DO-WHILE)**

**ANALISIS**

**guardara los numeros que le asigne leidos del teclado en un espacio maximo de 10 elememtos** 

[![dfd5dowhile.jpg](https://i.postimg.cc/Bb3NdvwW/dfd5dowhile.jpg)](https://postimg.cc/Kk9nTm2Q)

[![dfd5for.jpg](https://i.postimg.cc/KvZJfRMB/dfd5for.jpg)](https://postimg.cc/kDpQXMwg)

[![dfd5while.jpg](https://i.postimg.cc/7ZR9q9Qn/dfd5while.jpg)](https://postimg.cc/4YzV56GY)

**CODIGO**


//Almacena los N numeros leidos del telcado en un vector de 10 elementos WHILE
import 'dart:io';
import 'dart:async';

void main() {
  var cont = 0;
  var array = [];
  do {
    int n = int.parse(stdin.readLineSync()!);
    array.add(n);
    cont = cont + 1;
  } while (cont <= 9);

  print(array);
}



//Almacena los N numeros leidos del telcado en un vector de 10 elementos FOR
import 'dart:io';
import 'dart:async';

void main() {
  var array = [];

  for (var i = 0; i < 10; i++) {
    int n = int.parse(stdin.readLineSync()!);
    array.add(n);
  }
  print(array);
}


//Almacena los N numeros leidos del telcado en un vector de 10 elementos WHILE
import 'dart:io';
import 'dart:async';

void main() {
  var cont = 0;
  var array = [];

  while (cont <= 9) {
    int n = int.parse(stdin.readLineSync()!);
    array.add(n);
    cont = cont + 1;
  }
  print(array);
}



**DIAGRAMA 6**

**Almacene un contador negativo en un vector, el conteo es de 10 a 0. (FOR, WHILE, DO-WHILE)**

**ANALISIS**

**se pondra un contador que cuente en reversa hasta que llege a 0 que seria el contador negativo**

[![dfd6dowhile.jpg](https://i.postimg.cc/vZ88GL6T/dfd6dowhile.jpg)](https://postimg.cc/hfwRrmsR)

[![dfd6for.jpg](https://i.postimg.cc/HxMd66FZ/dfd6for.jpg)](https://postimg.cc/XGnRJkjd)

[![dfd6while.jpg](https://i.postimg.cc/VNr8N7sf/dfd6while.jpg)](https://postimg.cc/gwW5SH6Q)


**CODIGO**

//Almacene un contador regresivo en un vector, el conteo es de 10 a 0 DoWhile

void main() {
  var array = [];
  var c = 10;
  do {
    array.add(c);
    c--;
  } while (c >= 0);

  print(array);
}


//Almacene un contador regresivo en un vector, el conteo es de 10 a 0 FOR

void main() {
  var array = [];

  for (var i = 10; i >= 0; i--) {
    array.add(i);
  }
  print(array);
}


//Almacene un contador regresivo en un vector, el conteo es de 10 a 0 DoWhile

void main() {
  var array = [];
  var c = 10;

  while (c >= 0) {
    array.add(c);
    c--;
  }

  print(array);
}



**DIAGRAMA 7**

**Almacene en un vector de tamaño 10, todos los numeros pares capturados hasta completar todos.(FOR,WHILE, DO-WHILE)**

**ANALISIS**

**almacenar 10 numeros pares**

[![dfd7dowhile.jpg](https://i.postimg.cc/K8hLfWVV/dfd7dowhile.jpg)](https://postimg.cc/xcgcT69y)

[![dfd7for.jpg](https://i.postimg.cc/x1dRMhz2/dfd7for.jpg)](https://postimg.cc/ZC1phfH7)

[![dfd7while.jpg](https://i.postimg.cc/zBTSq19n/dfd7while.jpg)](https://postimg.cc/S2NzGHQs)


**CODIGO**
//Almacene en un vector de tamaño 10 todos los numeros pares capturados hasta completar todos DoWhile
import 'dart:io';
import 'dart:async';

void main() {
  var array = [];
  var c = 0;
  do {
    int n = int.parse(stdin.readLineSync()!);

    if (n % 2 == 0) {
      array.add(n);
      c = c + 1;
    }
  } while (c <= 9);
  print(array);
}


//Almacene en un vector de tamaño 10 todos los numeros pares capturados hasta completar todos FOR
import 'dart:io';
import 'dart:async';

void main() {
  var array = [];

  for (var i = 0; i <= 10; i++) {
    int n = int.parse(stdin.readLineSync()!);
    if (n % 2 == 0) {
      array.add(n);
      i = i - 1;
    }
  }
  print(array);
}


//Almacene en un vector de tamaño 10 todos los numeros pares capturados hasta completar todos DoWhile
import 'dart:io';
import 'dart:async';

void main() {
  var array = [];
  var c = 0;

  while (c <= 10) {
    int n = int.parse(stdin.readLineSync()!);
    c = c + 1;
    if (n % 2 == 0) {
      array.add(n);
      c = c - 1;
    }
  }
  print(array);
}






**DIAGRAMA 8**

**Obtener el promedio de las calificaciones aprobatorias y la cantidad de alumnos reprobados. La calificación entre 0 y 10 y el maximo de alumnos es de 15. (FOR, WHILE,DO-WHILE)**

**ANALISIS**

**se ingresa las calificaciones de los alumnos y se saca el procedimiento de la cuenta y te dice cual aprobo y cual reprobo**

[![dfd8dowhile.jpg](https://i.postimg.cc/L6J5PV8W/dfd8dowhile.jpg)](https://postimg.cc/zV1qZKWw)

[![dfd8for.jpg](https://i.postimg.cc/GmYp7hYJ/dfd8for.jpg)](https://postimg.cc/NKsYLtd5)

[![dfd8while.jpg](https://i.postimg.cc/SKfx4Tgn/dfd8while.jpg)](https://postimg.cc/XZXbc8SW)


**CODIGO**
/*calcule calificaciones de maximo 15 alumnos, saque promedio de aprobados
cuantos reprobaron y la calificacion mas alta DoWhile*/
import 'dart:io';
import 'dart:async';

void main() {
  double proma = 0;
  var contr = 0;
  double sumaa = 0;
  double conta = 0;
  double cal1 = 0;
  double cal2 = 1;
  var cont = 0;
  do {
    double c = double.parse(stdin.readLineSync()!);
    cont = cont + 1;
    if (c > 10) {
      print('la calificacion no puede ser mayor a 10');
      cont = cont - 1;
    }
    if (c < 0) {
      print('la calificacion no puede ser menor a 0');
      cont = cont - 1;
    }
    if (c < 6 && c > 0) {
      contr = contr + 1;
    }
    if (c <= 10 && c >= 6) {
      cal1 = c;
      sumaa = sumaa + cal1;
      conta++;
    }
    if (cal1 > cal2) {
      cal2 = cal1;
    }
  } while (cont <= 14);

  proma = sumaa / conta;
  print('el promedio de aprobados es $proma');
  print('la calificacion mas alta es $cal2');
  print('la cantidad de reprobados son $contr');
}



/*calcule calificaciones de maximo 15 alumnos, saque promedio de aprobados
cuantos reprobaron y la calificacion mas alta FOR*/
import 'dart:io';
import 'dart:async';

void main() {
  double proma = 0;
  var contr = 0;
  double sumaa = 0;
  double conta = 0;
  double cal1 = 0;
  double cal2 = 1;

  for (var i = 1; i <= 15; i++) {
    double c = double.parse(stdin.readLineSync()!);
    if (c > 10) {
      print('la calificacion no puede ser mayor a 10');
      i = i - 1;
    }
    if (c < 0) {
      print('la calificacion no puede ser menor a 0');
      i = i - 1;
    }
    if (c < 6 && c > 0) {
      contr = contr + 1;
    }
    if (c <= 10 && c >= 6) {
      cal1 = c;
      sumaa = sumaa + cal1;
      conta++;
    }
    if (cal1 > cal2) {
      cal2 = cal1;
    }
  }
  proma = sumaa / conta;
  print('el promedio de aprobados es $proma');
  print('la calificacion mas alta es $cal2');
  print('la cantidad de reprobados son $contr');
}


/*calcule calificaciones de maximo 15 alumnos, saque promedio de aprobados
cuantos reprobaron y la calificacion mas alta While*/
import 'dart:io';
import 'dart:async';

void main() {
  double proma = 0;
  var contr = 0;
  double sumaa = 0;
  double conta = 0;
  double cal1 = 0;
  double cal2 = 1;
  var cont = 0;

  while (cont <= 14) {
    double c = double.parse(stdin.readLineSync()!);
    cont = cont + 1;
    if (c > 10) {
      print('la calificacion no puede ser mayor a 10');
      cont = cont - 1;
    }
    if (c < 0) {
      print('la calificacion no puede ser menor a 0');
      cont = cont - 1;
    }
    if (c < 6 && c > 0) {
      contr = contr + 1;
    }
    if (c <= 10 && c >= 6) {
      cal1 = c;
      sumaa = sumaa + cal1;
      conta++;
    }
    if (cal1 > cal2) {
      cal2 = cal1;
    }
  }

  proma = sumaa / conta;
  print('el promedio de aprobados es $proma');
  print('la calificacion mas alta es $cal2');
  print('la cantidad de reprobados son $contr');
}





**DIAGRAMA 9**

**crea un dfd que capure N numeros en el rango [li,ls] donde  LI=limite inferior y LS=limite superior para li0, obtener:(FOR, WHILE, DO-WHILE)**

**cantidad de numeros pares y su promedio**

**cantidad de nmeros impares y su proedio**

**¿QUE PROMEDIO ES MAYOR?**

**ANALISIS**

**sirve para sacar la cantidad de numeros pares con su promedio al igual con los impares y depende los datos de cada operacion te dira cual promedio es el mayor**

[![dfd9.jpg](https://i.postimg.cc/PxZshPX2/dfd9.jpg)](https://postimg.cc/ygVry6SZ)

[![dfd9dowhile.jpg](https://i.postimg.cc/s2h0Gqk2/dfd9dowhile.jpg)](https://postimg.cc/TyTcZ7Y8)

[![dfd9for.jpg](https://i.postimg.cc/qRcbjnMV/dfd9for.jpg)](https://postimg.cc/G82xp4yq)


**CODIGO**

/*capture N numeros en el rango [Li,Ls] donde:
Li=Limite inferior
Ls=Limite superior para Li<Ls y Li>0
obtenga:
-cantidad de numeros pares y su promedio
-cantidad de numeros impares y su promedio
-que promedio es mayo?*/

import 'dart:io';

void main() {
  double sumap = 0;
  double sumai = 0;
  var contp = 0;
  var conti = 0;
  double promp = 0;
  double promi = 0;
  print('Introduce el limite inferior, mayor a 0');
  var li = int.parse(stdin.readLineSync()!);
  if (li < 0) {
    print('tu limite inferior debe ser mayor a 0');
  }
  if (li > 0) {
    print('Ahora introduce un limite superior');
    var ls = int.parse(stdin.readLineSync()!);
    if (ls < li) {
      print('tu limite superior debe ser mayor a tu limite inferior');
    }
    var cont = li;
    do {
      if (cont <= ls) {
        sumai = sumai + cont;
        conti = conti + 1;
      }
      if (cont % 2 == 0) {
        sumap = sumap + cont;
        contp = contp + 1;
        sumai = sumai - cont;
        conti = conti - 1;
      }
      cont = cont + 1;
    } while (cont <= ls);

    promi = sumai / conti;
    print('los impares son $conti y su promedio es $promi');
    promp = sumap / contp;
    print('los pares son $contp y su promedio es $promp');
    if (promp < promi) {
      print('$promi es mayor');
    }
    if (promp > promi) {
      print('el promedio $promp es mayor');
    }
  }
}



 /*capture N numeros en el rango [Li,Ls] donde:
Li=Limite inferior
Ls=Limite superior para Li<Ls y Li>0
obtenga:
-cantidad de numeros pares y su promedio
-cantidad de numeros impares y su promedio
-que promedio es mayo?*/

import 'dart:io';

void main() {
  double sumap = 0;
  double sumai = 0;
  var contp = 0;
  var conti = 0;
  double promp = 0;
  double promi = 0;
  print('Introduce el limite inferior, mayor a 0');
  var li = int.parse(stdin.readLineSync()!);
  if (li < 0) {
    print('tu limite inferior debe ser mayor a 0');
  }
  if (li > 0) {
    print('Ahora introduce un limite superior');
    var ls = int.parse(stdin.readLineSync()!);
    if (ls < li) {
      print('tu limite superior debe ser mayor a tu limite inferior');
    }

    for (var i = li; i <= ls; i++) {
      sumai = sumai + i;
      conti = conti + 1;

      if (i % 2 == 0) {
        sumap = sumap + i;
        contp = contp + 1;
        sumai = sumai - i;
        conti = conti - 1;
      }
    }

    promi = sumai / conti;
    print('los impares son $conti y su promedio es $promi');
    promp = sumap / contp;
    print('los pares son $contp y su promedio es $promp');
    if (promp < promi) {
      print('$promi es mayor');
    }
    if (promp > promi) {
      print('$promp es mayor');
    }
  }
}

 




**DIAGRAMA 10**

**obten la frecuencia de N calficaciones entre [1,10] indique la cantidad de reprovados y la cantidad de aprobadosy el promedio general (FOR,WHLE,DO-WHILE)**

**ANALISIS**

**sirve para obtener las calificaciones y te indica la cantidad de aprovados y reprovados y el promedio general**

[![dfd10dowhile.jpg](https://i.postimg.cc/yYW4nVtQ/dfd10dowhile.jpg)](https://postimg.cc/dLMxVKqr)

[![dfd10for.jpg](https://i.postimg.cc/T14sBDFk/dfd10for.jpg)](https://postimg.cc/Fk0GL79c)


[![dfd10while.jpg](https://i.postimg.cc/cLQDB2xk/dfd10while.jpg)](https://postimg.cc/MnpbWsj1)
 
 
 **CODIGO**
 
 /*obtener la frecuencia de N calificaciones entre [1,10]
indique cantidad de reprobados, cantidad de aprobados,
promedio de aprobados y promedio general FOR*/
import 'dart:io';

void main() {
  var contr = 0;
  var conta = 0;
  var contt = 0;
  double sumag = 0;
  double sumaa = 0;
  double promg = 0;
  double porma = 0;
  var C0 = 0;
  var C1 = 0;
  var C2 = 0;
  var C3 = 0;
  var C4 = 0;
  var C5 = 0;
  var C6 = 0;
  var C7 = 0;
  var C8 = 0;
  var C9 = 0;
  var C10 = 0;

  print('inserta las 10 calificaciones entera positiva, entre 1 y 10');
  for (var i = 0; i <= 9; i++) {
    int c = int.parse(stdin.readLineSync()!);

    if (c > 11) {
      print('La calificacion debe ser menor a 10');
      i = i--;
    }
    if (c < 0) {
      print('la calificacion debe ser mayor a 0');
      i = i--;
    }
    if (c == 0) {
      C0 = C0 + 1;
    }
    if (c == 1) {
      C1 = C1 + 1;
    }
    if (c == 2) {
      C2 = C2 + 1;
    }
    if (c == 3) {
      C3 = C3 + 1;
    }
    if (c == 4) {
      C4 = C4 + 1;
    }
    if (c == 5) {
      C5 = C5 + 1;
    }
    if (c == 6) {
      C6 = C6 + 1;
    }
    if (c == 7) {
      C7 = C7 + 1;
    }
    if (c == 8) {
      C8 = C8 + 1;
    }
    if (c == 9) {
      C9 = C9 + 1;
    }
    if (c == 10) {
      C10 = C10 + 1;
    }
    if (c < 11 && c >= 0) {
      if (c >= 6) {
        conta = conta + 1;
        sumaa = sumaa + c;
      }
      if (c < 6) {
        contr = contr + 1;
      }
      sumag = sumag + c;
    }
  }
  porma = sumaa / conta;
  contt = conta + contr;
  promg = sumag / contt;

  print('La frecuencia de 0 es $C0');
  print('La frecuencia de 1 es $C1');
  print('La frecuencia de 2 es $C2');
  print('La frecuencia de 3 es $C3');
  print('La frecuencia de 4 es $C4');
  print('La frecuencia de 5 es $C5');
  print('La frecuencia de 6 es $C6');
  print('La frecuencia de 7 es $C7');
  print('La frecuencia de 8 es $C8');
  print('La frecuencia de 9 es $C9');
  print('La frecuencia de 10 es $C10');
  print('Cantidad de reprobados $contr');
  print('cantidad de aprovaodos $conta');
  print('promedio general $promg');
  print('promedio aprobados $porma');
}

 
 



**DIAGRAMA 11**

**diagrama que capture 10 numeros de enteros positivos los ponga en un vector y diga cual es mayo y cual es menor (FOR, HWILE, DO-WHILE)**

**ANALISIS**

**ingresa 10 numeros positivos y te dice cual es mayor y cual es menor**


[![dfd11for.jpg](https://i.postimg.cc/gjgwpYHt/dfd11for.jpg)](https://postimg.cc/jnJqQY9y)
                
  **CODIGO**
                
  /*Diagrama que capture 10 numeros enteros positivos y los ponga en un vector
diga cual es mayor FOR*/

import 'dart:io';

void main() {
  var num = [];
  var mayor = 0;
  var menor = 0;
  for (var i = 0; i <= 9; i++) {
    int n = int.parse(stdin.readLineSync()!);
    if (n > 0) {
      num.add(n);
      if (n < 0) {
        print('el numero debe ser positivo');
        i = i - 1;
      }
    }
  }
  print(num);
  for (var i = 0; i <= 9; i++) {
    if (mayor < num[i]) {
      mayor = num[i];
    }
  }
  print('el numero mayor es $mayor');
  menor = mayor;
  for (var i = 0; i <= 9; i++) {
    if (menor > num[i]) {
      menor = num[i];
    }
  }
  print('el numero menor es $menor');
}
             


**ALMACENA UN ARRAY EL NUMERO N LEIDO DEL TECLADO.EL TAMAÑO DEL ARRAY ES 10 (FOR, WHILE, DO-WHILE)**

**DIAGRAMA 12**

**obtener la distancia mayor de dos numeros concecutivos en una lista de 10 vectores (FOR, WHILE, DO-WHILE)**

**ANALISIS**

**se obtiene la distancia que hay en numeros concecutivos en un rango de 10 numeros**

[![dfd12for.jpg](https://i.postimg.cc/ZqL42wcV/dfd12for.jpg)](https://postimg.cc/3yWsDCzv)

**CODIGO**
 
 //obtener la distancia mayor de 2 numeros consecutivos en una lista de 10 vectores FOR
import 'dart:io';

void main() {
  var num = [];
  var d = [];
  var dis = 0;
  var mayor = 0;

  for (var i = 0; i <= 9; i++) {
    int n = int.parse(stdin.readLineSync()!);
    if (n < 0) {
      print('el numero no debe ser negativo');
      i = i--;
    }
    if (n > 0) {
      num.add(n);
    }
  }
  print('los numeros son $num');
  for (var i = 0; i < 9; i++) {
    dis = num[i] - num[i + 1];
    d.add(i);
    if (dis < 0) {
      d[i] = dis * -1;
    }
    if (dis > 0) {
      d[i] = dis;
    }
  }
  print('las distancias son $d');
  for (var i = 0; i < 9; i++) {
    if (mayor < d[i]) {
      mayor = d[i];
    }
  }
  print('la distacia mayor es $mayor');
}

 
 
 
**DIAGRAMA 13**

**almacene en un vector el resultado de una tabla de multiplicar (10 numeros) (FOR, WHILE, DO-WHILE)**

**ANALISIS**


**se obtiene los resultados de las tablas de multiplicar**

[![dfd13for.jpg](https://i.postimg.cc/P5WjvSBT/dfd13for.jpg)](https://postimg.cc/dhVXzjsx)

 **CODIGO**
 
 
 //Almacene en un vector el resultado de una tabla de multiplicar 10 numeros FOR
import 'dart:io';

void main() {
  var array = [];
  int n = int.parse(stdin.readLineSync()!);
  for (var i = 0; i < 11; i++) {
    array.add(i);
    array[i] = n * i;
  }
  print('$array');
}
 
 
 
 
 

**DIAGRAMA 14**

**escribe un dfd que imprima el siguiente dibujo (FOR, WHILE, DO-WHILE)**

 /*
 /**
 /***
 /****
 /*****
 
**ANALISIS**

**se desarrolla la imagen y se crea el dibujo**



[![dfd14for.jpg](https://i.postimg.cc/mgyrWZZY/dfd14for.jpg)](https://postimg.cc/XrXWwbCq)

  **CODIGO**
                         
   /*escriba el siguiente dibujo
* 
**
***
****
*****
*/
import 'dart:io';

void main() {
  var n = 5;
  for (var i = 0; i < 5; i++) {
    for (var j = 0; j <= i; j++) {
      stdout.write('*');
    }
    print('');
  }
}                      
                         
                         
