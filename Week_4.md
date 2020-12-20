## Loops

**For loops**

For loops takes each item in an array or collection in order, and assigns it to the variable you define.

**Sample Program:**

    names = ['Christopher', 'Susan']
    for name in names:
        print(name)

**While loops**

While loops perform an operation as long as a condition is true.

**Sample Program:**

    names = ['Christopher', 'Susan']
    index = 0
    while index < len(names):
        name = names[index]
        print(name)
        index = index + 1

## Functions

Functions allow you to take code that is repeated and move it to a module that can be called when needed. Functions are defined with the def keyword and must be declared before the function is called in your code. Functions can accept parameters and return values.
+	Functions

        def functionname(parameter):
           # code to execute
           return value

## Function parameters

Functions allow you to take code that is repeated and move it to a module that can be called when needed. Functions are defined with the def keyword and must be declared before the function is called in your code. Functions can accept one or more parameters and return values.
+	Functions

        def function_name(parameter):
            # code to execute
            return value

Parameters can be assigned a default value making them optional when the function is called.

        def function_name(parameter=default):
           # code to execute
           return value

When you call a function you may specify the values for the parameters using positional or named notation

        def function_name(parameter1, parameter2):
           # code to execute
           return value

    # Positional notation pass in arguments in same order as parameters are declared
    
    result = function_name(value1,value2)

    # Named notation
    
    result = function_name(parameter1=value1, parameter2=value2)

## Conclusion:

Getting started with a new environment can be challenging, especially when you literally don't even speak the language.I didn’t dig into specific frameworks, but I help get youself ready to start exploring on your own. By now you can start learning your core Python concepts you'll need as you begin your journey into web development on popular frameworks such as Django and Flask, use AI services such as Cognitive Services, or even machine learning.

