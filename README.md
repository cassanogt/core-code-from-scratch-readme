<h1 align="center">core-code-from-scratch-readme</h1>
<h1 align="center">2022 April - June</h1>
 
 ## Index
 
 <h2>Week 1</h2>

1. [2022 04 05 (Tuesday)](#2022-04-05-Tuesday)
	1. [Interpreted And Compiled Programming Languages](#1-Interpreted-And-Compiled-Programming-Languages)
	2. [Is Java compiled or interpreted, or both?](#2-Is-Java-compiled-or-interpreted,-or-both?)
	3. [Pseudocode currency converter](#3-Pseudocode-currency-converter)
2. [2022 04 06 (Wednesday)](#2022-04-06-Wednesday)
	1. [Your date of birth in the matrix](#1-Your-date-of-birth-in-the-matrix)
	2. [MIPS](#2-MIPS)
3. [2022 04 07 (Thursday)](#2022-04-07-Thursday)
	1. [Print special numbers](#1-Print-special-numbers)
	2. [Bad Code](#2-Bad-Code)
	3. [Bad Code 2](#3-Bad-code-2)
4. [2022 04 08 (Friday)](#2022-04-08-Friday)


 <h2>Week 2</h2>


1. [2022 04 18 (Monday)](#2022-04-18-Monday)
	1. [Interpreted And Compiled Programming Languages](#1-Interpreted-And-Compiled-Programming-Languages)
	2. [Is Java compiled or interpreted, or both?](#2-Is-Java-compiled-or-interpreted,-or-both?)
	3. [Pseudocode currency converter](#3-Pseudocode-currency-converter)
1. [2022 04 19 (Tuesday)](#2022-04-19-Tuesday)
	1. [Interpreted And Compiled Programming Languages](#1-Interpreted-And-Compiled-Programming-Languages)
	2. [Is Java compiled or interpreted, or both?](#2-Is-Java-compiled-or-interpreted,-or-both?)
	3. [Pseudocode currency converter](#3-Pseudocode-currency-converter)
2. [2022 04 20 (Wednesday)](#2022-04-20-Wednesday)
	1. [Your date of birth in the matrix](#1-Your-date-of-birth-in-the-matrix)
	2. [MIPS](#2-MIPS)
3. [2022 04 21 (Thursday)](#2022-04-21-Thursday)
	1. [Print special numbers](#1-Print-special-numbers)
	2. [Bad Code](#2-Bad-Code)
	3. [Bad Code 2](#3-Bad-code-2)
4. [2022 04 22 (Friday)](#2022-04-22-Friday)

<h2>Week 3</h2>


1. [2022 04 25 (Monday)](#2022-04-25-Monday)
	1. [Interpreted And Compiled Programming Languages](#1-Interpreted-And-Compiled-Programming-Languages)
	2. [Is Java compiled or interpreted, or both?](#2-Is-Java-compiled-or-interpreted,-or-both?)
	3. [Pseudocode currency converter](#3-Pseudocode-currency-converter)
1. [2022 04 26 (Tuesday)](#2022-04-26-Tuesday)
	1. [Interpreted And Compiled Programming Languages](#1-Interpreted-And-Compiled-Programming-Languages)
	2. [Is Java compiled or interpreted, or both?](#2-Is-Java-compiled-or-interpreted,-or-both?)
	3. [Pseudocode currency converter](#3-Pseudocode-currency-converter)
2. [2022 04 27 (Wednesday)](#2022-04-27-Wednesday)
	1. [Your date of birth in the matrix](#1-Your-date-of-birth-in-the-matrix)
	2. [MIPS](#2-MIPS)
3. [2022 04 28 (Thursday)](#2022-04-28-Thursday)
	1. [Print special numbers](#1-Print-special-numbers)
	2. [Bad Code](#2-Bad-Code)
	3. [Bad Code 2](#3-Bad-code-2)
4. [2022 04 29 (Friday)](#2022-04-29-Friday)


## 2022 04 05 (Tuesday)

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

Script <br>
 <br>
let str = ''; <br>
 <br>
for (let i = 0; i < 100; i+= 2) { <br>
    str = str + i +"\n"; <br>
 <br>
} <br>
 <br>
console.log(str); <br>

### 2. Bad Code

The code shown below is not working in the right way, as a task you must find the error made by the developer who programmed this code and correct it, for this exercise you must explain what the error is and place the correct code

var cond = false; <br>
 <br>
if ((cond = true)) { <br>
  console.log('The cond variable is true'); <br>
} else { <br>
  console.log('The cond variable is false'); <br>
} <br>
 <br>

the programer inicialized the variable cond like a boolean, and this variable does not compared with aritmetic comparators. 
is a rule for ECMAScript to use 3 = in these cases.

var cond = false; <br>
 <br>
if ((cond == true)) { <br>
  console.log('The cond variable is true'); <br>
} else { <br>
  console.log('The cond variable is false'); <br>
} <br>
 <br>

### 3. Bad Code 2

You must create the code that follows the following logic, if the given number is 100, take this number as special and show the following message: "This is a special number!", but if the number is less than 1000, multiple of 10 and different from 100, you must show the following message: "This number is almost special". if none of the given conditions are met show the following message: "Just a regular number". Another developer was trying to program the logic, but apparently couldn't, you need to fix the code to work properly

var n = 100; <br>
 <br>
if (n == 100) { <br>
  console.log('This is a special number!'); <br>
} <br>
if (n < 1000) { <br>
  console.log(''); <br>
} else { <br>
  console.log('Just a regular number'); <br>
} <br>
if (n % 10 == 0) { <br>
  console.log('This number is multiple of 10'); <br>
} <br>
 <br>
 
 Before I fixed the code this work properly, the code is the next
 
 var n = 100; <br>
 <br>
if (n == 100) { <br>
  console.log('This is a special number!'); <br>
} <br>
else if (n < 1000 && n % 10 == 0) { <br>
  console.log('This number is almost special'); <br>
}  <br>
else { <br>
  console.log('Just a regular number'); <br>
} <br>

### 4. Git Course


## 2022 04 08 (Friday)
