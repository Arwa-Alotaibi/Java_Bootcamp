import java.util.Scanner;

public class Main {
    public static void main(String[] args) {


        System.out.println("Hello world!");
        Scanner input = new Scanner(System.in);


       //1.Write a Java program to print the sum, multiply, subtract, divide and remainder of two numbers.

       System.out.println("Enter your first number:) :");
        int number1 = input.nextInt();
        System.out.println("Enter your secound number:) :");
        int number2 = input.nextInt();
        int sum = number1 + number2;
       int multiply = number1 * number2;
       int subtract = number1 - number2;
       int divide = number1 / number2 ;
       int mod = number1 % number2;
       System.out.println("the sum is : " + (sum));
      System.out.println("the multiply is : " + (multiply));
       System.out.println("the subtract is : " + (subtract));
       System.out.println("the divide is : " + (divide));
       System.out.println("the mod is : " + (mod));


        //2.Write a Java program to convert a given string into lowercase.
        System.out.println("Enter String to convert to lowercase :) : ");
       String namee = input.nextLine();
       String convert = namee.toLowerCase();
       System.out.println("the string after convert : "+ (convert));



       //4.Write a Java program to accept a number and check the number is even or not.
       // Prints 1 if the number is even or 0 if the number is odd. (use if-statement)
        System.out.println("enter your number to check even or odd :) :");
       int number = input.nextInt();
       if(number %2 == 0){
           System.out.println("the number is even "+ 1);
       } else if (number%2 ==1) {
           System.out.println("the number is odd "+ 0);

        }

        //5.Write a program that checks the role of the user
        //If the role is admin print "welcome admin"
        //If the role is superuser print "welcome superuser"
        //If the role is user print "welcome user"
    System.out.println("Enter your role : ");
      String rolee = input.nextLine();

       if(rolee.equals("admin")){
           System.out.println("welcome admin");
        }
        else if(rolee.equals("superuser")){
           System.out.println("welcome superuser");
        }
       else if(rolee.equals("user")){
           System.out.println("welcome user");
       }

        //6.Write a Java program to calculate the sum of two integers and return true if the sum is equal to a third integer.
        System.out.println("enter your first num:");
        int first_number= input.nextInt();
     System.out.println("enter your secound num:");
       int second_number = input.nextInt();

       System.out.println("enter your third num:");
       int third_number = input.nextInt();
       int sum_two = first_number + second_number   ;
       boolean check_number = sum_two == third_number ;
       System.out.println(check_number);





        //7.Take three numbers from the user and print the greatest number.
      System.out.println("enter first number : ");
       int first_num = input.nextInt();

       System.out.println("enter secound number : ");
       int secound_num = input.nextInt();

       System.out.println("enter third number : ");
       int third_num = input.nextInt();

       if (first_num >=secound_num && first_num >=third_num ){
           System.out.println("The greatest: "+ first_num);
       }

        else if(secound_num >=first_num && secound_num>=third_num ){
            System.out.println("The greatest: "+ secound_num);
        }

       else if(third_num >=first_num && third_num>=secound_num  ){
           System.out.println("The greatest: "+ third_num);
        }


        //8.Write a Java program that keeps a number from the user and generates an integer between 1 and 7
        // and displays the name of the weekday.
       System.out.println("generates an integer between 1 and 7 :) :");
       int generates = input.nextInt();
       switch(generates){
           case 1 : System.out.println("monday");
           break;

           case 2 : System.out.println("tuesday");
           break;

           case 3 : System.out.println("wednsday");
           break;

           case 4 : System.out.println("thursday");
           break;

           case 5 : System.out.println("friday");
           break;

            case 6: System.out.println("saturday");
            break;

           case 7: System.out.println("sunday");
           break;

            default:System.out.println("please enter a valid number !!");

        }


    }




}


