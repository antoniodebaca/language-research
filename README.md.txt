
Ruby
-----------------------------------------------------
Quick description/history of the language you chose
-----------------------------------------------------
Ruby is a dynamic, reflective, object-oriented, general-purpose programming language. It was designed and developed in the mid-1990s by Yukihiro "Matz" Matsumoto in Japan. According to its authors, Ruby was influenced by Perl, Smalltalk, Eiffel, Ada, and Lisp. It supports multiple programming paradigms, including functional, object-oriented, and imperative. It also has a dynamic type system and automatic memory management.

source: http://en.wikipedia.org/wiki/Ruby_%28programming_language%29

-----------------------------------------------------
What it is good for (why would someone use it?) 
-----------------------------------------------------
¡öIs it a scripting language?
Yes, Ruby is a Object-Oriented scripting language.
¡öCompiled?
Yes, Ruby is compiled. JRuby and Rubinius first compile the Ruby code to byte code, and later execute it.
¡öLow-level?
Ruby is extremely high level programming language and completely object-oriented, 
and it has no primitives (outside of the runtime implementation) and everything can be treated as an object.

-----------------------------------------------------
An explanation of the scope rules
-----------------------------------------------------

--An explanation of the typing system

Ruby is dynamically AND strongly typed.
1. why ruby is dynamic typed.
Example of a language statically typed :
int x;
x = 3;
x = "hello"; //ERROR!Example of a language dynamically typed :

x = 3
x = "Transformers seems to be a boring movie"
x = :why_are_we_here
x = /is this a reg ex/
x = "enough already... I think we understand"

Dynamic typing is a mechanism where the type of a variable can change and be resolved on the fly at the exact moment it gets parsed by the interpreter.

Static typing is a mechanism where the type of a variable is resolved in advance by the interpreter/compiler. With statically typed languages, you cannot say that x is a string and, a few lines after, that it is an integer.

2. why ruby is strong typed.
In ruby, we can do :

a = "3"
b = a + "hi!" #result : "3hi!"

but we cannot do :

a = "3"
b= a + 3 #Ruby won't like that


--An explanation of how functions can be used

Ruby methods are used to bundle one or more repeatable statements into a single unit.

Method names should begin with a lowercase letter. If you begin a method name with an uppercase letter, Ruby might think that it is a constant and hence can parse the call incorrectly.

Methods should be defined before calling them, otherwise Ruby will raise an exception for undefined method invoking.



# A simple method   
def hello  
  'Hello'  
end  
#use the method   
puts hello  
  
# Method with an argument - 1   
def hello1(name)   
  'Hello ' + name   
end  
puts(hello1('satish'))   
  
# Method with an argument - 2   
def hello2 name2   
  'Hello ' + name2   
end  
puts(hello2 'talim') 


The output is:

>ruby p008mymethods.rb   
Hello   
Hello satish   
Hello talim   
>Exit code: 0 



--A code sample showing how to use recursion

def countdown(n)
  return if n.zero? # base case
  puts n
  countdown(n-1)    # getting closer to base case 
end               

countdown(5)
5
4
3
2
1


--A code sample showing how to use arrays

nums = Array.[](1, 2, 3, 4,5)


3.Merge any new changes from my repo into yours

4.Deliverable One Send a pull request