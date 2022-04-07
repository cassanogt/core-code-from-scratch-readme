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

	a. Create a program to add two numbers given by the user

Script

[].data </br>
[]        number1: .asciiz "\nAdd First number: \n"  </br>
[]        number2: .asciiz "\nAdd Second number: \n"  </br>
[]        result_message: .asciiz "\nthe sum is: "  </br>
5  .text
6        main:
7              li $v0, 4
8              la $a0, number1
9              syscall
10              
11              li $v0, 5
12              syscall
13              
14              move $t0, $v0
15              
16              li $v0, 4
17              la $a0, number2
18              syscall
19
20              li $v0, 5
21              syscall
22
23              move $t1, $v0
24
25              li $v0, 1
26              move $a0, $t0
27              syscall
28              
29              add $t2, $t0, $t1
30              
31              li $v0, 4
32              la $a0 result_message
33              syscall
34
35              li $v0, 1
36              move $a0, $t2
37              syscall

Create a program that display your name

Script

.data
        message: .asciiz "\nHeber Daniel Sánchez Hernández\n"
  .text
        main:
              li $v0, 4
              la $a0, message
              syscall


## 2022 04 07 (Thursday)

## 2022 04 08 (Friday)
