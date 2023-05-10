#include <stdio.h>

int main (){
    
    int bil1,bil2, pil;
    char op;
    do {
        printf ("Masukkan Bilangan 1 : ");
        scanf("%d", &bil1);
        printf("Masukkan Bilangan 2  : ");
        scanf("%d", &bil2);
        printf("Masukkan operasi matematika * - + / ");
        scanf("\n");
        scanf("%c", &op);
        if (op=='+'){
            printf("%d", bil1+bil2);
        } else if (op=='-'){
            printf("%d", bil1-bil2);
        } else if (op=='*'){
            printf("%d", bil1*bil2);
        } else if (op=='/'){
            printf("%.2f", bil1/bil2);
        }
        printf("\n");
        printf("Apakah anda ingin menggunakan kalkulator lagi?\n1. Ya\n2. Tidak\n");
        scanf("%d", &pil);
    } while (pil==1);
    return 0;
}
