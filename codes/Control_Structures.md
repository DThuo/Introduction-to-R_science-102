# Control Structures in R

Control structures manage the flow of code execution in R, useful for decision-making and loops.

## 1. `if`, `else if`, `else`

#The `if`, `else if`, and `else` statements control the flow based on conditions. 
### Syntax:
```r
if (condition) {
    # code if TRUE
} else if (another_condition) {
    # code if TRUE
} else {
    # code if all FALSE
}

####Example
x <- 10
if (x > 0) print("positive") else if (x == 0) print("zero") else print("negative")

## 2. for Loop
for (variable in sequence) {
    # code for each item
}

####Example
for (i in 1:5) print(i)

## 3. While loop

while (condition) {
    # code while TRUE
}

###Example 
x <- 1; 
while (x <= 5) { print(x); x <- x + 1 }

#### 4.repeat loop
repeat {
    # code
    if (condition) break
}

###Example
x <- 1; repeat { print(x); x <- x + 1; if (x > 5) break }

#### 5. ifelse

ifelse(test, yes, no)
 
 x <- 1:5; ifelse(x %% 2 == 0, "Even", "Odd")










![cps](https://github.com/user-attachments/assets/b4618b09-74b0-4f0d-bae8-058ec1655cd3)


















