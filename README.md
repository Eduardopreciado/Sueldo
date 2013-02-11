Sueldo
======

ejercicio de prueba

#include <stdio.h>
int sueldo;
float s,sn,n;
int main(void) {
  int sueldo;
	float s,sn,n;
	
	printf("Introducir sueldo actual: ");
	scanf( "%f",&s);
	if (s<=1250){
	     sn=.20*s;
	     n= sn+s;
		printf("Su Nuevo Sueldo Con Aumento De Un 20 Porciento Es: %f",n);
	}
    else{
	printf("No Hay Aumento De Sueldo Tu Sueldo ");
	printf("No Necesita Aumento Deacuerdo A La Empresa \n");
	
	}
}








