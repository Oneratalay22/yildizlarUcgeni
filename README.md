import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        System.out.println("Bir sayı giriniz:");
        int n = input.nextInt();

        int i = 1;
        while (i <= n) {
            int k = 1;
            while (k <= (n - i)) {
                System.out.print(" ");
                k++;
            }

            int j = 1;
            while (j <= (2 * i) - 1) {
                System.out.print("*");
                j++;
            }

            System.out.println();
            i++;
        }

    }
    }

