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
