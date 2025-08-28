[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/KfWXY3c0)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=20182673)
Change the code so that instead of saying "Hello World" it says "Hello Object Oriented Programming", and then compile and test. 
Additionally try these out and see what errors you get. Document your errors here in the readme. (This is taken from Exercise 3 in the text book).

Starting with the Hello World program, try out each of the following errors. After you make each change, compile the program, read the error message (if there is one), and then fix the error.

Remove one of the opening curly braces.
    Exception in thread "main" java.lang.Error: Unresolved compilation problem: 

        at HelloWorld.main(HelloWorld.java:2)


Remove one of the closing curly braces.
    Exception in thread "main" java.lang.Error: Unresolved compilation problem: 
        Syntax error, insert "}" to complete ClassBody

        at HelloWorld.main(HelloWorld.java:4)


Instead of main, write mian.
    Error: Main method not found in class HelloWorld, please define the main method as:
   public static void main(String[] args)
    or a JavaFX application class must extend javafx.application.Application

Remove the word static.
    Error: Main method is not static in class HelloWorld, please define the main method as:
    public static void main(String[] args)

Remove the word public.
    Error: Main method not found in class HelloWorld, please define the main method as:
    public static void main(String[] args)
    or a JavaFX application class must extend javafx.application.Application

Remove the word System.
    Exception in thread "main" java.lang.Error: Unresolved compilation problem: 
        out cannot be resolved

        at HelloWorld.main(HelloWorld.java:3)v

Replace println with Println.
    Exception in thread "main" java.lang.Error: Unresolved compilation problem: 
        The method Println(String) is undefined for the type PrintStream

        at HelloWorld.main(HelloWorld.java:3)

Replace println with print.
         Works fine but it does not generate a new line.


Delete one parenthesis.
    Exception in thread "main" java.lang.Error: Unresolved compilation problem: 
        Syntax error on token "println", ( expected after this token

        at HelloWorld.main(HelloWorld.java:3)

Add an extra parenthesis.
    Exception in thread "main" java.lang.Error: Unresolved compilation problem: 
        Syntax error, insert ")" to complete Expression

        at HelloWorld.main(HelloWorld.java:3)


Fix the code so it works and commit your changes.
