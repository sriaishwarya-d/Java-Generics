Java Generics - Maximum Value

A Java program that demonstrates the use of generics to find the maximum value from different types of arrays.
Features
- Finds the maximum integer value
- Finds the maximum float value
- Finds the maximum string value
- Uses a single generic method for different data types
- Uses the Comparable interface for comparison
Concepts Used
- Java Generics
- Generic Methods
- Bounded Type Parameters
- Comparable Interface
- Arrays
- compareTo() Method
- Classes and Objects
How It Works
The program defines a generic method called findMax() that accepts an array of a generic type. The type is bounded by Comparable<T>, allowing the elements to be compared with each other. GENERIC(PROGRAM,OUTPUT)
The program tests the generic method with three different types of arrays:
- Integer array
- Float array
- String array GENERIC(PROGRAM,OUTPUT)
The maximum value from each array is then displayed.
Sample Input
The program uses the following arrays:
Integer: 10, 23, 34, 5, 47
Float: 10.4, 25.6, 17.9, 40.8
String: apple, mango, orange, banana

Sample Output
Maximum integer = 47
Maximum Float = 40.8
Maximum String = orange

The uploaded program produces these results for the given arrays. GENERIC(PROGRAM,OUTPUT)
How to Run
1. Make sure Java is installed on your computer.
2. Open a terminal in the project folder.
3. Save the program as genericMaximum.java.
4. Compile the program:
javac genericMaximum.java

5. Run the program:
java genericMaximum

File Structure
Java-Generics/
└── genericMaximum.java

Author
Sri Aishwarya D
