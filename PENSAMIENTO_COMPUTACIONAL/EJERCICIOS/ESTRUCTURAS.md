# RETOS
## REALIZAR LOS SIGUIENTES RETOS CON SU ALGORITMO Y DIAGRAMA DE FLUJO CORRESPONDIENTE CADA UNO 

### Programa que pida un número y diga si es positivo o negativo
* 1-Inicio
* 2-Declarar (num)float
* 3-Mostrar("Ingresa un número")
* 4-asignar(num)
* 5-si num>0 entonces
      mostrar("el numero es positivo")
    sino mostrar ("El numero es negativo")
* 6-Fin

![image](https://user-images.githubusercontent.com/104279722/167274574-eb3a6987-ee85-441f-a24e-a18c2d6e79df.png)![image](https://user-images.githubusercontent.com/104279722/167274840-739392fe-c13f-4196-b15f-2c86071a7839.png)




### Programa que solicite se ingrese una letra y sólo permita introducir los caracteres s y n.

* 1-Inicio
* 2-Declarar (letra)char
* 3-mostrar ("Digite una letra")
* 4-asignar (letra)
* 5-si letra=s,n,S OR N entonces
            mostrar ("correcto")
          sino mostrar ("letra no valida")
        finsi
* 6-Fin

![image](https://user-images.githubusercontent.com/104279722/167275724-b30c55d0-991f-4383-8433-b392224156d5.png)
![image](https://user-images.githubusercontent.com/104279722/167275730-302d2640-e958-4834-83f3-14d16f91f981.png)




### Un programa que pida una letra y detecte si es una vocal. 

* 1.-INICIO
* 2.-Declarar (letra)char
* 3.-Mostrar ("Ingresa una letra")
* 4.-Asignar (letra)
* 5.-Si letra==a or letra==e or letra==i or letra==o or letra==u or letra==A or letra==E or letra==I or letra==O or letra==U 
* Entonces 
* Mostrar ("La letra", letra, "es una vocal") 
* sino 
* mostrar ("La letra", letra, "no es vocal")
* finsi
* 6.-FIN
![image](https://user-images.githubusercontent.com/104279722/168409112-fdda90de-a676-42c1-af06-57cd6f10cb67.png)
![image](https://user-images.githubusercontent.com/104279722/168409135-604c23b9-1e0f-4122-887a-d247f5069acd.png)

### Programa que pida 3 números y los muestre en pantalla de menor a mayor.  

* 1.-INICIO
* 2.-Declarar(n1,n2,n3)
* 3.-Mostrar("Ingresar el primer numero")
* 4.-Asignar (n1)
* 5.-Mostrar("Ingresa el segundo numero")
* 6.-Asignar (n2)
* 7.-Mostrar("Ingresa el tercer numero")
* 8.-Asignar (n3)
* 9.-Si n1>n2 entonces
      * Si n2>n3 entonces
      Mostrar("El oreden de menor a mayor es ", n3,",",         n2,",",n1"," )
sino
      Si n1>n3 entonces
            Mostrar ("El oreden de menor a mayor es ",n2,",", n3,",",n1",")
sino
      Mostrar("El oreden de menor a mayor es ",n2,",", n1,",",n3",")
      finsi
finsi
Sino
      Si n1>n3 Entonces
      Mostrar ("El ordes de menor a mayor es ",n3,", ",n1,", ",n2,", ")
SiNo
	Si n2>n3 Entonces
	 Mostrar("El ordes de menor a mayor es ",n1,", ",n3,", ",n2,", ")
SiNo
	 Mostrar("El ordes de menor a mayor es ",n1,", ",n2,", ",n3,",")
			FinSi
		FinSi
	FinSi
* 10.-FIN


![image](https://user-images.githubusercontent.com/104279722/168409417-a8c84085-f54a-4e50-ae91-8b3b74019667.png)
![image](https://user-images.githubusercontent.com/104279722/168409432-4b05e43b-5b00-4657-bb65-ef3d8e1c9ad6.png)


### De un programa que pida un número del 1 al 12 y diga el nombre del mes correspondiente.

* 1.-INICIO
* 2.-Declarar(num)
* 3.-Mostrar("Ingresa un numero")
* 4.-Asignar(num)
* 5.-Si num>0 y num<13 entonces
Si num=1 entonces mostrar("Es Enero ") finsi
Si num=2 entonces mostrar("Es Febrero ") finsi
Si num=3 entonces mostrar("Es Marzo ") finsi
Si num=4 entonces mostrar("Es Abril ") finsi
Si num=5 entonces mostrar("Es Mayo ") finsi
Si num=6 entonces mostrar("Es Junio ") finsi
Si num=7 entonces mostrar("Es Julio ") finsi
Si num=8 entonces mostrar("Es Agosto ") finsi
Si num=9 entonces mostrar("Es Septiembre ") finsi
Si num=10 entonces mostrar("Es Octubre ") finsi
Si num=11 entonces mostrar("Es Noviembre ") finsi
Si num=12 entonces mostrar("Es Diciembre ") finsi
finsi
* 6.-FIN

![image](https://user-images.githubusercontent.com/104279722/168410632-75632e31-ba07-4977-9e44-725efa245dea.png)
![image](https://user-images.githubusercontent.com/104279722/168410644-5a4825f4-bcd6-4174-8ed6-a8b151507840.png)
![image](https://user-images.githubusercontent.com/104279722/168410664-6249715e-b026-45f6-acf5-8490f43edbd8.png)
![image](https://user-images.githubusercontent.com/104279722/168410684-f19f4fe9-acb8-4bd8-bddf-9dc140904609.png)

### De un programa que permita al usuario elegir un candidato por el cual votar. Las posibilidades son: candidato A por el partido rojo, candidato B por el partido verde, candidato C por el partido azul. Según el candidato elegido (A, B ó C) se le debe imprimir el mensaje “Usted ha votado por el partido [color que corresponda al candidato elegido]”. Si el usuario ingresa una opción que no corresponde a ninguno de los candidatos disponibles, indicar “Opción errónea”.

### Para un programa que almacene la cadena de caracteres para una contraseña y email, pregunte al usuario por la contraseña y email e imprima por pantalla si la contraseña y el email introducidos por el usuario coincide con los guardadados en las variables.

* 1.-INICIO
* 2.-Declarar(r_u,r_c,usu,cont)char
* 3.-Mostrar("Registra un usuario")
* 4.-Asignar(r_u)
* 5.-Mostrar("Registra una contraseña")
* 6.-Asignar(r_c)
* 7.-Mostrar("REGISTRO COMPLETO")
* 8.-Mostrar("Ingresar usuario")
* 9.-Asignar(usu)
* 10.-Si usu=r_u entonces
* Mostrar("Usuario correcto")
* Sino 
* Mostrar("Usuario incorrecto")
* finsi
* Mostrar("Ingresa contraseña")
* 11.-Asignar(cont)
* 12.- Si r_c=cont entonces
* Mostrar("Contraseña Correcta")
* sino
* Mostrar("Contraseña incorrecta")
* finsi
* 13.-FIN

![image](https://user-images.githubusercontent.com/104279722/168411179-5c67325d-3c68-45a4-946e-7eb01f3a727a.png)
![image](https://user-images.githubusercontent.com/104279722/168411189-a8232a9a-18e8-4040-99a5-41fa715888e5.png)
