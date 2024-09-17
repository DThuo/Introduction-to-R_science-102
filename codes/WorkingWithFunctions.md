# Working with Functions in R

#Functions allow you to reuse code, making your scripts more modular and efficient. In R, functions are created using the `function` keyword.

## Basic Function Syntax

### Syntax:
```r
function_name <- function(arg1, arg2, ...) {
    # Code block
    return(value)  # (Optional) Returns a result
}


#function_name: The name you assign to the function.
#arg1, arg2, ...: Arguments (inputs) that the function takes.
#return(): Returns the result of the function (optional, R automatically returns the last expression if return is not used).

##Example

# A function to calculate the square of a number
square <- function(x) {
    return(x^2)
}

# Calling the function
square(4)  # Outputs: 16


## Functions can return values using the return() statement, or implicitly return the last evaluated expression.

# A function that multiplies two numbers
multiply <- function(x, y) {
    product <- x * y
    return(product)  # Explicitly returning the product
}

# Calling the function
multiply(3, 4)  # Outputs: 12

#######Example with Implicit Return:

# A function that divides two numbers
divide <- function(x, y) {
    x / y  # No explicit return needed, R returns the last expression
}

# Calling the function
divide(10, 2)  # Outputs: 5

#Function without Arguments

#Functions can be created without arguments if the task they perform does not depend on input.

# A function that prints a greeting
greet <- function() {
    print("Hello, World!")
}

# Calling the function
greet()  # Outputs: "Hello, World!"


#Nested Functions
#Functions can call other functions within them, allowing more complex operations.

# A nested function to calculate the area of a rectangle
area <- function(length, width) {
    calculate_area <- function(l, w) {
        return(l * w)
    }
    return(calculate_area(length, width))
}

# Calling the nested function
area(5, 3)  # Outputs: 15



#Variable Scope in Functions
#R uses lexical scoping, which means variables defined inside a function are local to that function.


# Function with local variables
scoped_function <- function() {
    x <- 10  # Local variable
    return(x)
}

# Calling the function
scoped_function()  # Outputs: 10
print(x)  # Error: object 'x' not found (x is local to scoped_function)

#Handling Multiple Return Values
##R can return multiple values from a function as a list.

# Function to return sum and product of two numbers
sum_and_product <- function(x, y) {
    sum <- x + y
    product <- x * y
    return(list(sum = sum, product = product))
}

# Calling the function
result <- sum_and_product(3, 4)
print(result$sum)      # Outputs: 7
print(result$product)  # Outputs: 12






























