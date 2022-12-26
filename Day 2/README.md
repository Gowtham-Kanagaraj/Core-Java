# Dissecting Java program

## what is the difference between JRE and JDK

Java Runtime Environment (JRE) is a software package that contains what is needed to run a Java program. It includes the Java Virtual Machine (JVM), the Java class libraries, and other supporting files. JRE is used to run Java programs, but not to develop them.

Java Development Kit (JDK) is a software development kit that includes tools for developing Java programs. It includes the JRE, as well as the compilers and other tools needed to develop Java code. The JDK is used to create Java programs and applets, as well as run them.

In summary, JRE is a runtime environment that allows you to run Java programs, while JDK is a development kit that includes tools for developing and running Java programs.

## What are Class and Objects in Java

!n the Java programming language, a class is a template that defines the data and behavior of a type of object. An object is an instance of a class.

Here is an example of a simple class in Java:

    public class Dog {
        // instance variables
        String breed;
        int age;
        String color;

    // constructor
    public Dog(String breed, int age, String color) {
        this.breed = breed;
        this.age = age;
        this.color = color;
    }

    // method
    public void bark() {
        System.out.println("Woof!");
    }
    }

This class defines a type of object called "Dog", with three instance variables (breed, age, and color) and one method (bark).

To create an object of the Dog class, you can use the following code:

    Dog myDog = new Dog("Labrador", 3, "yellow");

This creates an object called "myDog" that is an instance of the Dog class, with the specified breed, age, and color. You can then call the object's method like this:

    myDog.bark();  // Outputs "Woof!"


A class is like a blueprint for an object. It defines the properties and behavior that the object will have. For example, you could create a class called "Pen" that has the following properties:

1. color (e.g. blue, black, red)
2. brand (e.g. Bic, Pilot, Uni-ball)
3. ink level (e.g. full, half full, empty)

The class could also have the following behavior:

* write: produces writing on a piece of paper
* refill: adds ink to the pen

An object is an instance of a class. It has the properties and behavior defined by the class, but with specific values for those properties. For example, you could create an object called "myPen" that is an instance of the "Pen" class, with the following properties:

* color: blue
* brand: Bic
* ink level: full

You could then use the object's behavior like this:
    
    myPen.write("Hello, world!") // produce writting on pieces os paper

    myPen.refill() // adds ink to the pen
    
So in this example, the "Pen" class is the blueprint, and "myPen" is an object of that class, with specific values for its properties and the ability to perform the behavior defined in the class.


## "Hello, World!" program in Java:

    public class HelloWorld {
      public static void main(String[] args) {
        System.out.println("Hello, World!");
        }
    }

1. public class HelloWorld - This line declares a class called "HelloWorld". The public keyword means that the class can be accessed by any other class in the Java program.

2. public static void main(String[] args) - This line declares the main method of the class. The public static void part means that the method is public (can be accessed by any other class in the Java program), static (belongs to the class itself, rather than an instance of the class), and returns no value (void). The main method is the entry point for the Java program, meaning that it is the first method that is executed when the program starts. The String[] args part declares an array of String objects called "args", which can be used to pass command-line arguments to the program.

3. System.out.println("Hello, World!"); - This line prints the string "Hello, World!" to the console. The System.out.println method is a predefined method in the Java library that prints a string to the console and adds a new line after it.

In this example, "HelloWorld" is the name of the class and can be changed to any other valid identifier. The contents of the main method, including the println statement, can also be modified as desired.

## main() method:

In the Java programming language, the main method is the entry point for a Java application. It is the method that is executed when the program starts. The main method is always declared with the following syntax:

    public static void main(String[] args)

In the above hello world program, the public keyword means that the method can be accessed by any other class in the Java program. The static keyword means that the method belongs to the class itself, rather than an instance of the class. The void keyword means that the method does not return a value.

The main method takes an array of String objects as its argument. This array is called "args" and can be used to pass command-line arguments to the program.


When we execute hello  world program, the main method is called and the string "Hello, World!" is printed to the console.

It is important to note that every Java application must have a main method in order to be executed. The main method is the starting point of the program and is where the program's logic begins to execute.

## what is static method? why java main method is static

In the Java programming language, a static method is a method that belongs to a class, rather than an instance of the class. This means that the method can be called without creating an object of the class.

Static methods are often used for utility or helper functions that do not depend on the state of an object. They can be called directly from the class, rather than from an object of the class.


In the above hello world's  example, the main method is a static method that prints hello world in the console.

    HelloWorld.main(); 

The main method in a Java program is declared as static because it is called by the Java runtime system before any objects of the class are created. This means that the main method needs to be accessible without an object of the class being present.

It is also worth noting that the main method must be public, which means that it can be accessed by any other class in the Java program. This is necessary because the main method is the entry point for the Java program and needs to be able to be accessed by the Java runtime system when the program is launched.

## why main method has void return type

In the Java programming language, the main method is the entry point for a Java application and is declared with the void return type. This means that the main method does not return a value when it is finished executing.

The void return type is used for methods that do not return a value. In the case of the main method, the Java runtime system calls the main method when the program starts and does not expect a return value. Instead, the main method is responsible for executing the logic of the program and producing any necessary output

In the above hello world example, the main method does not return a value. Instead, it simply prints the string "Hello, World!" to the console.

It is important to note that the main method must be declared as void, as this is the required syntax for the entry point of a Java program. If the main method were declared with a different return type, the program would not be able to execute.

## do we need to define main method inside public class?

Yes, in the Java programming language, the main method must be defined inside a public class.

The main method is the entry point for a Java application and is called by the Java runtime system when the program starts. In order to be called, the main method must be defined inside a class, and that class must be declared as public.

In the above hello-world example, the main method is defined inside the HelloWorld class, which is declared as public. This means that the main method can be accessed by the Java runtime system and the program can be executed.

It is important to note that the main method must be declared as public and static in order to be called by the Java runtime system. It must also have the required syntax, including the void return type and the String[] args argument.

## relation between java code file name and class name

In the Java programming language, the name of a code file (also known as a source file) must match the name of the public class or interface it contains.

For example, if a code file contains a public class called "HelloWorld", the code file must be named "HelloWorld.java". Similarly, if a code file contains a public interface called "MyInterface", the code file must be named "MyInterface.java".

In the abvoe hello-world example, the code file is named "HelloWorld.java", which matches the name of the public class it contains.

It is important to note that a code file can contain multiple classes and interfaces, but only one of them can be declared as public. The name of the code file must match the name of the public class or interface.