int vet[10];
// reserva o espaço da memória e não é possivél alterar depois, ou seja é estático

int *vet;
// falando que é uma váriavel do tipo ponteiro

/*#include <stdio.h>
#include <stdlib.h>

// é capaz de armazenar o enderço de memória
void gera(int *v,int n){
	int i;
	printf("Endereco do vetor na funcao:%x\n",v);
	srand(time(NULL));
	for(i=0;i<n;i++){
	v[i]=rand()%10;
	}
}

int main(){
	
	int n,i;
	int *vet;
	printf("tamanho do vetor:");
	scanf("%d",&n);
	vet = malloc(sizeof(int)*n);
	gera(vet,n);
	
	// sizeof retorna o valor de quantos bytes tem no int
	// malloc aloca um tamanho de memória
	
	srand(time(NULL));
	for(i = 0;i < n;i++){
		vet[i] = rand()%10;
	}
	
	for(i = 0;i < n;i++){
		printf("vet[%d]:%d\n",i, vet[i]);
	}
	
	printf("Endereco do vetor no Main: %x\n",vet);
	
	for(i = 0;i<n;i++){
		printf("Endereco do vetor[%d]: %x\n",i,&vet[i]);
	}
	getch(); // pausa
}*/

// EM Java
/*tBanda nova = new tBanda(0); // new retorna um endereço de memória
nova2 = nova;

public void modifyObject(MyObject obj){
obj.setAttribute("new value:"); // Modifica o objeto original
obj = new MyObject(); // Não afeta a referência original fora do metódo
// tá faltando

public class Car{

private int velocidade;
public int velocidadeAtual() {
return this.velocidade;
}

public void alteraVelocidade(int novaVelocidade) {
this.velocidade = novaVelocidade;
}

}
*/

/*/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package pkg13022025;

/**
 *
 * @author 14679274654
 */
public class Car {

    private int velocidade;

    public int velocidadeAtual() {
        return this.velocidade;
    }

    public void alteraVelocidade(int novaVelocidade) {
        this.velocidade = novaVelocidade;
    }
}

*/

/*/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package pkg13022025;

/**
 *
 * @author 14679274654
 */
public class Main {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        Car novoCarro = new Car();
        novoCarro.alteraVelocidade(10);
        System.out.println("Velocidade do novoCarro:"
                + novoCarro.velocidadeAtual());
        Car carro2 = novoCarro;
        carro2.alteraVelocidade(20);
        System.out.println("Velocidade do novoCarro:"
                + novoCarro.velocidadeAtual());
        System.out.println("Velocidade do carro 2:"
                + carro2.velocidadeAtual());
        // TODO code application logic here
    }

}
*/
