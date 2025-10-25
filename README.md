# my calc

import java.util.Scanner;

//TIP To <b>Run</b> code, press <shortcut actionId="Run"/> or
// click the <icon src="AllIcons.Actions.Execute"/> icon in the gutter.
public class Main {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
      String  toCantine;
        boolean  start ;
        System.out.println("::welcome to in my calculator::");
        System.out.println("to start calculator chiose (true)- to stop calculator chiose(false) ");
        start = input.nextBoolean();
        if (start == true) {


            while (true) {
                {
                    System.out.println("Enter number1:");
                    float number = input.nextFloat();
                    System.out.println("Enter number2:");
                    float number2 = input.nextFloat();
                    System.out.println("Enter operation:");
                    String operation = input.next();

                    switch (operation) {
                        case "+":
                            System.out.println("result :" + (number + number2));
                            break;
                        case "-":
                            System.out.println("result :" + (number - number2));
                            break;
                        case "*":
                            System.out.println("result :" + (number * number2));
                            break;
                        case "/":
                            System.out.println("result :" + (number / number2));
                            break;
                        case "%":
                            System.out.println("result :" + (number % number2));
                            break;


                    }


                }


            }

        }
else{

            System.out.println("::think you to test my calculator::");
        }


    }
}



