# Java Fundamentals ##

*  A simple Java Program
	* public class FirstSample {. //(Class scope - highlighted in green)//
			public static void main(String[] args { //(Method Body - highlighted in yellow/gold blocks)//
				System.out.println("We will not use 'Hello World'");
				}
	}
	
	
*   Method belongs to classes, members of the class (interview buzzword)

* Null-ary Methods
	* public static void anotherMethod() {
		System.out.println("The quick brown fox");
	}
	
* Java programming - cannot print system outside of a method, cannot write object w/o class?? 
* Java is case sensitive
* Class names must begin with a letter, and after that, they can have any combination of letters, digits, and underscores 
	* By convention, class names start with a capital letters (firstSample vs. FirstSample)
	* cannot name it a reserved word as well
* You need to make the name for the source code the same as the public source code
	* Whitespace is irrelevant to the compiler (be mindful of whitespace so other dev can read it.)
* For every open curly bracket, there is a closed curly bracket - in reference to the Carnell question on location of {} []
	* when clicking on the brackets the corresponding bracket is highlighted  

* Scope will be named off the term it representing**
* local scope w/ the class - not global scope

* A Class defines all of the Java code 
	* In Java (pretty much) everything is an Object - 
	* **main** is  merely a special method that is executed when the program runs
	* **main** doesn't return anything, thus the **void** return keyword
	* **main** doesn't operate on an object, thus the **static** keyword  	 
		* **Static** means occuring or exisiting independent of the state of the object

## Object Stuff
*	Since almost everything in Java is an object , for now remembert that:
	* Static methods are called on a **CLass**, not on objects themselves
		* SomeObject.someMethod() <-- starts the consturction of the method
	* Instnace mehtods are called on instances of the objects directly  

	example: SomeObject so = new SomeObject();
	so.someInstanceMethod();
	
* Method by itself = function (lives independent of object) 
* method w/o class or object is not a method, its a function

### Java Environment
* Code is complied with javac
	* javac Example.java 

### Java Comments
* // for single line
* /* */multiline
* /** */ - will be used to generate documentation automatically

### Data Types -
* Java is a strongly typed language and every variable must have a declared type
	* **declaration** of the variable can occur once, and can be changed w/o declaring the variable again
	* **Declaration w/o initialization** - variable w/o value --> default number when run will be zero 
	* ex: int x: - declaration of variable x with no value
				x = 10; // assignment & **initalization** of some variable, x whose value is 10
				x = 11; // assignment (not initialization) of some variable, x whose value is 11

* Eight Primitive types in Java: (lowercase) - mistake from the grandfather program - corrected since w/ future versions of Java. 
	* int
	* short
	* long
	* byte
	* float
	* double
	* char
	* boolean

## Integer Types 
	* integertypes are for numbers without fractional parts.
	* int (4 bytes) - -2,147,483,648 to postive same number
	* Short (2 bytes) - -32,769 to 32, 767
	* long (8 bytes) - 9,223,372,036,775,808 to 9,223,372,036,854,775,807
	* byte (1byte) - -128 to 127


### Floating-Point Types 
	*float (4bytes) Approx 
	*double (8bytes) Approx
	
		** check out Robert Edward Grant - Mathatician 

### Char Type
	*literal values of type char are enclosed in single quotes. 
	*Values of types can be expressed:  
	*char someCharacter = '\u000'; 
	*char maxCharacter = '\uFFF';
	
# Boolean Type
* boolean type has two values, false and true 
	* lowercase boolean can only compare two value
	* Uppercase boolean can compare more than 2 values - takes up more storage but doable

# Big Numbers
* If the precision of the basic integer and floating-point types is not sufficent, you can turn to a couple of handy classes

* you cannot use the familiar mathematical operators such as + and * to combine big numbers 
	* BigInteger c = a.add(b);
	* BigInteger d=c.multuply(b.add(BigInteger.valueOf(2)));

# Variables 
*In Java, every variable has a type. You declare a variable by placing the type first, followed by the name of the variable 
	* int i,j; - declaration of a varable - both i and j are designated intergers **big no no, respect each variable by giving its own line**

# Initializing Variables 
* rewatch video 

** Static in Class - acting independent of the class 

* You can both declare and initialize a variable on the same line. - int vacationDays = 12;

# Constants
* Keyword final indicates that you can assign to the variable once, and then its value is set once and for all. Also known as a constant. 
	* Objects has the ability to mutate

# Operators 
* usual arithmetic operators (+, -, /, *, %)

# Mathematical Methods and Constants
* Math class contains an assortment of mathematical functions that you may occasionally need

	* double x=4
	* double y = Math.sqrt(x);
	* System.out.println(y);
	* double y = Math.pow(x,a);

# Conversions between Numeric Types 
	* byte to short, int, long, float, or double
	* short to int, long, float, or double
	* char to int, long, float, or double
	* int to long, float, or double
	* long to float or double
	* float to double
* A widening primitive converion does not lose informaiton about the overall magnitude of a numeric value 

* *int n = 12345678*
* *float f = n; (not doable)*

# Casts 
* When two values are combined with a binary operator (such as n+f where n is an integer and f is a flaoting-point value), both operands are converted to a common type before the operation is carred out. 
* Operands will become the respective type and then computing
	* *double x = 9.997;*
	* *int nx = (int) x;*

	
* DeMorgan law - 
* Java uses && for the logical "and" operator and || 
* The && and || operators are evaluated in "short circuit" fashion 
	* the second argument is not evaluated if the first argument already determines the value
	** expression1 && expression2
	
* Go over again the value expression

* Ternary Operator - Java supports the ternary ?: operator
	* condition (if true store this value) ? Expression1 : Expression2 	

# Parentheses and Operator Hierarchy


	

	
	
	