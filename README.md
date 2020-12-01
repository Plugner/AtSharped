# ReSharped Project

The **ReSharped** language is a **High-Level language** based in **Java**, my first language.

Project Start Date: **01/12/2020**
Current Version: **v-0.0.1 PRE-RELEASE**

# License

We use **MIT License** in our repositories, you can read the license in **LICENSE** file.

# Why use ReSharped?

  
One of the reasons for you to use **ReSharped**, is the practicality in the code, which for being a language in development, has various **updates**.

# Contribute

If you decide to contribute to ReSharped, you can download the sources, and send Pull-Requests, feel free to create a Fork!

# Compilling

To compile, clone this repository, download **Maven** and use the Maven command: 

> **mvn clean package**

# Language Examples

## Hello World
 

    // Set the file package (folders and sub-folders)
    define package = org.resharped.example.helloworld;
    
    // Uses Native Input/Output system
    use Native.IO;

    // Starting the code defining the Class.
    define class HelloWorld {
    
     // Sets a string with the "Hello World!" message.
     define string message = "Hello World!";
    
     // Creating a Function thats returns a void, (main function) 
     define void Main([Array]String:args) {
       // Show the variable as a message in console.
       System.printLine( message );
     }
    }
    

