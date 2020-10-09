# examen.ejercicio-2

#include <stdio.h>
int main(){
   int numero;
   int potencia=0;
   
   for (numero=1, numero<=5; numero++)
   {
   potencia= numero*numero*numero;
   printf("El cubo del numero % es %i\n", numero, potencia);
   }

return0;
}
