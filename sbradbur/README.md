R 
========
R is designed for computing and graphics related to statistics. It is an implementation of an earlier statistical programming language called S. The source code for R is written in C, Fortran, and R.  R is an interpreted, high-level language that makes handling and displaying data easy.  Unlike most statistical programming languages, it is object-oriented.  It is often used by scientists and mathematicians to analyze and visually represent large amounts of data. 

R uses lexical scoping, which uses early binding to determine scope.  
R is dynamically and strongly typed. 

Functions
========
Functions in R are set in the following way: 
functionName <- function(args) {
  statements
}

Recursion 
=========
factorial <- function(n) {
  if(x==1)
    return(1)
  else 
    return(x*factorial(x-1))
}

Arrays
=========
Vectors in R are used much like arrays are used in other languages.  A vector would be defined in the following way: 
vectorName <- c(item1, item2, ...) 
vectorName <- 0:30 would make a vector populated with the numbers 0 through 30. 
R has many build in functions to work with vectors.  Some common ones are:
sum(), mean(), sd(), sort(), plot(), and hist()
An index can be accessed using vectorName[index]

Example: 
vect1 <- c(1, 2, 3)
vect2 <- c(4, 5, 6)
vect3 <- c(vect1, vect2)
vect3[4]                  #equals 4
sum(vect3)                #equals 21
hist(vect3)               #creates a histogram of data in vector
