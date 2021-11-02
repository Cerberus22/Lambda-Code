# import statement
` #import "filename.lc" `


# comments
```
// Comment
/// multi  
line
Comment ///
```


# defining functions
```
func name(arg1, arg2)
  print(arg1, arg2)
  int var = 123
  return var
endfunc

arrowfunc = () =>
  **logic**
  int var = 123
  return var
endfunc
```


# data types
string <name> = "rick" <br>
int <name> = 7 (32bits int) <br>
long int <name> = 98739823544856 (64bits int) <br>
float name = 0.1 <br>
array arr[type,length] = 1,2,2,3,3,4 <br>
const <data type> <name> = <var>


# Conditional statements and iterations
### If statements
```
if (code == code2)
  your code


elseif (code == code2)
  your code


else 
  your code

endif
```

### For loop
```
for i in var
  your code
endfor
```

### While loop
```
while true
  your code
endwhile
```


# Operators
== equal <br>
!= not equal <br>
<= lower than or equal <br>
\>= greater than or equal <br>
< lower than <br>
\> greater than <br>

= assignment <br>

++ increment by 1 <br>
-- decrement by 1 <br>
+= increment by the number specified <br>
-= decrement by the number specified <br>
*= multiplication by the number specified <br>
/= division by the number specified <br>

### Logical operators
and
or


# Object Oriented Programming
## Classes:
```
class <Name> (params)
  <accessModifier> <type> attr = <default>
endclass
```
So as for simplicity, the parameters of the constructor is defined directly inside the parantheses.


## Encapsulation
### Access Modifiers
-> **Shield:** Can only be accessed within the class
-> **Global:** Can be accesed from anywhere


## Inheritance 
```
class Animal () 
  func eat () 
    print("I am eating some stuff")
  endfunc
endclass

class Dog inherits Animal () 
  func bark () 
    print("Woof woof!")
  endfunc
endclass
```
