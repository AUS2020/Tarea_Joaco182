#include <stdio.h>
#define MM3(X,Y,Z) (Num1>Num2 && Num1>Num3) ? (printf("%d Es el mas grande",Num1)) : ( (Num2>Num3) ? (printf("%d Es el mas grande",Num2)) : (printf("%d Es el mas grande",Num3)))
#define PAR(X) ((N1)%2)

int main(void) {


int N;              //Variable del swich

float radio;        //Variable  case 1

int Num1,Num2,Num3; //Variables case 2    //Importante, hay que introducir las variables fuera del switch, porque sino tira error (por lo menos en mi caso no me dejaba)

int N1;             //Variable  case 3


  printf("Ingrese un numero....\n Para Mas Informacion\n Presione 0\n");          //Aca pedi que se ingresara un numero, Con aclaracion que al ingresar 0 muestre que opciones tenes
    scanf("%d",&N);

switch(N) {                       //creo el switch

                case 0:           //caso de las opciones

    printf("Nº1 -------> Saber el Radio y Circunferencia de un Circulo\n Nº2 -------> Saber Que numero es mas grande Entre [3Nums] \n Nº3 -------> Saber si un Numero es Par o Impar"); //Cree las opciones
    break;                        //Esto se utiliza para salir del switch
 
                    
                    case 1:           //caso del primer subprograma

printf("Ingrese el radio de la circunf:");
    scanf("%f", &radio);                    // va con & porque le pasamos el lugar de memoria de radio a scanf

printf("El perimetro de la circunf es: %f\n",3.141592*radio);

printf("El area de la circunf: %.3f\n",3.141592*radio*radio);

break;                            //Esto se utiliza para salir del switch

                case 2:          //caso del segundo subprograma

printf("Ingrese los numeros a comparar... \n [Maximo 3] \n");
    scanf("%d %d %d",&Num1,&Num2,&Num3);

    MM3(Num1,Num2,Num3);  //Esto es un macro se encuentra en las primeras 3 lineas del programa

    break;

                case 3:          //Caso del tercer subprograma


printf("Introdusca Un Numero...\n");
    scanf("%d",&N1);

    if(PAR(N1) == 0) {
     printf("El Numero es par");
    }
    else{
      printf("El Numero no es par");
      break;
    }

}
        return 0;
}
