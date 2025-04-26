package Homework;

import java.util.Scanner;

public class LabAssignment1 {
    public static int chooseFunc(){
        Scanner scan = new Scanner(System.in);
        int choose = scan.nextInt();
        return choose;
    }public static int numInput1(int num1){
        Scanner scan = new Scanner(System.in);
        System.out.print("Choose your first number: ");
        num1 = scan.nextInt();
        return num1;
    }public static int numInput2(int num2){
        Scanner scan = new Scanner(System.in);
        System.out.print("Choose your second number: ");
        num2 = scan.nextInt();
        return num2;
    }public static int calcAdd(int num1, int num2){
        System.out.println("Your numbers are: " + num1 + " + " + num2 + ".");
        int finalNum = num1 + num2;
        return finalNum;
    }public static int calcSub(int num1, int num2){
        System.out.println("Your numbers are: " + num1 + " - " + num2 + ".");
        int finalNum = num1 - num2;
        return finalNum;
    }public static double calcDiv(int num1, int num2){
        System.out.println("Your numbers are: " + num1 + " / " + num2 + ".");
        double finalNum = (double)num1 / num2;
        return finalNum;
    }public static int calcMult(int num1, int num2){
        System.out.println("Your numbers are: " + num1 + " x " + num2 + ".");
        int finalNum = num1 * num2;
        return finalNum;
    }public static double calcMod(int num1, int num2){
        System.out.println("Your numbers are: " + num1 + " % " + num2 + ".");
        double finalNum = (double)num1 % num2;
        return finalNum;
    }
    
    public static void main(String[] args) {
        int num1 = 0, num2 = 0, choice;
        double finalNum;
        
        System.out.println("Hello, welcome to the calculator. This adds, subtracts, multiplies, divides 2 numbers, and preforms the modulo (remainder) of 2 numbers.");
        System.out.println("Which function would you like to use?");
        System.out.println("1 = Addition, 2 = Subtraction, 3 = Division, 4 = Multiplication, 5 = Modulo");
        System.out.print("Pick a number: ");
        choice = chooseFunc();
        num1 = numInput1(num1);
        num2 = numInput2(num2);
        
        switch (choice) {
            case 1:
                finalNum = calcAdd(num1, num2);
                System.out.println("The sum of your numbers is: " + finalNum + ".");
                break;
            case 2:
                finalNum = calcSub(num1, num2);
                System.out.println("The difference of your numbers is: " + finalNum + ".");
                break;
            case 3:
                finalNum = calcDiv(num1, num2);
                System.out.println("The quotient of your numbers is: " + finalNum + ".");
                break;
            case 4:
                finalNum = calcMult(num1, num2);
                System.out.println("The product of your numbers is: " + finalNum + ".");
                break;
            case 5:
                finalNum = calcMod(num1, num2);
                System.out.println("The modulo of your numbers is: " + finalNum + ".");
                break;
            default:
                
                System.out.println("Pick a correct number");
                break;
        }
    }
}
