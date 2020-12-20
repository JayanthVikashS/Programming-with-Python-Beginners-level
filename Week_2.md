## Comments

Comments start with a hash character (#) and allow you to document your code. Comments are ignored when code is executed.

+	Comments

**Sample program:**

**Comments are not executed :**

    # This is a comment in my code it does nothing
    # print('Hello world')
	# print("Hello world")
	# No output will be displayed!

## Strings

Python can store and manipulate strings. Strings can be enclosed in single or double quotes. There are a number of string methods you can use to manipulate and work with strings
*	strings
*	string methods

Converting to string values
*	str

**Sample program:** 

**String in  Variables:**

    # You can store strings in variables
	first_name = 'Susan'
	
	# The variable can then be used later in your code
	print(first_name)

## Numeric values

Python can store and manipulate numbers. Python has two types of numeric values: integers (whole numbers) or float (numbers with decimal places)

*	numeric types

Converting to numeric values
*	int
*	float

**Sample program:** 

**Combining Strings and numbers:**

    days_in_feb = 28 
    # The print function can accept numbers or strings
    
    print(days_in_feb)
 
    # The + operator can either add two numbers or it can concatenate two strings
    # it does not know what to do when you pass it one number and one string
   
    # This line of code will cause an error
    
    print(days_in_feb + ' days in February')
 
    # You need to convert the number to a string to display the value
    # This line of code will work
    
    print(str(days_in_feb) + ' days in February')

