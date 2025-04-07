package com.company;

import java.util.Scanner;

public class Main {


    public static void main(String[] args) {
        Scanner teclado = new Scanner(System.in);
        int idade = 0;


        //exercicio 1

        System.out.println("Digite a sua idade ");
        idade = teclado.nextInt();
       if(idade >=18){
           System.out.println("Voce e maior de idade");
       }else{
           System.out.println("Voce é menor de idade");
       }

       //exercico 2

        System.out.println("Escreva um numero");
        float numero = teclado.nextFloat();
        if(numero <=0){
            System.out.println("seu numero nao é positivo ");
        }else{
            System.out.println("seu numero é positivo");
        }

        //exercicio3
        System.out.println("Digite sua nota");
        float nota = teclado.nextFloat();
        if(nota >=7){
            System.out.println("voce passou");
        }else{
            System.out.println("voce nao atingiu a nota  ");
        }
        //exercicio4
        System.out.println("Digite um numero");
        int par = teclado.nextInt();
        if((par  % 2) ==0){
            System.out.println("seu numero é par");
        }else{
            System.out.println("seu é impar");
        }
        //exercico5
        System.out.println("Digite a temperatura");
        float temperatura = teclado.nextFloat();
        if(temperatura >30){
            System.out.println("esta acima de 30 graus");
        }
        int num = 1;
        while(num >=10)
            System.out.println("\n " +num);
        num--;
    }
}
