package atividade_07;

/**
 * @since 10/06/2020
 * @author allys
 */
public class Atividade_07_TabelaFibonacci {

     public static void main(String[] args) {
         new Atividade_07_TabelaFibonacci().executarAlgoritimo(); 
     }

    private void executarAlgoritimo() {
        int numero1 = 1;
        int numero2 = 1;
        imprimir(numero1, numero2);
        
        for(int i = 1; i < 15; i++){
            numero1 = numero1 + numero2;
            numero2 = numero1 - numero2;
            System.out.println(numero1);
            
    }
    }

    private void imprimir(int numero1, int numero2) {
        System.out.println(numero2);
        System.out.println(numero1);
        
    }
