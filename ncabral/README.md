#Swift

###Description/History 
Swift is a programming language created by Apple for OSX and iOS development (Apple's desktop and mobile operating systems). It was released in 2014 as a more concise and less error prone successor to Objective-C, which was the previous programming language of choice for applications running on Apple devices. Swift supports the existing Objective-C libraries to help with backwards compatibility.

###What it is good for?
Swift is a compiled language that is best used for developing software for Apple devices. The syntax should be familiar to programmers used to used to C-style imperative languages such as C++ and Java. Development in Swift is typically done using Apple's libraries, rather than at lower levels. In fact, pointers are discouraged and not created by default, so as to reduce direct manipulation of memory by developers.

###Scoping
Like other similar languages, Swift uses static scoping.

###Typing
Swift is strongly type, and uses type-safe checking during compile time. That is to say that if a section of code is expecting a specific type of variable, passing it an incompatible type will generate a compiler error. Swift also introduces a new type called "optional" types; this allows the variable flagged as optional to be set to either a value of the particular type, or nil. This is different from the standard typing system in which, for example, an integer cannot be nil, but must be zero or some other integer.

###Functions
Functions in Swift are first class objects. They can passed to functions, returned by functions, and assigned to variables.

###Recursion
A recursive function in Swift that prints out a decreasing list of numbers:

`func printNums(num : Int)
    {
        println("\(num)")
        if num >= 0
        {
           printNums(num - 1)
        }
    }
`
    

###Arrays
An empty array can be created like this:

`var myIntArray = [Int]()
`

Elements can be added to this empty array using the .append() function of the array object.

In order to create an initialized list, the following syntax is used:

`var myIntArray: [Int] = [5, 6]`

Swift also supports the following syntax for creating an array with a specified size and initialized to the specified value:

`var myIntArray = [Int](count: 200, repeatedValue: 0)`