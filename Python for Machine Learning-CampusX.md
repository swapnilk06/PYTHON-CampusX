
###### Date : 24-12-24

---------------------------
### Part 1 :
---------------------------


#### Q. What is programming? <br>
=> Human talk with Machine, that required language for talking called <b>Programming</b> or <b>Programming language.</b>
<br>

### print() -

- print() - "()" is indicates function of all programming language.<br>

#### Q. What is Function?
=> 
- You can give as a input, its return output based upon a logic called <b> Function.</b>
  - E.g. Function concept is similar for S/W as well as H/W. fan, projector... etc.
- Simple, <b>`Function means gives Input & retured Output without knowing internal main logic.`</b>
- for print() you don't required how print work internally <i>(means its function)</i>.
- print() is readymade, you can directly used it, without knowing internal logic, for programmer easy working.
<br>

E.g.  
``` python
print(4)  # 4
print(4.5) # 4.5
print(Salman Khan) # SyntaxError : invalid syntax
 # bcz, we always write text in string => " or '
print("Salman Khan") # Salman Khan
	  
print(1,"Salman Khan") # 1 Salman Khan
print(1: "Salman Khan") # SyntaxError : invalid syntax
 # print rewured  2 inputs seperated by comma "," only.

print(1,2,3,4,5,6) # 1 2 3 4 5 6
 # print input have "No" any upper limit.
print() # printing Blank as output
 # print input minimum limit have 1 input.
````	  
 
###### Date : 25-12-24

### Data Types - 

<b>Data</b> :
   - Whatsapp data - Chat & Messages
   - Zomato data - Restro details, order details, menu
   - Ola data - Pickup point, destination, fare, driver details
   - Instagram data - Photos, profile info, status
   - Youtube data - Videos, search terms, comments
<br>

> * NOTE :
>   - Different platforms have different types of data. <br>
>   - E.g. Youtube main data is videos, Instagram main data is photos, Whatsapp main data is text. <br>
>   - Different different data called as "Data Types"
<br>

</b>Data types</b> :
```python
# int : We (human) speak its Numbers
print(2) # 2

# float : We speak its as Decimal
print(2.4) # 2.4

# string : We speak its as Text
print("Haldia") # Haldia
```
> * NOTE : Python can <b>inheriently support string</b>, but C can't support string.
```python
# bool : boolean 1 and 0
print(True) # True
print(False) # False
print(false) # NameError: name 'false' is not defined
```
Thats boolean example shows python is a `case sensitive language` (Uppercase & Lowercase for python are not similar)
```python
# Complex number : 
print(5+6j) # (5+6j)
```
> * NOTE :
>   - Python is the only programming language that `"Natively support of complex numbers."`
>   - We can build S/W based upon complex number we choosen `Python language` only.

#### Data types : int, float, string, bool, complex
<br>

### User Input -

E.g. - Daily life S/W's using <b>user input</b>
 - Whatsapp : give msg as a input.
 - Youtube : search, comments... are inputs from users.
 - Ola : destination
 - Phone lock, Face look -> required user inputs.
<br>

E.g. - S/W's that <b>not required</b> user input.
 - clock, calender... etc.
<br>



  
### Static Vs Dynamic - 
>NOTE : All overs desktop apps. website are have only 2 types (S/W's) -
><b>Static</b> and
><b>Dyanamic</b>

- Static :- S/W's that not required user input.
   - E.g. - Clock, Calendar...
- Dynamic :- S/W's that required user inputs.
   - E.g. - Youtube, Instagram, Whatsapp...
<br>


#### Program or user and Static or Dynamic?  
```python 
print("Haldia")
```

Q. Above <i>"print("Haldia")"</i> is "<b>program</b>" or not ?<br>
  - It's proper program bez, it have definated output is print on screen.

Q. Question is <i>"print("Haldia")"</i> is static or Dynamic? Are you getting Confuse between a programer & User?<br>
  - Static S/W is that S/W they gives by programmer (not by User).
  - User can only view output. User can't interact or make changes. i.e.Static S/W.
  - E.g. News website read without any login is static example.
<br>


###### Date : 30-12-24


### input() -

```python
input()
# >>> Pappu # this enter by the user
# >>> 'Pappu' #  this output printed on screen
```

```python
# user friendly code
input("Enter your name")
# >>> Enter your namekeju
# >>> 'Keju'
```
<br>


###### Date : 02-01-25

> * NOTE :
>   Harddisk is a read only memory (You can only read memory, we can't write on that memory)


#### Example of File save or movie save
- File or move save on harddisk(ROM - Read Only Memory).
- Movie is ROM - bcz, you can't change movie is example of ROM.
- Movie is storing time its not running that time.
- Storing movie while playing or <b>running its store ROM to RAM.</b>
- Example of ROM to RAM is APP on mobile backsite to running.
- All in run time code are store in RAM.
<br>

#### We use "ROM" as position of RAM
- ROM & RAM are same(memories) are work as storing.
- We also use <b>ROM as storage.</b>
- 1 Problem would be slow speed.
  - Example, While playing NFS runing very slowly.
- Slow playing Bcz,<b> RAM is fast in comparsion to ROM.</b>
<br>

#### Why "RAM" is fast compare with ROM?
- RAM made up of high quality silicon & ROM made up of low quality Germanium.
- Material difference.
- Example of RAM & ROM in classroom - student introduce from front of all its like RAM & all students are hear all of what they can say, but student can on seating site introduce they can't hear all i.e. ROM. 
<br>

> * NOTE :
  - Code execute from Top to Bottom for every programming.
  - "RAM" is volatile bcz, its can hold stored data that time whenever we do not close app or machine do not closed.
 - DATABASE : In RAM more values are generated - at time programmer decision is user can also ask that values, them they can move values from RAM to DATABASE(database aslo stored in ROM).
  - Example of Database - Calculator history(stroing past calculation) is decision of programmer we show past values or not?


<br>

### Variable -
- Varaible is a nothing but a container - that in storing user inputs for future use.
- In python we never declare variables, we can directly use them.

<br>

> * NOTE : - In python, input() default format is "string" format.

> --
> Interview Question -
> - Q. Why its keeped as "string"? why not default format in integer, complex, boolean, decimal...?
> --

<br>

#### Reason behind in python input() as in "string" format 
1) Integer can easily written in String, but string can't written in integer.
   - 4(integer) written in '4'(string), but 'Pune'(string) is <b>not written in integer.</b> its varsatile.
2) Current world mostly user input format in "string".


<br>

### Data type -
```python
type(4) # <class 'int'>
type(4.5) # <class 'float'>
type(True) # <class 'bool'>
type(fnum) # <class 'str'>
```

### Type Conversion - 

E.g. - without type conversion ERROR
```python
int("Pune") # Invalid Literal for int()
'``
<br>
```python
int(4.5) # 4
int("4") # 4

5(int("4")) #<class 'int'>

```















	   


	 
