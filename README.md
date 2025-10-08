## Questoes-java


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

### 12. Crie um programa que solicite cinco números para o usuário e ordene esses
números de forma crescente.
