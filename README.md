# arrayExercise
Crie um menu onde o usuário possa escolher 1 entre 4 opções de filme diferentes utilizando um array.




package aula04.arrays;
import java.util.Scanner;

public class arraysExercise {
    public static void main(String[] args) {

        Scanner scan = new Scanner(System.in);

        String[] filmes = new String [4];
        filmes[0] = "Homem de Ferro 2";
        filmes[1] = "Era uma vez";
        filmes[2] = "Exorcista";
        filmes[3] = "Nárnia";

        System.out.println("Selecione um dos filmes abaixo");
        System.out.println("1. " + filmes[0]);
        System.out.println("2. " + filmes[1]);
        System.out.println("3. " + filmes[2]);
        System.out.println("4. " + filmes[3]);
        int selection = scan.nextInt();

        if(selection == 1){
            System.out.println(filmes[0]);
        } else if(selection == 2){
            System.out.println(filmes[1]);
        } else if(selection == 3){
            System.out.println(filmes[2]);
        } else if (selection == 4){
            System.out.println(filmes[3]);
        } else {
            System.out.println("Opçao inválida");
        }
    }
}


