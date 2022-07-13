# uslu_sayilar.java
www.patika.dev Uslu sayilar



        import java.util.Scanner;

        public class uslu_sayilar {
        public static void main(String[] args) {
        int a;
        System.out.println("Ust limiti giriniz:");
        Scanner input= new Scanner(System.in);
        a=input.nextInt();
        for (int i =1;i<a;i*=4){
            System.out.println(i);
        }
        for (int i=1;i<a;i*=5){
            System.out.println(i);
        }
    }
}
