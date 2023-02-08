# DZ-C-F
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.println("Введите число");
        int a = 32;
        double b = 1.8;
        double c;
        c = scanner.nextDouble();
        double result = c * b + a;
        System.out.println("Ваш результат " + result);
    }
}
