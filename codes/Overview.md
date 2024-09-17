# Introduction to R and RStudio

## What is R?

R is a programming language and environment commonly used in statistical computing, data analysis, and graphical representation. It is highly extensible and used by data scientists and statisticians.

## What is RStudio?

RStudio is an integrated development environment (IDE) for R. It provides a user-friendly interface with features like syntax highlighting, debugging, and project management.

### Why Learn R?

- Open-source and free
- Powerful data analysis and visualization tools
- Large community and vast resources
- Easy to learn

## Installing R and RStudio

### Step 1: Installing R
Follow the instructions for downloading and installing R from the official CRAN site:  
[R Download](https://cran.r-project.org/)

### Step 2: Installing RStudio
Download and install RStudio from the official website:  
[RStudio Download](https://rstudio.com/products/rstudio/download/)

Once you have installed both, open RStudio to get started.


### Sample Exercise: 01_RStudio_Basics.md

```markdown
# RStudio Basics - Exercise

In this exercise, you will explore the basic RStudio interface and commands.

## Task 1:

Write and Run Simple Code

1. Open RStudio.
2. In the script pane, write the following:
   ```r
   # Basic math in R
   5 * 3 ---multiplication

   sqrt(25) ---squareroot

##Task 2:

Create a variable

       1. Here we will assign result of an expression to a variable
 
              result <- 5 *3

              result

       2. Now view the result variable in the environment pane.

Write and Run Simple Code

1. Open RStudio.
2. In the script pane, write the following:
   ```r
   # Basic Arithmetic Operations in R
   
# multiplication
   5 * 3 
   
#Squareroot
   sqrt(25) 
   
# Division

9 / 3  

# Exponentiation
2^3  

# Modulus (remainder of division)
7 %% 3  

# Integer division (quotient)
7 %/% 3  


##Task 2:

Create a variable

       1. Here we will assign result of an expression to a variable
 
             x <- 10
             
             y <- 5t

       # Print the value of a variable
             
             print(x) 



##Data Types in R
R supports different types of data: 

-Numeric: Numbers (e.g., 1, 2.5, -4)
-Character: Strings (e.g., "Hello", "R")
-Logical: TRUE or FALSE


# Numeric
num <- 42

# Character (strings)
name <- "R Language"

# Logical (Boolean)
flag <- TRUE

# Check the data type using class()
class(num)    # Output: "numeric"
class(name)   # Output: "character"
class(flag)   # Output: "logical"



# Create a numeric vector
numbers <- c(1, 2, 3, 4, 5)

# Create a character vector
names <- c("Alice", "Bob", "Charlie")

# Access elements in a vector (indexing starts from 1)
numbers[2]  # Output: 2

# Modify an element in a vector
numbers[3] <- 10
numbers  # Output: 1, 2, 10, 4, 5

# Logical indexing
numbers[numbers > 3]  # Output: 10, 4, 5






Once done, feel free to experiment with more R commands.






























