# Coding-Basics-
1. Odd or Even
###Method 1: Modulo (Normal)
import java.util.Scanner;
public class OddEven_Modulo {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter number: ");
        int n = sc.nextInt();
        System.out.println(n % 2 == 0 ? "Even" : "Odd");
    }
}    
###Method 2: Bitwise
import java.util.Scanner;
public class OddEven_Bitwise {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter number: ");
        int n = sc.nextInt();
        System.out.println((n & 1) == 0 ? "Even" : "Odd");
    }
}
###Method 3: Division Formula
import java.util.Scanner;
public class OddEven_Division {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter number: ");
        int n = sc.nextInt();
        System.out.println((n / 2) * 2 == n ? "Even" : "Odd");
    }
}
###Method 4: GFG Format (return boolean)
class Solution {
    static boolean isEven(int n) {
        return n % 2 == 0;        // Method 1: Modulo
        // return (n & 1) == 0;   // Method 2: Bitwise
    }
}

