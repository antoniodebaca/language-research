Shane Odham
============

Scala
------

>Scala is an acronym for "Scalable Langue", it is meant to grow with you. Staring out with one-line expressions and eventually learning how to implement the language into large scale projects.

>Scala is both Object-Oriented and Functional, I know, super crazy. Every value in scala is an object and every operation is a method call. Classes, singletons, and traits are just some of the things that make it Object Oriented.

>Scala uses everything that you would traditionally expect in a functional language, including first-class functions, immutable data structures, and a preference of immutability over mutation. It is supposed to be very easy to transition from the object oriented side to the functional side.

>Scala also runs on the JVM so java and scala can be freely mixed, whether or not they are in separate projects or in the same project.

>

http://www.scala-lang.org/what-is-scala.html

History
--------

>Design for Scala started in 2001 at the EPFL (École polytechnique fédérale de Lausanne) by Martin Odersky. Odersky's previous works were working on Generic Java and the javac compiler.

>Scala was released publicly in early 2004 on the java platform, preceding a release on the .NET platform in June of 2004. .NET support was officially dropped in 2012.

>On January 17, 2011 the Scala team gained a 2.3 million dollar grant from the European Research Council. Odersky, soon after, launched Typesafe Inc., a company designed to provide commercial support, training, and services for Scala.

>

http://en.wikipedia.org/wiki/Scala_(programming_language)#History

What is Scala good for?
-------------------------

>Scala is a compiled language, it is compiled into java bytecode which runs on the JVM. This makes it able to run concurrently with java.

>Unlike java, however, scala has a very strong root in functional programming, thus side-effecting can be minimized and safer code can be potentially achieved.

Scope
--------
>Scala matches the scope rules of java, having the standard global and local stack scope. Global being accessed by the entire class (or the entire program depending on the specifications), and local scope within each code block's stack frame. These can be set with the same types inherent in java, public (accessible by other classes), private (accessible within the class created) etc.. The default for this behavior is public if not specified.

Typing
---------
>Scala is normally statically scoped but it should be noted that interesting behavior comes out of implicit typing. When using the implicit type on an object. Scala tries to figure out the type that should be given to an implicit object, if there are several eligible arguements that match the parameter's type, then the most specific one will be chosen using something called the rules of static overloading resolution.

Functions
-----------
>Functions in scala can be used in the same way they are used in Java. Scala treats functions as objects, the function type is a class. This is the same as java as far as I can tell since method calls in java are treated as objects themselves.

Recursion Example
-------------------
>
def sum(x:List[Int]): Int = {
	if(x.isEmpty) 0
	else x.head + sum(x.tail)
}

Using Arrays
--------------
>val numbers = Array(1, 2 ,3 ,4)     //Declaring the array

>val first = numbers(0)				//read the first element

>numbers(3) = 100					//replace the 4th element with 100



