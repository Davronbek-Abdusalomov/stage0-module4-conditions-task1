# Tasks:
#### 1) True printer.
Create a program that will print "true" to console. Printing command should be placed inside if block
which will have "true" in condition part.  Program should be implemented in code snippet:


        public class ConditionalTruePrinter {
            public static void main(String[] args) {
            if(true){
            System.out.println(true);
            }
            }
        }

#### 2) False printer.
Create a program that will print "false" to console from else part of "if" block. Printing command
should be placed inside else block, whereas "if" condition will have "false" in condition part.  Program should be
implemented in code snippet:


        public class ConditionalFalsePrinter {
            public static void main(String[] args) {
            if(false){
            System.out.println(true);
            }
            else  
            {
            System.out.println(false);}
            }
        } 



#### 3) No brackets printer.
Put the brackets to the code snippet so as to not print anything to console in the following
code snippet:


        public class NoBracketsPrinter {
            public static void main(String[] args) {
               if(false){
                  System.out.println("The statement is true");}
                  System.out.println("");
            
            }
        }


#### 4) Integer comparison.
Fill the gaps in the code snippet so that the program compiles and prints: "Hello, World!"


        public class IntegerComparison {
            public static void main(String[] args) {
                  int x = 50;
                  int y = 50;
                 if(x == y) {
                         System.out.println("Hello, World!");
                  }
           }
        }


#### 5) Positive number determiner.
Create a program that will determine and print if consumed number is positive (in this
case print true) or no (print false) using if-else block. The program should be implemented inside of code snippet:


        public class PositiveNumberDeterminer {
           public void isPositive(int numberToBeDetermined) {
           if(numberToBeDetermined>0){
           System.out.println(true);}
           else 
               System.out.println(false);
           }
        }

Where numberToBeDetermined - var that should be used to print if it is positive.
