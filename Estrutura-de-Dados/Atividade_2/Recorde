package atividade_2;

import java.time.LocalDate;

public class Recorde {
    private LocalDate data;
    private double tempo;
    private String nome;
    private int topo;
    private Recorde[] elementos;
    
    public void setRecorde(LocalDate data, double tempo,String nome){
    
    this.topo++;
    this.data = data;
    this.tempo = tempo;
    this.nome = nome;
    
    }
    public void Recorde(int tamanho){
    this.elementos = (Recorde[]) new Object[tamanho];
    this.topo = -1;
    }
    public LocalDate getData(){
        return data;
    }
    public double getTempo(){
        return tempo;
    }
    public String getNome(){
        return nome;
    }
    
    public boolean isEmpty() {
        // Verifica se a pilha está vazia
        return this.topo == -1; 
        // Retorna true se o índice do topo for -1 (pilha vazia)
        // Isso equivale ao seguinte código:
        /*
        if (this.topo == -1) {
            return true;
        } else {
            return false;
        }
        */
    } // fim do isEmpty
    
    public boolean isFull() {
        // Verifica se a pilha está cheia
        return this.topo == this.elementos.length - 1; 
        // Retorna true se o índice do topo for igual ao último índice do array
        // Essa lógica também pode ser escrita como:
        // return this.elementos.length - 1 == this.topo;
    } // fim do isFull
    
    
    @Override
    public String toString() {
        // Este método sobrescreve o `toString` padrão da classe Object para retornar
        // uma representação personalizada dos elementos da pilha, do topo até o início.
        StringBuilder retorno = 
                new StringBuilder(); // Adiciona a palavra "Topo" ao início da visualização
                for (int i = this.topo; i >= 0; i--) {
                    retorno.append(this.nome + "," + this.tempo + "," + this.data + "\n"); // Adiciona cada elemento, linha por linha
                }
                
                return retorno.toString(); // Retorna a String construída com todos os elementos
    }
    
}
