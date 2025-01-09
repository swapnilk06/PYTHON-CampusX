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

### Keywords -

#### Keywords through backstory -
  - In python coding all words like <b>"print, input, type, int, complex"</b> are english(universal language then it written in english) type of word.
  - But our machine that on our code is running or executing that have `Processor` called "CPU"(i5, snapdrogon).
  - Processor are issentially `IC's` as "Integrated Circuits" that have problem is only can understand `1's` or `0's` becz, are `digital in nature`.
  - They can understand `0 volt(0's)` or `5 volt(1's)` they <i>can't understand 2.5 volt, 3 volt</i>.
  - Our english written code humans are understand easily, but english wriiten code can't understand processor.

-----


- Compiler or Interpreter that convert english high level code to machine level code.
- Compiler is piece of software written by other some experience programmer, that convert high level code to low level code.

- 
- In binary `0's & 1's` combination as a assembly language.
- As begining to solving this issue (of whole things in binary are not possible) programer developed `Assembly language` to solve `'2' as 0010`, pattern for `'+' assume 10101`, `'3' as 0110`(all   with like 2+3 => `0010ADD011`.


> NOTE* -
> `Machine language(Binary language)` --> `Assembly language` --> `High level language`
  ```
 High level language              `3rd introduced`
         ^
         |
 Assembly language                `2nd introduced`
         ^
         |
Machine language(Binary language) `1st introduced` 
```

> - Assembly language : 2+3 => `0010ADD011`
>   - In assembly language we don't build "facebook".
>   - Using this assembly language 
> - High level language : C, Fortran , basic

`9-1-25`

