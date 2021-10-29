# Fundamentals Programming Structures in JAVA (redux)

* simple Java program
	* hello world example
* Java is case sensitive
	* class name starts begin with a letter then any other comboination of letters, digits, and underscores.
	* class names is capitalize as well as the save file
* cannot use jave reserved word to name a variable or class
* you need to make the name for the source ocde the same as the name of the public class
* whitespace is irrelevant to the java compiler


{} - starts and stop a block of code 

* A class defines all of Java code 
* main is a special method (afunction defined in a class) that is executed when a program runs
* man does't return anything, thus the void

# object stuff
* Since almost everything in jave is an object:
	* static methods are called a class, not on objects themese
	* instance methods are called on instance of the object directly 

# java environment 
* always remember to compile the code before you run it 
	* compiler and jvn

# comments
* allows us to flesh out the reasoning for the code
	* // for single line comment
	* /* and */ for multiline comments
		* cannot nest /** */ in Java
	* using a /** to start and a */ to end
	* Write a comment in the code, then flesh it out with the code

# data types 
* Java is a strongly typed language and every variable must have a declared tyype 
	* 8 primitive types in Java - how much numbers can be processed
	* 2 types of numbers (float and double) 
	* these numbers matter to the computer, and the size matter to the computer
		* 8 bytes to a bite
		* interger = 4 byte wide 
* Floating -point types
	* float = 4 bytes
	* double = 8 bytes    
* Question: the 8 primitives are types of numbers the comp can compute?  

* incorrect values can be shown due to rounding. Computing is not precise 

* Char type - everything typed out in a computer, character = number to the comp
* Types allows us to figure out what is character, numbers, or function

# Boolean Type - has two values - false and true

# Big numbers -
* bignumber. a = used to calculate bigger numbers than bytes
	* mathematical operators need a call function

# Variables 
 * You declare a variable by placing the type first, follow by the name of the variable. End in a semicolon to complete the java satement
 * always declare the type (first), variable (second), and semicolon (last)
 * declare multiple variables on a single line: 
 * int i, j; //both are integers
 * Always have to initialize your variables**
 	* int vactionDay = 12; or int vactionDay; vactionDay = 12

# Constants 
* the keyword final indicates that you can assign to the variable once, and then its value is set once and for all. Also known as a constant. 
	* example in code: final double

# operators 
* usual arithmetic operators 
* use java mathmatical function = math.pow

# Conversions between numberic types   
* 19 specific conversions on primitive types, smaller bytes can be transffered into bigger bytes, not vice versa
* How does condensing program work, with converting large files into smaller ones
* widening primitive conversion does not lose information - don't go from int --> float

* conversions in which loss of information is possible are done by means of casts 
* * Combining assignment w/ operators 
	* x+=4; same as x=x+4; - all operators works this way

# Increment and decremet operators 
* n++ adds 1 to the current value or n-- subtracts 1
* example - int n = 12; n++ ; never ++n


# Relational and Boolean Operators 
* to test for equality, use a double equal sign, == (single = is assignment)
	* 3==7 // is false not equal to 3 
	* Use a != for inequality
	* 3!=7 //true - not equal to 7 

* Java uses &&(logical true and true) for the logical "and" operator and ||(x&y true or false) for the logical "or" operator. 
* ! is the logical negation operator (flips the false to true and true to false.)
* && and || operators are evaluated in "short circuit" fashion
* Java support the ternary ?:operator
	* condition ? expression1:expression2 (if/and statement) 
	* example x < y ? x : y // gives the smaller of x and y - good for two numbers and see which is smaller or bigger based on the symbol

# Parentheses and operator hierarchy:
* Java order of operations, java order of operation exisit as well: 
	* PEMDAD??

	
#Enumerated Types 
* You can define your own enumerated type
	* enum Size {small, Medium, Large, Extra_Large};
	* Now you can declare variables of this type:
		* Size s = Size.MEDIUM;

* Learn the JAVA Primitive types
* Think Java - look for primitive types  

 