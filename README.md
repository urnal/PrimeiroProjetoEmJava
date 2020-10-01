# PrimeiroProjetoEmJava
Primeiro Projeto
import java.util.Scanner;

pubic class NextLevel {
    public static void main(String[] args) {
        scanner sn = new Scanner(System.in)
        System.out.print("Digite seu nome: ");
        String nome = sc nextline();
        System.out.print("Bem vido "+nome+".");

pubic class CalculoMedia {
    pubic static void main(String[] args) {
       
       
        int peso1 = 3; int peso2 = 3; int peso3 = 2; int peso4 = 3;
        
        
        Scanner nota1 = new Scanner(System.in);
        System.out.print("Digite a sua primeira nota:");
        int a = nota1.nextInt();
        int valornota1 = a * peso1;
        //System.out.println(valornota1);

        Scanner nota2 = new Scanner(System.in);
        System.out.print("Digite a sua segunda nota:");
        int b = nota2.nextInt();
        int valornota2 = b * peso2;
        //System.out.println(valornota2);

        Scanner nota3 = new Scanner(System.in);
        System.out.print("Digite a sua terceira nota:");
        int c = nota3.nextInt();
        int valornota3 = c * peso3;
        //System.out.println(valornota3);

        Scanner nota 4 = new Scanner(System.in);
        System.out.print("Digite a sua quarta nota:");
        int d = nota4.nextInt();
        int valornota4 = d * peso4;
        //System.out.println(valornota4);

        int mediabimestre1 = ((valornota1+valornota2+valornota3+valornota4)/11);


        System.out.println("NOTA DO SEGUNDO BIMESTRE");

        Scanner nota5 = new Scanner(System.in);
        System.out.print("Digite a sua primeira nota:");
        int a2 = nota5.nextInt();
        int valornota5 = a2 * peso1;
        //System.out.println(valornota5);

        Scanner nota6 = new Scanner(System.in);
        System.out.print("Digite a sua segunda nota:");
        int b2 = nota6.nextInt();
        int valornota6 = b2 * peso2;
        //System.out.println(valornota6);

        Scanner nota7 = new Scanner(System.in);
        System.out.print("Digite s sua terceira nota:");
        int c2 = nota7.nextInt();
        int valornota7 = c2 * peso3;
        //System.out.println(valornota7);

        Scanner nota8 = new Scanner(System.in);
        System.out.print("Digite a sua quarta nota:");
        int d2 = nota7.nextInt();
        int valornota8 = d2 * peso4;
        //System.out.println(valornota8);

        int mediabimestre2 = ((valornota5+valornota6+valornota7+valornota8));


        System.out.println("NOTA DO TERCEIRO BIMESTRE");

        Scanner nota9 = new Scanner(System.in);
        System.out.print("Digite a sua primeira nota:");
        int a3 = nota9.nextInt();
        int valornota9 = a3 * peso1;
        //System.out.println(valornota5);

        Scanner nota10 = new Scanner(System.in);
        System.out.print("Digite a sua segunda nota:");
        int b3 = nota10.nexInt();
        int valornota10 = b3 * peso2;
        //System.out.println(valornota6);

        Scanner nota11 = new Scanner(System.in);
        System.out.print("Digite a sua terceira nota:");
        int c3 = nota11.nextInt();
        int valornota11 = c3 * peso3;
        //System.out.println(valornota7);

        Scanner nota12 = new Scanner(System.in);
        System.out.print("Digite a sua quarta nota:");
        int d3 = nota12.nextInt();
        int valornota12 = d3 * peso4;
        //System.out.println(valornota8);

        int mediabimestre3 = ((valornota9+valornota10+valornota11+valornota12)/11);


        if ((mediabimestre1+mediabimestre2+mediabimestre3)/3 >= 8) {
            
            System.out.println("APROVADO"); 
       
        } if { System.out.println("REPROVADO");
        
        System.out.println("A sua nota minima na prova final e: " + 10-(mediabimestre1+mediabimestre2+mediabimestre3)".") 
        }



    }