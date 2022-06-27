
#[WEEK 01](https://github.com/cassanogt/core-code-from-scratch-readme/blob/main/Week%2001/README01.md)

### Week challenges (Tuesday) 💻

  Base on this reading and this video, create an explanation about Interpreted And Compiled Programming Languages in your README

  Is Java compiled or interpreted, or both?, check the sources and answer the question in your README

  Pseudocode Currency Converter exercise

  Learn about High and Low level languages

### Week challenges (Wednesday) 💻

  Your date of birth in the matrix? exercise
  MIPS exercise

### Week challenges (Thursday) 💻

  Print special numbers exercise
  Bad Code exercise
  Bad Code 2 exercise
  Follow Git Course



1. [2022 04 05 Week Challenges(Tuesday)](#2022-04-05-Week-Challenges-Tuesday)
	1. [Interpreted And Compiled Programming Languages](#1-Interpreted-And-Compiled-Programming-Languages)
	2. [Is Java compiled or interpreted, or both?](#2-Is-Java-compiled-or-interpreted,-or-both?)
	3. [Pseudocode currency converter](#3-Pseudocode-currency-converter)
2. [2022 04 06 Week Challenges(Wednesday)](#2022-04-06-Week-Challenges-Wednesday)
	1. [Your date of birth in the matrix? exercise](#1-Your-date-of-birth-in-the-matrix?-exercise)
	2. [MIPS exercise](#2-MIPS-exercise)
3. [2022 04 07 Week Challenges(Thursday)](#2022-04-07-Week-Challenges-Thursday)
	1. [Print special numbers exercise](#1-Print-special-numbers-exercise)
	2. [Bad Code exercise](#2-Bad-Code-exercise)
	3. [Bad Code 2 exercise](#3-Bad-code-2-exercise)
4. [2022 04 08 (Friday)](#2022-04-08-Friday)






### 1. Interpreted And Compiled Programming Languages

A resume about them:

Interpreted Languages run through a program line by line and execute each command. 
they were once significantly slower than compiled languages. But, with the development of just-in-time compilation, that gap is shrinking.
the source code is not directly translated by the target machine. Instead, a different program, aka the interpreter, reads and executes the code.


Compiled Languages are converted directly into machine code that the processor can execute. As a result, they tend to be faster and more efficient to execute than interpreted languages. 
They also give the developer more control over hardware aspects, like memory management and CPU usage.
Compiled languages need a “build” step – they need to be manually compiled first. You need to “rebuild” the program every time you need to make a change. 


Most programming languages can have both compiled and interpreted implementations – the language itself is not necessarily compiled or interpreted.
However, for simplicity’s sake, they’re typically referred to as such. that like as intermediate languages.

Python, for example, can be executed as either a compiled program or as an interpreted language in interactive mode. On the other hand, most command line tools, CLIs, and shells can theoretically be classified as interpreted languages.


Advantages and disadvantages

Advantages of compiled languages
	Programs that are compiled into native machine code tend to be faster than interpreted code. 
	Source code is private
	Ready to run

Disadvantages of compiled languages
	Additional time needed to complete the entire compilation step before testing
	Platform dependence of the generated binary code
	Inflexible

Advantages of interpreted languages
	They tend to be more flexible, and often offer features like dynamic typing and smaller program size. 
	Easier to debug
	Simpler to test

Disadvantages of interpreted languages
	The most notable disadvantage is typical execution speed compared to compiled languages.
	Source code is public
	Interpreter required



### 2. Is Java compiled or interpreted, or both?
Java is a compiled and interpreted language, because is first compiled into bytecode which JRE can understand. ByteCode is then interpreted by the JVM making it as interpreted language.


### 3. Pseudocode currency converter

	a.	Starting point: START
	b.	Set CostBitcoin
		webiste: visite https://usd.es.currencyrate.today/btc and update the cost of the bitcoin
	c.	Set AmountDollars
	d.	Set ConvertDollars 
	e.	Write: Ask about amount to convert
	f.	Read: Input: insert a amount
	g.	Set AmountDollars = Input
	h.	ConvertDollars = CostBitcoin * AmountDollars
	i.	Write: the AmountDollars is in BTC
	j.	End Point.
	
## 2022 04 06 (Wednesday)

### 1. Your date of birth in the matrix?

I was born in 1978 for that reason my binary birth year is 11110111010

### 2. MIPS

Base on the guide and the examples of the low-level language, create the following

	1. Create a program to add two numbers given by the user

### Script

.data </br>
        number1: .asciiz "\nAdd First number: \n"  </br>
        number2: .asciiz "\nAdd Second number: \n"  </br>
        result_message: .asciiz "\nthe sum is: "  </br>
  .text </br>
        main: </br>
              li $v0, 4 </br>
              la $a0, number1 </br>
              syscall </br>
               </br>
              li $v0, 5 </br>
              syscall </br>
               </br>
              move $t0, $v0 </br>
               </br>
              li $v0, 4 </br>
              la $a0, number2 </br>
              syscall </br>
 </br>
              li $v0, 5 </br>
              syscall </br>
 </br>
              move $t1, $v0 </br>
 </br>
              li $v0, 1 </br>
              move $a0, $t0 </br>
              syscall </br>
               </br>
              add $t2, $t0, $t1 </br>
               </br>
              li $v0, 4 </br>
              la $a0 result_message </br>
              syscall </br>
 </br>
              li $v0, 1 </br>
              move $a0, $t2 </br>
              syscall </br>

	2. Create a program that display your name

### Script

.data </br>
        message: .asciiz "\nHeber Daniel Sánchez Hernández\n" </br>
  .text </br>
        main: </br>
              li $v0, 4 </br>
              la $a0, message </br>
              syscall </br>
 </br>



## 2022 04 07 (Thursday)

### 1. Print Special Numbers

In this exercise you must use an iterative flow control to be able to print all the even numbers in the range of numbers from 0 to 100. Remember that you should not print each number, you should use a flow control structure to perform the exercise
```Javascript
Script 
let str = ''; 
for (let i = 0; i <= 100; i+= 2) { 
    str = str + i +"\n"; 
} 

console.log(str); 
```

### 2. Bad Code

The code shown below is not working in the right way, as a task you must find the error made by the developer who programmed this code and correct it, for this exercise you must explain what the error is and place the correct code

```Javascript
Script
var cond = false; 
if ((cond = true)) { 
  console.log('The cond variable is true'); 
} else { 
  console.log('The cond variable is false'); 
} 
```

the programer inicialized the variable cond like a boolean, and this variable does not compared with aritmetic comparators. 
is a rule for ECMAScript to use 3 = in these cases.

```Javascript
Script
var cond = false; 
if ((cond == true)) { 
  console.log('The cond variable is true'); 
} else { 
  console.log('The cond variable is false'); 
} 
```

### 3. Bad Code 2

You must create the code that follows the following logic, if the given number is 100, take this number as special and show the following message: "This is a special number!", but if the number is less than 1000, multiple of 10 and different from 100, you must show the following message: "This number is almost special". if none of the given conditions are met show the following message: "Just a regular number". Another developer was trying to program the logic, but apparently couldn't, you need to fix the code to work properly

```Javascript
\\Script
var n = 100; 
if (n == 100) { 
  console.log('This is a special number!'); 
} 
if (n < 1000) { 
  console.log(''); 
} else { 
  console.log('Just a regular number'); 
} 
if (n % 10 == 0) { 
  console.log('This number is multiple of 10');
} 
``` 
 
 Before I fixed the code this work properly, the code is the next
 
 ```Javascript
 \\Script
 var n = 100; 
 
if (n == 100) { 
  console.log('This is a special number!'); 
} 
else if (n < 1000 && n % 10 == 0) { 
  console.log('This number is almost special'); 
}  
else { 
  console.log('Just a regular number'); 
} 
```

### 4. Git Course


## 2022 04 08 (Friday)
