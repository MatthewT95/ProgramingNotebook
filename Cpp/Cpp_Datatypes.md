# Datatypes
* [Primitives](#Primitives)
	* [Boolean](#boolean)
## Primitives
| Datatype | Keyword | Range | Description|
|---|---|---|---|
| [Boolean](#boolean) | bool | Integer 0 or 1 | Holds value representing true or false|
### Boolean
A Boolean datatype has a size of one byte. Its value represents a state of 'true' or 'false'. 
This value is represented by value of one for true and zero  for false.
It is declared using the keyword 'bool'.
A bool value can be set using the keywords 'true' or 'false'.
#### Declaring and assigning values to Boolean
```cpp
	bool status; //boolean declared named status
	status = true; //Setting boolean to true using keyword
	status = false; //Setting boolean to false using keyword
	status = 1; //Setting boolean to true using number > 0
	status = 0; //Setting boolean to false using number <= 0
```
#### Checking value of Boolean
```cpp
	bool status = true;
	//Checks if bool is true
	if (status){...}
	if (status == true){...}
	if (status != true){...}
	if (status == 1){...}
	if (status != 0){...}
	//Checks if bool is true
	if (!status){}
	if (status == false){...}
	if (status != true){...}
	if (status == 0){...}
	if (status != 1){...}
```
#### Printing Boolean values to console with std::cout
```cpp
	bool statusA = true;
	bool statusB = false;
	
	//Default is 'Print boolean as 1 or 0'
	std::cout << statusA << " " << statusB << std::endl;
	
	std::cout << std::boolalpha; //set flag 'Print boolean as true or false'
	std::cout << statusA << " " << statusB << std::endl;
	
	std::cout << std::noboolalpha; //set flag 'Print boolean as 1 or 0'
	std::cout << statusA << " " << statusB << std::endl;
```
	
	Output:
	1 0
	true false
	1 0
### Character

### Integer
The Integer datatype has a size of four bytes. Its value represents a whole number.
and can be between -2147483648 to 2147483647. It's declared using keyword **int**.
You can modify the range and size by using the keywords **unsigned**,**short** and **long**. 
The **Short** reduces it size to two bytes.   
The **Long** sets the size to four bytes.   
The **Unsigned** restricts value to positive values.
#### Declaring and assigning values to Boolean

### float

### double floating point

### Valueless

### Wide Character wchar_t
