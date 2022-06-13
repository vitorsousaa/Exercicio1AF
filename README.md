# Exercicio1AF
Exercicio1 AF Agenda 
Declarar variaveis 
matriz[][] = new int [10][5]
int = coluna = 0, linha = 0
Para linha de 1 até 10 faça 
  Para coluna de 1 até 5 faça 
  Leia Nome (matriz[linha][coluna])
  Leia Endereço (matriz[linha][])
  Leia Código Postal(matriz[linha][coluna]))
  Leia Bairro (matriz[linha][coluna])
  Leia Telefone (matriz[linha][coluna])
  FimPara			
FimPara
Para linha de 1 até 10 faça 
Quebrar linha
  Para coluna de 1 até 5 faça
  Escreva (matriz[linha][coluna])
  FimPara
FimPara




package exercicios_prof_ohata;

import java.util.Scanner;

public class matrizes_agenda {

	public static void main(String[] args) {
		//Declarar variaveis 
		int coluna, linha; //Inica coluna e linha 
		
		String matriz[][] = new String[2][5];//Inicia matriz e atribui o tamanho dela
		
		Scanner input = new Scanner(System.in);//Declara scanner para a entrada de dados
		
		//For para atribuir valores para a matriz
		for (linha = 0; linha < 2; linha++) {
			
			for (coluna = 0; coluna < 5; coluna++) {
				
				//Entrada de dados das linhas e colunas
				System.out.printf("Digite o nome para ser registrado: ");
				matriz[linha][coluna] = input.next();
				
				System.out.printf("Digite o endereco para ser registrado: ");
				matriz[linha][coluna] = input.next();
				
				System.out.println("Digite o codigo postal para ser registrado: ");
				matriz[linha][coluna] = input.next();
				
				System.out.println("Digite o bairro para ser registrado: ");
				matriz[linha][coluna] = input.next();
				
				System.out.println("Digite o telefone para ser registrado: ");
				matriz[linha][coluna] = input.next();
			}	
			
		}
		//Percorre matriz e exibi seus valores
		for (linha = 0; linha < 2; linha++) {
			
			//Quebra linha para formar a tabela
			System.out.printf("\n");
			
			for (coluna = 0; coluna < 5; coluna++) {
				
				//Exibir valor da matriz
				System.out.printf("%s",matriz[linha][coluna]);
			}
		}

	}

}

![image](https://user-images.githubusercontent.com/103973613/173454117-d650d7b0-4dc0-4cfd-bac1-8f03ba639bca.png)


