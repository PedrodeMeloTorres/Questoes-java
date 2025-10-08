## Questoes-java 08/10


### 3. Escreva um programa que calcule o fatorial de um número digitado pelo
usuário.

```
import java.util.Scanner;

public class Main {

public static void main(String[] args) {

Scanner scan = new Scanner(System.in);

System.out.print("Digite um numero: ");

int num = scan.nextInt();

System.out.print(num + " = ");

int fatorial = 1;

for (int i=num; i>0; i--){

fatorial *= i;

System.out.print( " " + i);

}

System.out.print(" \nresultado: " + fatorial);

}

}

```

### 14. Faça um programa que converta um número romano para decimal.

```
import java.util.Scanner;

public class Teste {

    public static void main(String[] args) {
 Scanner teclado = new Scanner(System.in);
 int numero, i;
int vaNum[]= {1000, 900, 500, 400, 100, 90, 50, 40, 10, 9, 5, 4, 1};
 String vaRom[] = {"M", "CM", "D", "CD", "C", "XC", "L", "XL", "X", "IX", "V", "IV", "I"};
        while(true){
            numero = teclado.nextInt();
            if(numero == 0)
                break;
            System.out.printf("%-4d", numero);
            i=0;
            while(numero>0){
            if(numero >= vaNum[i]){
                System.out.println(vaRom[i]);
                numero = numero - vaNum[i];
}
}
 }
 }
}
```
