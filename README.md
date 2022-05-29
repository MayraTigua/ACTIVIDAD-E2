# PROGRAMAS EN C++ DE TIGUA MAYRA

# # # Informacion de autor # # # 

Autor: Tigua Rodriguez Mayra Alexandra

Correo electronico: mayra.tigua.rodriguez@utelvt.edu.ec

Celular: 0997038653

Link de video: https://youtu.be/-YX8sqxA2Uw

# Nombre de cada Programas

TiguaMayra-Compara.cpp

TiguaMayra-CuentaMoneda.cpp

TiguaMayra-Edad.cpp

TiguaMayra-PuntoVenta.cpp

TiguaMayra-SumaVNum.cpp

# Descripcion de cada Programas

> TiguaMayra-Compara.cpp : 

	Es un programa que nos permite comparar dos números y verificar cual de estos es el mayor o menor.

> TiguaMayra-CuentaMoneda.cpp : 

	Es un programa que permite al usuario contar monedas de tres denominaciones, saber cuanto es la cantidad de dinero que tiene y cuantas monedas tiene de cada denominación.

> TiguaMayra-Edad.cpp : 

	Es un programa que permite al usuario calcular su edad en Años Meses y Dias.

> TiguaMayra-PuntoVenta.cpp :  

	Es un programa que se encargara de calcular la compra de varios productos, calculando su valor bruto, sumandole el Iva a la compra y realizando un descuento adicional a la compra del usuario.

> TiguaMayra-SumaVNum.cpp : 

	Es un programa encargado para que cualquier usuario en general pueda calcular los valores de varios números.

# Funcionalidad

>>>> TiguaMayra-Compara.cpp :

	  float MR_m,MR_a;
	  cout<<"Ingrese el valor de M: ";
	  cin>>MR_m;
	  cout<<"Ingrese el valor de A: ";
	  cin>>MR_a;
  
 >>>> TiguaMayra-CuentaMoneda.cpp : 
  
    int MR_n, MR_c=0, MR_c1=0, MR_c2=0;
    float MR_x, MR_a=0, MR_a1=0, MR_a2=0, MR_m=0.10;
    cout<<"Cantidad de monedas a ingresar : ";
    cin>>MR_n;
    do{
	  cout<<"ingrese el valor de la moneda (0.10, 0.25) : ";
    cin>>MR_x;
        
>>>> TiguaMayra-Edad.cpp : 
    
    	int MR_dd,MR_mm,MR_yy,MR_dd1,MR_mm1,MR_yy1,MR_da,MR_ma,MR_ya;
	cout<<"Ingresa la Fecha Actual: Dia Mes y Año "<<endl;
	cin>>MR_dd>>MR_mm>>MR_yy;
	cout<<"Ingresa la Fecha de Nacimiento: Dia Mes y Año "<<endl;
	cin>>MR_dd1>>MR_mm1>>MR_yy1;    
   
>>>> TiguaMayra-PuntoVenta.cpp : 
     
     int MR_b=0,MR_q;
     float MR_e=0,MR_m,MR_vt,MR_tiva,MR_tdes,MR_iva=0.12,MR_dsc=0.10,MR_pt;
     cout<<"Ingresar la cantidad de productos a comprar: ";
     cin>>MR_q;
     do{
     cout<<"Ingresar el valor del producto: ";
     cin>>MR_m;
   
>>>> TiguaMayra-SumaVNum.cpp : 
    
    	int MR_a=0,MR_m;
	  float MR_t=0,MR_r;
	  cout<<"Ingresar la cantidad de numeros a sumar: ";
	  cin>>MR_m;
	  do{
	  cout<<"Ingresar un numero: ";
	  cin>>MR_r;   
        
 # Salida de los programas
   
>>>> TiguaMayra-Compara.cpp :

	cout<<"El valor de M: "<<MR_m<<" es mayor a A: "<<MR_a<<endl;

	cout<<"El valor de A: "<<MR_a<<" es mayor a M: "<<MR_m<<endl;
  
>>>> TiguaMayra-CuentaMoneda.cpp : 

  	cout<<"El resultado fue:"<<endl;
  
  	cout<<"Cantidad de monedas ingresadas : "<<MR_c<<endl;
  
  	cout<<"Cantidad total en dinero contado : "<<MR_a<<endl;
  
 	cout<<"Cantidad de monedas de 0.10c ingresadas : "<<MR_c1<<endl;
  
  	cout<<"Cantidad total en dinero de monedas de 0.10cc : "<<MR_a1<<endl;
 
 	cout<<"Cantidad de monedas de 0.25cc ingresadas : "<<MR_c2<<endl;
 
  	cout<<"Cantidad total en dinero de monedas de 0.25cc : "<<MR_a2<<endl;

>>>> TiguaMayra-Edad.cpp : 

  	cout<<"Ustd Tiene "<<MR_ya<<" años "<<MR_ma<<" meses "<<" y "<<MR_da<<" dias "<<endl;

>>>> TiguaMayra-PuntoVenta.cpp : 

  	cout<<"El valor del iva de su compra es: $ " <<MR_tiva<<endl;

 	cout<<"Su compra obtiene descuento de: "<<MR_vt<<endl;
  
  	cout<<"El valor total a pagar de su compra es: $ "<<MR_pt<<endl;

>>>> TiguaMayra-SumaVNum.cpp : 

  	cout<<"La suma total es: "<<MR_t<<endl;

   # Instalacion 
   
1.- Descargar F-Droid
  
  https://f-droid.org/

2.- Descargar la Terminal (Termux)

    Dentro de la aplicación F-Droid

3.- Instalar paquetes en la Terminal (Termux)

    pkg install git

    pkg install vim

    pkg install g++

    pkg install clang

    apt update

    apt upgrade

4.- Clonar el Repositorio en la Terminal

    git clone https://github.com/MayraTigua/ACTIVIDAD-E2

5.- Acceder al Repositorio

    cd ACTIVIDAD-E2

6.- Acceder al Directorio

    cd ACTIVIDAD-B2-C2

7.- Escribir Comando > ls

    * TiguaMayra-Compara
    * TiguaMayra-Compara.cpp
    * TiguaMayra-Compara.jpg
    * TiguaMayra-CuentaMoneda
    * TiguaMayra-CuentaMoneda.cpp
    * TiguaMayra-CuentaMoneda.jpg
    * TiguaMayra-Edad
    * TiguaMayra-Edad.cpp
    * TiguaMayra-Edad.jpg
    * TiguaMayra-PuntoVenta
    * TiguaMayra-PuntoVenta.cpp
    * TiguaMayra-PuntoVenta.jpg
    * TiguaMayra-SumaVNum
    * TiguaMayra-SumaVNum.cpp
    * TiguaMayra-SumaVNum.jpg  
    
# Copilacion de los programas

1.- Ingresar al Repositorio

  cd ACTIVIDAD-E2

2.- Ingresar al Directorio

  cd ACTIVIDAD-B2-C2

3.- Compilar Programa

  g++ TiguaMayra-SumaVNum.cpp -o TiguaMayra-SumaVNum
  
# Copilacion de los programas
  
  ./TiguaMayra-SumaVNum
    
# Visualizacion del programa
  
 ![Ejecucion de programa de suma de varios numeros](https://user-images.githubusercontent.com/101366766/170888980-1f3d8351-46f2-46ba-bca8-d0c20f4c3623.jpeg)
 
  
  
