/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/Classes/Main.java to edit this template
 */
package pkg26.pkg03.pkg2025;

import java.util.Scanner;
        
public class Main {

    static Scanner leia = new Scanner(System.in); // usar o leia em qualquer parte do código

    private static int menu() {
        System.out.println("\n--- Menu Pilha ---");
        System.out.println("1. Inserir elemento");
        System.out.println("2. Remover elemento");
        System.out.println("3. Mostrar topo");
        System.out.println("4. Mostrar pilha");
        System.out.println("0. Sair");
        System.out.printf("Digite a opção desejada:" );
    	return leia.nextInt();
	}
   
    public static void main(String[] args) {
        int opcao;
        System.out.println("Tamanho da pilha: ");
        int tamanho = leia.nextInt(); // passando tamanho da pilha
        
        // criando a Pilha
        Pilha<Integer> minhaPilha = new Pilha(tamanho);
        
        do{
        opcao = menu();
        switch(opcao){
            case 1: // inserir elemento
                if(minhaPilha.isFull()){
                    System.out.println("Pilha cheia, não é possivél inserir");
                }
                else{
                System.out.println("Dado:");
                int dado = leia.nextInt();
                minhaPilha.push(dado);
                }
                break;
            case 2: // remover elemento
                if(!(minhaPilha.isEmpty())){
                System.out.println("Topo removido: " + minhaPilha.pop());
                }
                else{
                System.out.println("Pilha vazia!");
                }
                break;
            case 3:
                if(!(minhaPilha.isEmpty())){
                System.out.println("Valor do Topo: " + minhaPilha.pick());
                }
                else{
                    System.out.println("Pilha vazia!");
                }
                break;
            case 4:
                System.out.println(minhaPilha);
                break;
            case 0:
                System.out.println("Saindo...");
                break;
        } // fim do switch
        leia.nextLine(); // pausa
        }while(opcao != 0); // fim do while
        
    } // fim do main
    
}
