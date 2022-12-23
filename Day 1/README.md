# Java Introduction

[![ Introduction To Java](https://github.com/Gowtham-Kanagaraj/Core-Java/blob/main/images/intro.jpg)](https://www.youtube.com/watch?v=xVRp-38R234 " Introduction To Java - Click to Watch!")

click above image to watch youtube lesson by - Suraj

Java is a programming language developed by Sun Microsystems (now owned by Oracle Corporation). It was first released in 1995 and has since become one of the most widely used programming languages in the world. Java is known for its "write once, run anywhere" philosophy, which means that Java code can be compiled and run on any device with a Java Virtual Machine (JVM). This makes it a popular choice for developing applications that can be deployed on a variety of platforms, including Windows, Mac, Linux, and mobile devices. Java is also used for building server-side applications, including web applications, and it is a popular choice for developing Android apps.

There are several different versions of the Java programming language, including:

1. Java SE (Standard Edition): This is the core Java platform and includes the Java language and a set of libraries for developing standalone applications.

2. Java EE (Enterprise Edition): This is an extension of Java SE and includes additional libraries and APIs for developing enterprise applications, such as web applications, distributed systems, and multi-tier applications.

3. Java ME (Micro Edition): This is a version of Java designed for developing applications for small devices, such as mobile phones and embedded systems.

In addition to these main versions of Java, there are also other specialized versions, such as Java FX for building rich internet applications and Java Card for developing applications that run on smart cards.

## "write once, run anywhere"
Here is an example of how the "write once, run anywhere" philosophy of Java could be applied to the development of a TV remote control application:

First, the developer would create the application using the Java programming language and any necessary libraries.

The application would then be compiled into bytecode, which is a platform-independent format that can be run on any device with a Java Virtual Machine (JVM).

The bytecode could be packaged into a file, such as a JAR or WAR file, and deployed to the desired devices.

On each device, the JVM would interpret the bytecode and execute the application.

In this way, the TV remote control application could be developed and deployed on a wide range of devices, including smart TVs, streaming devices, and even mobile phones, without the need to rewrite the code for each individual platform. The developer could write the code once and have it run on any device with a JVM, saving time and effort.

## Java features

Java is a popular programming language known for its simplicity, portability, and security. Some of the key features of Java include:

1. Object-oriented programming: Java is an object-oriented programming language, which means that it supports the creation and manipulation of objects that represent real-world entities. This allows developers to model complex systems and solve problems in a more organized and reusable way.

2. Platform-independence: Java is designed to be "write once, run anywhere," which means that Java code can be compiled and run on any device with a Java Virtual Machine (JVM). This makes it a popular choice for developing applications that can be deployed on a variety of platforms, including Windows, Mac, Linux, and mobile devices.

3. Concurrency: Java supports concurrent programming, which allows multiple threads to execute simultaneously within a single program. This makes it easier to develop applications that can take advantage of multi-core processors and improve performance.

4. Security: Java includes a number of security features, such as a built-in security manager and support for digital signatures, that help to protect against malicious code and ensure the integrity of applications.

5. Extensive libraries: Java has a large and comprehensive set of libraries for a wide range of tasks, including input/output, networking, data structures, and more. This makes it easier for developers to create powerful applications without having to reinvent the wheel.

6. Automatic memory management: Java includes a garbage collector that automatically frees up memory that is no longer being used by the program. This helps to prevent common memory-related errors and makes it easier for developers to write efficient and reliable code.

## Java Platform-independence:

In the early days of Java, the "write once, run anywhere" philosophy of the language was a major advantage for developers. Prior to Java, most programming languages were tied to specific platforms, requiring developers to write and maintain separate versions of their code for different systems. This was time-consuming and error-prone, as any changes or updates to the code had to be made separately on each platform.

Java's platform-independent nature made it much easier for developers to create applications that could be deployed on a variety of systems. For example, a developer could write a Java application on a Windows PC and then easily deploy it on a Mac, a Linux server, or even a mobile phone. This greatly reduced the time and effort required to develop and maintain applications, and made it possible for developers to reach a wider audience with their soft

    Java is designed to be "write once, run anywhere," which means that Java code can be compiled and run on any device with a JVM, regardless of the underlying operating system (OS) or hardware architecture. This is made possible by the use of the JVM, which is a software implementation of a virtual machine that executes Java bytecode. When a Java program is compiled, it is transformed into bytecode, which is a platform-independent format that can be run on any device with a JVM. The JVM interprets the bytecode and executes the program, providing the necessary platform-specific features and resources.

Here are a few examples of how Java can be used to write platform-independent code on systems with different hardware architectures:

* IBM: IBM produces a variety of hardware platforms, including servers, workstations, and mainframes, which can run the Java Virtual Machine (JVM). This means that Java applications can be developed and deployed on IBM systems without needing to be rewritten for the specific hardware architecture.

* Apple: Apple's Mac and iOS devices use a hardware architecture known as ARM. Java applications can be run on these devices using the JVM, which allows them to be deployed and run without needing to be rewritten for the specific hardware architecture.

* Sun: Sun Microsystems (now owned by Oracle Corporation) developed the SPARC hardware architecture, which is used in many high-performance servers and workstations. Java applications can be run on SPARC systems using the JVM, allowing them to be deployed and run without needing to be rewritten for the specific hardware architecture.

## Simple program

* Install the Java Development Kit (JDK): The JDK is a software development kit that includes the tools and libraries needed to develop Java applications. It can be downloaded from the Oracle website or from a package manager (such as Homebrew on Mac).

* Create a Java source file: A Java source file is a plain text file that contains the Java code for your program. The source file should have a .java extension and should contain a single public class with a main method, which is the entry point for the program.

* Compile the source file: To compile the source file, open a terminal or command prompt and navigate to the directory where the source file is located. Then, use the javac command to compile the source file. For example:

        javac HelloWorld.java

This will create a new file with a .class extension that contains the compiled bytecode for your program.

* Run the program: To run the program, use the java command followed by the name of the class that contains the main method. For example:

        java HelloWorld

This will start the JVM and execute the main method in your program.

Here is a simple "Hello, World!" program written in Java:
        
        public class HelloWorld {
            public static void main(String[] args) {
                System.out.println("Hello, World!");
            }
        }


To run this program, you will need to compile it using the javac command and then run it using the java command. For example:

        javac HelloWorld.java
        java HelloWorld
This will start the JVM and execute the main method in the HelloWorld class, causing the string "Hello, World!" to be printed to the console.

Here is a brief explanation of what each line of code does:

1. The first line declares the class name as "HelloWorld."
2. The second line declares the main method, which is the entry point for the program.

3. The third line uses the System.out.println() method to print the string "Hello, World!" to the console.

4. The fourth line closes the main method.

5. The fifth line closes the class definition.

![Java execution](https://github.com/Gowtham-Kanagaraj/Core-Java/blob/main/images/java_execution.jpg)

![Java Keywords](https://github.com/Gowtham-Kanagaraj/Core-Java/blob/main/images/basic_keyword_in_java.jpg)
