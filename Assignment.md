



# Data Science with R: Assignment Task

## 1. BASICS

### 1.1. Variables in  R

What is the value of  " B " after running these command?																													    [2]

```R
a <- 5.0
c <- 10
t <- 12
B <- a+c/t
```

What type of vector do you get in each of the following?																														   [4]

```R
vec_1 <- c(44, 5, 0, "k")
vec_2 <- c(1, 2, 3, FALSE)
vec_3 <- c("a", "b", "c", TRUE)
vec_4 <- c(1, 2, 3, "4")
```

### 1.2. Conditional subsetting

Consider the following vector:

```R
vec <- c(141.2741, 141.8392, 140.5730,NA, 141.3571, 139.8689, 
         137.9384, NA,139.6620, 138.2521, 138.8635, 141.3885, NA)
```

#### 1.2.1. Create a vector vec_1 with no missing values using conditional subsetting and explain your code													   [3]

#### 1.2.2. Create a vector of indexes of missing values using conditional subsetting and explain your code   												     [3]

#### 1.2.3. Write a code to determine how many missing values are in vec.																													      [2]

#### 1.2.4. Write a R code to create a data frame which contains details of 3 students as follows:	   															  		[4]

- Name
- Surname
- Age
- Gender

## 2. Functions in R

### 2.1. Create  a function which returns a mean of an input vector and explain your code 																						  [4]

### 2.2. Create a function which take  no inputs , it reads  a Titanic .csv file and returns its content and explain your code. 								  [3]

## 3. Conditionals and Loops

#### 3.1. Write a function that take an input below and returns a transformed vector below into 1 when its element is male and 2 when its female using ifelse.														     																																						  [8]

```R
g <- c("MALE","FEMALE","FEMALE","MALE","FEMALE","MALE","MALE","FEMALE", "MALE","MALE","FEMALE","MALE","MALE",
"FEMALE","MALE","MALE","MALE")
```

3.2. Generate x from normal distribution and sample with replacement "M" and "F" for male and female respectively by running the code below. 																						 

```R
x <- rnorm(1000, 120, 5)
y <- sample(c("M","F"),size = 1000, replace = TRUE)
```

3.2.1. Use the "cbind " function in R to create one dataset and assign it to df. 																						  [2]

3.2.2. Convert df from 3.2.1 into a data.frame   																																		  [2]

3.2.3. Write a code using tidyverse to compute a number of males ("M") and females ("F")  in 3.2.1														[3]

3.2.4. Create a bar plot using ggplot to visualize your results in 3.2.3																										[5]

3.2.5. Use mutate function to add sum of x per "M" and "F" and plot the results using sum of x per "M" and "F".								     [5]

























#  

