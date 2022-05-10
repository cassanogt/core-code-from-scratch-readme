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
	1. [Follow the github course](#1-Follow-the-github-course)
	2. [Create an account in Codewars](#2-Create-an-account-in-Codewars)
	3. [Read about if...else, for, while, functions](#3-Read-about-if...else,-for,-while,-functions)
1. [2022 04 19 (Tuesday)](#2022-04-19-Tuesday)
	1. [Multiply exercise](#1-Multiply-Exercise)
	2. [ASCII Total exercise](#2-ASCII-Total-Exercise)
	3. [Char From ASCII Value exercise](#3-Char-From-ASCII-Value-Exercise)
	4. [Binary Addition exercise](#3-Binary-Adittion-Exercise)
	5. [Student's Final Grade exercise](#3-Student's-Final-Grade-Exercise)
2. [2022 04 20 (Wednesday)](#2022-04-20-Wednesday)
	1. [Holliday VIII - Duty Free exercise](#1-Holliday-VIII-Duty-Free-Exercise)
	2. [Twice As Old exercise](#2-Twice-As-Old-Exercise)
	3. [Valid Spacing exercise](#3-Valid-Spacing-Exercise)
	4. [Fake Binary exercise](#4-Fake-Binary-Exercise)
3. [2022 04 21 (Thursday)](#2022-04-21-Thursday)
	1. [Remove All Exclamation Marks From The End of Sentence exercise](#1-Remove-All-Exclamation-Marks-From-The-End-Of-Sentence-Exercise)
	2. [Vowel Remover exercise](2-Vowel-Remover-Exercise)
	3. [Rock Paper Scissors! exercise](#3-Rock-Paper-Scissors!-Exercise)
	4. [Persistent Bugger exercise](#4-Persistent Bugger-Exercise)
4. [2022 04 22 (Friday)](#2022-04-22-Friday)

<h2>Week 3</h2>


1. [2022 04 25 (Monday)](#2022-04-25-Monday)
	1. [Who likes It exercise?](#1-Who-Likes-It?-exercise)
	2. [Bit Counting exercise](#2-Bit-Counting-exercise)
	3. [Your Order, Please exercise](#3-Your-Order,-Please-exercise)
1. [2022 04 26 (Tuesday)](#2022-04-26-Tuesday)
	1. [Simple Pig Latin](#1-Simple-Pig-Latin-exercise)
	2. [Counting Duplicates exercise](#2-Counting-Duplicates-exercise)
	3. [Decode The Morse Code exercise](#3-Decode-The-Morse-Code-exercise)
2. [2022 04 27 (Wednesday)](#2022-04-27-Wednesday)
	1. [Valid Parentheses exercise](#1-Valid-Parenthesis-exercise)
	2. [Convert String To Camel Case exercise](#2-Convert-String-To-Camel-Case-exercise)
	3. [Unique In Order exercise](#3-Unique-In-Order-exercise)
3. [2022 04 28 (Thursday)](#2022-04-28-Thursday)
	1. [Fold An Array exercise](#1-Fold-An-Array-exercise)
	2. [Encrypt This! exercise](#2-Encrypt-This!-exercise)
	3. [Completing my 1st Core Challenge](#3-Completing-My-1st-Core-Challenge)
4. [2022 04 29 (Friday)](#2022-04-29-Friday)

# WEEK 1

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
for (let i = 0; i <= 100; i+= 2) { <br>
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



# WEEK 2


## 2022 04 19 (Tuesday)


### 1. Multiply Exercise

Script <br>
function multiply(a, b){ <br>
  return a * b; <br>
} <br>
 <br>


### 2. ASCII Total Exercise

Script <br> 
function uniTotal (string) { <br>
let suma=0; <br>
for (let i = 0; i < string.length; i++){ <br>
   suma = suma + string.charCodeAt(i);   <br>
}// total up dem unicodes! <br>
  return suma; <br>
} <br>


### 3. Char From ASCII Value Exercise

Script <br>
Char From ASCII Value <br>
function getChar(c){ <br>
  return String.fromCharCode(c);   <br>
} <br>


### 4. Binary Addition Exercise

Script <br>
function addBinary(a,b) { <br>
  let addBinary = a + b; <br>
return addBinary.toString(2); <br>
} <br>


### 5. Student's Final Grade Exercise

Script <br>
function finalGrade (exam, projects) { <br>
 let result = 0; <br>
    if( exam > 90 || projects > 10){ <br>
        result = 100; <br>
    } else if( exam > 75 && projects >= 5){ <br>
        result = 90; <br>
    } else if( exam > 50 && projects >= 2){ <br>
        result = 75; <br>
    }  <br>
  return result; <br>
} <br>


## 2022 04 20 (Wednesday)

### 1. Holiday VIII - Duty Free Exercise

Script <br>
function dutyFree(normPrice, discount, hol){ <br>
let dutyPrice = Math.floor(hol / (normPrice * (discount/100))) ; <br>
return dutyPrice; <br>
} <br>


### 2. Twice As Old Exercise

Script <br>
function twiceAsOld(dadYearsOld, sonYearsOld) { <br>
 let diferencia = Math.abs(dadYearsOld - sonYearsOld); <br>
 let sonYearsOldTwice = sonYearsOld * 2; <br>
 let haceEstosAnios = 0; <br>
 if (diferencia >= sonYearsOldTwice){ <br>
 haceEstosAnios = (Math.abs(dadYearsOld - sonYearsOldTwice)); <br>
} else { <br>
haceEstosAnios = (Math.abs(dadYearsOld - sonYearsOldTwice)); <br>
} <br>
 return haceEstosAnios; <br>
} <br>


### 3. Valid Spacing Exercise

Script <br>
function validSpacing(s) { <br>
 if(s.charAt(0) === ' ' || s.charAt(s.length - 1) === ' ') { // como <br>
     return false; <br>
  } <br>
   <br>
  for(let i = 0; i < s.length; i++) { <br>
    if(s.charAt(i) === ' '){ // es el caracter que estamos viendo igual a un espacio? <br>
      if(i != 0 && s.charAt(i-1) === ' ') { <br>
        return false; <br>
      } <br>
      if(i != (s.length - 1) && s.charAt(i+1) === ' ') { <br>
        return false; <br>
      } <br>
    } <br>
    // .... <br>
  } <br>
   <br>
  return true; <br>
} <br>


### 4. Fake Binary Exercise 

Script <br>
function fakeBin(x){ <br>
  let largoString=x.length; <br>
    for (let index1 = 0; index1 < largoString; index1++){ <br>
    let numero1 = x.charAt(index1); <br>
    if (numero1 === "1"){ x = x.replace(x.charAt(index1), "0");  <br>
  } <br>
    } for (let index2 = 0; index2 < largoString; index2++){ <br>
    let numero2 = x.charAt(index2); <br>
    if (numero2 === "2"){ x = x.replace(x.charAt(index2), "0");  <br>
  }} <br>
  for (let index3 = 0; index3 < largoString; index3++){ <br>
    let numero3 = x.charAt(index3); <br>
    if (numero3 === "3"){ x = x.replace(x.charAt(index3), "0");  <br>
  }} <br>
  for (let index4 = 0; index4 < largoString; index4++){ <br>
    let numero4 = x.charAt(index4); <br>
    if (numero4 === "4"){ x = x.replace(x.charAt(index4), "0");  <br>
  }} <br>
  for (let index5 = 0; index5 < largoString; index5++){ <br>
    let numero5 = x.charAt(index5); <br>
    if (numero5 === "5"){ x = x.replace(x.charAt(index5), "1");  <br>
  }} <br>
  for (let index6 = 0; index6 < largoString; index6++){ <br>
    let numero6 = x.charAt(index6); <br>
    if (numero6 === "6"){ x = x.replace(x.charAt(index6), "1");  <br>
  }} <br>
  for (let index7 = 0; index7 < largoString; index7++){ <br>
    let numero7 = x.charAt(index7); <br>
    if (numero7 === "7"){ x = x.replace(x.charAt(index7), "1");  <br>
  }} <br>
  for (let index8 = 0; index8 < largoString; index8++){ <br>
    let numero8 = x.charAt(index8); <br>
    if (numero8 === "8"){ x = x.replace(x.charAt(index8), "1");  <br>
  }} <br>
  for (let index9 = 0; index9 < largoString; index9++){ <br>
    let numero9 = x.charAt(index9); <br>
    if (numero9 === "9"){ x = x.replace(x.charAt(index9), "1");  <br>
  }} <br>
  return(x); <br>
} <br>


## 2022 04 21 (Thursday)


### 1. Remove All Exclamation Marks From The End Of Sentence Exercise

Script <br>
function remove(string) { <br>
  return string.replace(/!+$/g, ''); <br>
} <br>


### 2. Vowel Remover Exercise

Script <br>
function shortcut (string) { <br>
  return string.replace(/[aeiou]/g, ''); <br>
} <br>


### 3. Rock Paper Scissors! Exercise

Script <br>
const rps = (p1, p2) => { <br>
  if (p1 === p2) return 'Draw!'; <br>
  if (p1 === 'rock' && p2 === 'scissors') return 'Player 1 won!'; <br>
  if (p1 === 'scissors' && p2 === 'paper') return 'Player 1 won!'; <br>
  if (p1 === 'paper' && p2 === 'rock') return 'Player 1 won!'; <br>
  return 'Player 2 won!'; <br>
}; <br>


### 4. Persistent Bugger Exercise

Script <br>
function persistence(num) { <br>
  let times = 0; <br>
  let digits = []; <br>
  while (num >= 10) { <br>
    digits = num.toString().split(''); <br>
    num = 1; <br>
    for (let i = 0; i < digits.length; i++) { <br>
      num *= digits[i]; <br>
    } <br>
    times++; <br>
  } <br>
  return times; <br>
} <br>



# WEEK 3

## 2022 04 25 (Monday)

### 1. Who Likes it? Exercise

Script <br>
let message = ""; <br>
  let large = names.length; <br>
  if ( names.length === 0){ return "no one likes this";} <br>
  else if (names.length === 1) { return names[0] + " likes this";} <br>
  else if (names.length === 2) { return names[0] + " and " + names[1] + " like this";} <br>
  else if (names.length === 3) { return names[0] + ", " + names[1] + " and " + names[2] + " like this";} <br>
  else if (names.length > 3 ) { return names[0] + ", " + names[1] + " and " + (large - 2) + " others like this";}  <br>
  }  <br>


### 2. Bit Counting Exercise

Script <br>
binary = n.toString(2); <br>
  const myArray = binary.split(""); <br>
  let suma = 0; <br>
  for (let i = 0; i < myArray.length; i++) { <br>
    if( myArray[i] === "1"){ suma = suma + parseInt(myArray[i])} <br>
     <br>
   } return suma;// Program Me <br>
}; <br>



### 3. Your Order, Please Exercise

Script <br>
function order(words){ <br>
  const myArray = words.split(" "); <br>
for (let i = 0; i < myArray.length; i++ ) { <br>
  myArray[i] = myArray[i] + i; <br>
  words = myArray.join(" "); <br>
 return words; <br>
}} <br>
 <br>


## 2022 04 26 (Tuesday)


### 1. Simple Pig Latin Exercise
```Javascript
Script
function pigIt(str){
  let arrStr = str.split(" ");
  let newArray = [];
  newArray = arrStr.map(function(element){
    if(!element.match(/^[.,:!?]/)){
      return (element.slice(1) + element.slice(0,1) + "ay");}
    return element
  });
  let finalPig = newArray.join(" ");
      return finalPig;
    
}
```

### 2. Counting Duplicates Exercise

### 3. Decode The Morse Code Exercise


## 2022 04 27 (Wednesday)

### 1. Valid Parentheses Exercise

### 2. Convert String To Camel Case Exercise

### 3. Unique In Order Exercise



## 2022 04 28 (Thursday)

### 1. Fold An Array Exercise

### 2. Encrypt This! Exercise

### 3. Completing my 1st Core Challenge.



