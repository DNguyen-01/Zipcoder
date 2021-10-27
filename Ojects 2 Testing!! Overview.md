# Objects 2 Testing!! Overview

* Obj today: How do do testing in BlueJ

* **Class** - describes a category or thing
	* **Object** - is an instance of a class and has its own settings
	* Object creates a blue print of the Class 

# Objects Instance:
* Identity, State, & Behavior
* **Variables** - Java is a strong type computer language
		* Primative data type (i.e. boo, variables, int) or Object reference (triangles, addressess, age)
	* Strongly type computer language has to 3 things that nees to be done
	* declare, initialize and Use 
		* int total = O; - Declare & Initialize
		* total = 5584939 - Use	 
		* running total =  time + distance - Use
	* Declare, Initialize & Use
		* Address (Class is always capitalize) address 1;
		* address1 = new Address();
		* currentPostalCode=address1.getPostalCode();
	* Null - when a class is undefined
		* Address address1; - Undefined class = Null
			* If a class has no mutator methods(such as String or LocalDate),
			* This can be useful if you dont yet have an object for date to refer to, or if you want to indicate a special situation, such as an unknown date.(Null can be used a place holder until you have a class)

* Dotted line in BlueJ - Person --> Address
	* Embedded Class 
	* Objects are like an index card, and in coding objects can contain string on each oject
	* Class locates the code that is working with it 

## Test Driven Development - TDD
* is all about writing "clean code that works." 
* TDD grew out of Extreme Programming, most testing comes after the coding process or periodaclly during the coding process.
	* Gives you confidence that your code works correctly
	* helps you quickly find bugs
	* focuseses on the design task
	* helps you completely understand the requirements for your code 	  
		* Helps with taking code from GitHub and applying it to your system
* Unit test is not exhaustive - cannot cover all the codes, only covers percentage testing
	* can have more testing than coding   

## Unit Testing in BlueJ Demo - Test Staffing

* Create a test class for staff - 
	* right click on staff
	* **create test class**
	* Left hand corner (up arrow) 
	* Right click - create test method
	* Specify Name - _testSetRoom_ or any specific class you want to test
	* Unit Test - Create setTest Method (notice its recording)
		* create a new staff object in Staff class
		* Set room to *123*
		* End 
	* Run test

### LAB
* in Lab in portal - 
	* doc - Chapter 2 - read over and follow the instructions in the chapter to recreate/changing the ticket machine
	* First two labs is to complete the lab, not quite emphasises on the github commit 