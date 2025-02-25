`6-1-25`


## Python for machine learning Part 2 -


### Examples of print()

```python
print(1,2,3,4) # 1 2 3 4

print(1,2,3, sep='/') # 1/2/3

print(1,2,3, sep='Jai mata di') # 1 Jai mata di2Jai mata di3

print(1, end="Jai shree ram") # 1 Jai shree ram
```

<br>

### Variable Binding -

- Values stored in variable that process called as `Variable Binding.`

```python
fnum = 100
fnum    # 100
fnum    # 100 -> always printing fnum as value is 100 i.e. variable binding example
```

- Variable binding have 2 types -
  - Single assessment (a=5)
  - Multiple assessment (a=b=c=5, a,b,c=5,6,7)

> NOTE* - python variable binding increase our program "efficiency" & also increases our typing speed that hel to minimum time to program.
 
```python
a,b,c=2,3,4
b    # 3

a=b=c=5
c    # 5 
```

<br>

### Type Conversion -

- Type Conversion have 2 types -
  - Implicit Type Conversion
    - Python interpreter witohut programmer help directly solve 'int' + 'float' value output as 'float' value without showing error.
  - Explicit Type Conversion
    - As programmer or our responsibilty to told interpreter that time we required type conversion. 

```python
# Implicit Type Conversion
5+4.5    # 9.5
```

<br>

### Comment - 

- `#` this is comment
- Comnment means, is line of code that <b>ignore</b> by interpreter or compiler.

> NOTE* - Comments `#` make best whats about in current program or project. It's best practice to showing info about what in that part.


<br>

`9-1-25`

### Keywords -

#### Keywords through backstory -
  - In python coding all words like <b>"print, input, type, int, complex"</b> are english(universal language then it written in english) type of word.
  - But our machine that on our code is running or executing that have `Processor` called "CPU"(i5, snapdrogon).
  - Processor are issentially `IC's` as "Integrated Circuits" that have problem is only can understand `1's` or `0's` becz, are `digital in nature`.
  - They can understand `0 volt(0's)` or `5 volt(1's)` they <i>can't understand 2.5 volt, 3 volt</i>.
  - Our english written code humans are understand easily, but english wriiten code can't understand by "processor".
  - We need a mechanism which can convert english code to `1's` and `0's` pattern that have easily understand by machine.
  - Thats of conversion(english high level code to machine level code) work done by `Compiler` or `Interpreter`.

#### Compiler or Interpreter -
- Compiler or Interpreter that convert english high level code to `machine level code`.
- Compiler is `piece of software written by some other experience programmer`, that conversion particular high level code to low level code.

#### Before invesion of compiler code wriiten -
  - #### 1] Machine Language -
  - Before all high level Programming we code in only `0's & 1's`.
  - Example of Binary Code -
    - 2+3 `'2' as 0010`, `'+' assume pattern 10101`, `'3' as 0110` & output of 5 in also in binary as `0010101010110`.
  - Programmer written all over code in binary format as well as output.
  - Code written in Binary language is `very difficult`.
  - Facebook type big application can't build in binary language.
  - That time programer realise in this type of language(binary language) not a possible to build application.

  - #### 2] Assembly Language -
  - We need to in programming `Remember somethings`. thats way 1st programmer replace by some keywords like `ADD`, `CUB`, `CUT`, `PASTE`...
  - Example of Assembly Code -
    - 2+3 => `0010ADD011`
  - Assembly language also realise not work done.

  - #### 3] High-Level Language -
  - Basic, C, FORTRAN `high-level` programming languages(procedural languages).
  - Internally all languages confusion without keywords -
    - Imaging as programer we store `0010ADD011` in variable `ADD` then it confuse `ADDADD011`.
  - This reasons other languages & python reserve keywords used.
  
- In python 32 keywords are reserved. they are not used as a variable name.
- `Keywords` : are those reserved words by the compiler or the language that are not use by programmer as variable names, as function names, class name.


> NOTE* -
>
  ```
 High level language                 `3rd introduced` - Basic, C, FORTRAN
         ^
 Assembly language                   `2nd introduced`
         ^
Machine language(Binary language)   `1st introduced` 
```

### Identifiers -

#### In python identifiers makes from 3 things ours - `variable names`, `function names`, `class names`
- Any name as a programmer we create that means it's `Identifiers`.

#### Rules for Identifiers -
- 1] Can be combo of `lowercase`, `uppercase`, `digits` and `_`.
- 2] Can't start with a digit.
  - e.g. 1variable # <i>not allowed </i>
- 3] Keywords != identifiers
- 4] Can't use sepcial characters inside our identifiers.  
- 5] Can have any length(no restriction on it naming length).
<br>

`18-1-25`

### Indentation - Maintain readability aspect
<br>

> NOTE* - Good Coding Practices
>   1. Descriptive identifiers - Give variable names as meaningful naming
>   2.  Descriptive file names - Give file naming as understand anyone what code inside file.
>   3. Frequent Comments
>   4. Indentation
<br>


### Statements -
- Any line of our code which are executable by code is called `statement`.
  - E.g. a=b+c, print (hello world)... that are also executable by python that called statements.
<br>

### Expressions -
- E.g. 2+4 i.e. `Operand` is 2 -> `Operator`  is + -> `Operand` is 4
<br>

### Literals - 
- Literals are values given to a variable.
- E.g. a = 2 i.e. 2 is `literal`
- E.g. a = 0b0011 is literal

``` python
# Litertal
a = 0b0011   # 0b means "Binary code"
a            # 3

a = 0x123    # 0x means "Hexa decimal code"
a            # 291
```

#### Numrical literals
``` python
a = 1.5e4    # e means "Exponential"
a            # 15000.0
# this are numrical literals we can use instead motation 1.5e4 of 15^10.
```
<br>

`24-1-25`
#### String literals
``` python
city = "Pune"
city        # 'Pune'
city = 'Pune'
city        # 'Pune'
# In python "" or '' are same output.
```
- `"" or '' quotes` -> for these single or double quote same functionality programmer also write extra code.

#### Q. Why `"" or '' quotes` in python? Why that comfort any quote which can used?
- Reasons through E.g.
``` python
day = 'It's a rainy day'  # Error - SyntaxError

day = "'It's a rainy day'"  # "It's a rainy day"
```

#### None literal
``` python
x=None      # ___ "it show blank value"
````
#### Interview - Q. Why `None` in python?
- bcz, in python `variable declaration is not present`.

#### Interview - Q. In python its possible variable stored in code without any value?
- In python `we never declare variable` i.e. we just create & used them.
``` python
thor      # Error - NameError: name 'thor' is not defined
````
- Whaever we plan to required 10 variable in future using `None`.
``` python
thor=None
thor            # ____ "it show blank value"
thor="Hero"     # Hero
````

#### Interview based answer - When I plan project on various senario that point we need variable, that variable stored in code for future used through reasign that we initialize it using `None`.
<br>

> NOTE :
> - Every time we thick why any learn?
<br>


### Operators - 




39 min
