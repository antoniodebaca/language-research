***History
C# was originally named as "Cool" (C-like Object Oriented Language", and created by the team formed by Anders Hejlsberg from Microsoft. It was claimed to be the imitation of Java by james Gosling who was the creator of Java programming language.

***What it is good for
C# is simple, general-purpose object-oriented language. It has different implementaion of generic classes than Java and it has several major features to accommodate funtional-style programming similar to closures. It ca be run on multiple platforms including windows, unix, linux and solaris. 

***Other info
C# is compiled, high-level languagge and uses static scoping. It is strongly-typed language.

***Funtions
The funtions are treated as first class object and declaration is similar to Java:
<visibility> <return type> <name>(<parameters>)
{
	<function code>
}
Calling a function- name();

***Recursion
public long Factorial(int value){
if (n==0)
	return 1;
return n*Factorial(n-1);
}


***Arrays
Declaration and initiation of arrays

int[] numbers;
numbers  = new int[15]; // single dimetional array of size 15

int[,] numbers;
numbers = new int[5,10]; // multidimentional array (different 						from java becuase uses int[,] while 						declaring
int[,,] numbers= new int [5,10,15]; // 3 dimentional

int[][] numbers = new int [5][]; // delcaring and initializing 							array of array

for (int i = 0; i < numbers.Length; i++){
	numbers[i] = new int[i+2];
} // creating the array of array (jagged array)


// We can also mix multidimentional array and jagged array

int[][,] numbers; // single dimentional array of 2-dimentional 					array

