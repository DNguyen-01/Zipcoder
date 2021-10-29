What is a String

* capital letter is an object
* It is a wrapper for an array of characters
	* Integer y = new Integer(x);  - Integer is a wrapper for Int - should look like so for a wrapper class
* Wrapper class takes a primiateive class, and exposes it to method manipulation
	* String starts and end w/ " "
	* String is immutable - cannot be manipulated
	* Re-assignment - can create the illusion of string mutation thru re-assignment
		* s = s.toUpperCase(); - creating a copy of the string, or else it will be lost to the class. to persist the change of upper casing, we must reassign the value to the copy
* Constructor can take: 
	* String
	* StringBuilder** Main subject of this class 
	* StringBuffer

* \n = new line modifier
* spaces are considered a character
* .charAt(int index) = trying to figure out the particular character in a specific index you use "int index"

* SubString Method - calling out specific location of the code and will print out the location and beyond - see video**

* .Trim = removes white spaces when printing
* .compareTo(String otherString)      
* String.join(delimiter) 
	* Don't use == to compare - java will not concat - be explicit 
* If Statement for a given value