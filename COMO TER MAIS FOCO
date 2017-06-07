#include <stdio.h>
#include <stdlib.h>
#include <windows.h>

int main(void) {
    
   
    int segundo = 0;
    int minuto = 5;
    int hora = 0;
    
       for (int i = 15; i < 30; --i) {
        
        printf("\n\n\t\t%dh : %dmin : %dseg", hora, minuto, segundo);
        
        Sleep(1000);
        system("CLS"); 
        segundo++;
        
        if (segundo == 60) {
            segundo = 0;  
            minuto++;
        }   
        
        
        if (minuto == 60) {
            minuto = 0;  
            hora++;
        }  
    }
    
    return 0;
}
