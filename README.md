# Build a simple calculator
## Mid Semester Project

### Define the function and the numbers that we will use in this program 
```
int main (){
    
    int bil1,bil2, pil;
    char op;
    do { 
```

### Input the number you want to operate on
```
printf ("Masukkan Bilangan 1 : ");
        scanf("%d", &bil1);
        printf("Masukkan Bilangan 2  : ");
        scanf("%d", &bil2);
 ```

### Select which operation that will use in this calculation
```
printf("Masukkan operasi matematika * - + / ");
        scanf("\n");
```

### Once selected, the operation will be executed immediately
```
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
  ```
  
  ### 
        
        
        
