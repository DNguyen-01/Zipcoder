# Object Oriented Programming Intro

* What is procedural programming? 
	* structured programming conisists of desining set of procedure to solve a program
* Why we use it - small problems easily resolved w/ a procedural implementation
		* As we get more complex, we need a more complex approach
	* drawbacks: scale poorly, as it grows in size:
		* harder to read
		* harder to de-bug
		* maintance becomes difficult
		* testing a single aspect becomes nearly impossible
		* behavior becomes tightly-coupled - the behavior of each code is tied to the previous one
* Why we use OOP?
	* large problems can be scaled down
	* allows to view code details within the context of a specific object (i.e. game = car is an object, track is an object, seat is an object) 
	* Allows you to test each individual aspect of the object and not the entire game when the code fails
	* OOP = program is made of objects
	* object has specific functionalities, which users acess via the object's **methods**
	* OOP paradigm suggests that a program:
		* identiy structure
		* then which item will be used
* 3 aspect of an object
	* identiy - what is the location?
		* how is the obj distinguished from the other objects of the same type? (e.x. two same honda civic)
	* state - what does it store?
		* What is the value of the internal obj this obj contains? (i.e. two cups, differnet contents)
	* Behavior - How does it act?
		* What services or actions this object cn perform
* Classes
	* template/blue print from which obj are mde
		* cookie cutter to a cookie
		* classification of an object
	* Class naming conventions - 
		* class name must begin with a letter followed by letter, digits, and underscores
		* convention, class names start w/ a capital letter
			* you cannot use. java reserved word to name a variable or class (ie. null)
		* Whitespace is irrelevant to the Java compiler  
* Encapsulation
	* combining data (variables) behaviors (methods) into one package from the users of the object
	* Classes encapsulate several data-fields and behaviors into a single entity
	* Encapsulation combine class-members (methods and variables) in a single scope
		* see video for example  
* Instance-fields
	* an instance-filed, or instance-variable are representative of the properties or attrubutes of a CLASS
	* Value of the field is the Instance-State

* Instance Methods 
	* behaviors of an object are made available to users via obj methods
	* Keep your method clean to make it easier to identify (i.e. method speak = nameSpeak)
* Access Modifiers: 
	* Public - method can be called from any class
	* Private - can only be called from within the same class
	* Protected - method can only be called from classes in the same package or subclasses
	* default (Package private) - method can only be alled from classess in the same package (achieved when ommited public/private/protected)
* Optional Specifiers 
	* static: used for class methods: **System.out.println(...)**
	* abstract: used when not providing a method body
	* final: used when a method is not allowed to be overrideen by a subclass
	* synchronized: used in concurrency
* Method Declaration: Method Name - how we identify and call method at hand
	* reserved word or numbers, $, _ string
* Parameter List: Method does not need to contain parameters
	* Variables should be seperated via commas not semicolon
 * Method Declaration: Optional exception list
 * Method Declaration: Method Body - "concrete body" - method w/ a body not abstract
 * Varargs: Method may use a vararg parameter (variable argu- ment) as if ti was an array. - ** only have one vararg parmeter per method
* Instance-Variables (Fields)
	* accessors (getters)
	* mutators  (Setters)

* Static Methods and Fields
	* static method does not require an instance of a class - do not have to create an instance of. class to call it
	* means they belong to the class not the instance
	* for utility or helper methods that don't require any object state
	* for state that is share by all insances of a class like a counter (i.e. turtle counter)  
	
* An instance method can call a static method but a static method cannot call an instance method
* Static Variables 
	* Constants are static variables that meeant to never change during the program - "final" the value it holds is the final thing it can hold
		* variable is the cup holder - super glue is the "final" thats = thats the last cup itll hold, but the state of the cup can be modified 

** follow-up via video recording  

* Setters = using void to set the class