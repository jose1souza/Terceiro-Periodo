/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package pkg19032025;

/**
 *
 * @author 14679274654
 */
public class Main {
    
    // aumentando a velocidade em 1
    static void addVelocidade(int velocidade){
        velocidade++;
        System.out.println("Velocidade na funcao: " + velocidade);
    }
    
    // recebendo por endereço de memória
    // pega um carro e altera a velocidade
    // qualquer alteração vai alterar no meu objeto
    static void addVelocidade2(Car carro){
        int novaVelocidade = carro.velocidadeAtual();
        novaVelocidade++;
        carro.alteraVelocidade(novaVelocidade);
        System.out.println("Velocidade na funcao 2: " + novaVelocidade);
    }
    
    static void alteraNome(String novoNome){
        novoNome+= " IFSULDEMINAS";
        System.out.println("Nome na funcao: " + novoNome);
    }

    public static void main(String[] args) {
        // instanciando um objeto para retornar o endereço de memória
        Car novoCarro = new Car();
        novoCarro.alteraVelocidade(10);
        System.out.println("Velocidade do novoCarro:"
                + novoCarro.velocidadeAtual());
        
        // chamada de funçao velocidade
        int minhaVelocidade = novoCarro.velocidadeAtual();
        addVelocidade(minhaVelocidade);
        
        // Como foi passado por valor o 
        // valor do main continua 10 e o da funcao muda 
        
        // mostrando minha velocidade
        System.out.println("Minha Velocidade: " + minhaVelocidade);
        
        // chamada da segunda função 
        addVelocidade2(novoCarro);
        System.out.println("Segunda funcao no main:" + 
                novoCarro.velocidadeAtual());
        
        
        String nome = "José";
        alteraNome(nome);
        System.out.println("Nome no main: " + nome);
        // Strings são imutaveis
        
        /*
        // guarda o endereço de memória
        Car carro2 = novoCarro;
        carro2.alteraVelocidade(20); 
        System.out.println("Velocidade do novoCarro:"
                + novoCarro.velocidadeAtual());
        System.out.println("Velocidade do carro 2:"
                + carro2.velocidadeAtual());
        // TODO code application logic here*/
    }
    
}
