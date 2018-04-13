# __Intro to Lua__
Lua is a programming language traditionally used in much larger projects because of its small, lightweight, and simple framework. It is also used in many games with a similar purpose. This should be an introduction to the language as well as basic fundamentals of it.
## Hello World
`print ("Hello World!")`

## Variables
Loosely typed. Variables are global by default.

#### Local Variables
```
local i = 1

local i, j = 1, 10;

local i, j = 1 --j is nil
```
#### Global Variables
```
i = 1

i, j = 1, 10;

i, j = j, i --helpful value swap
```

## Comments

#### Single Line Comments
`
--Two hyphens signals singleline comment
`
#### Multi-Line Comments
`--[[ The square brackets following the two hyphens creates a multi-line comment ]]`

## Functions

Functions are started with the **Function** keyword followed by the name of the function and a slot for parameters. It is ended by the keyword **end**.

```
function Name(param)
        print('Hello' .. param)
        return
end --included in all to close
```

## Arrays
Generally filled with 0's using loop before use. This way anything outside of expected parameters returns nil

`a = {} --new Array`

## Control & Program Flow

#### Control Operators
```
"if" --used to execute a block of code only if a condition is met

"for" --used to execute a block of code with iteration

"while" --used to execute a block of code while something remains true

"repeat" --used to repeat a block of code a specified number of times
```

#### End Operators
```
"end" --used after any operator other than repeat to end the block

"until" --used after repeat to tell how many times to repeat
```

#### Structure
```
if i = j then
  print("true")
end
```

## Operators

#### Basic
```
"+" --adds two operands

"-" --subtracts second operand from first

"*" --Multiply both operands

"/" --Divide numerator by denominator

"%" --Modulus operator, returns remainder

"^" --Exponent operator
```

#### Relational
```
"==" --Checks if two values are equal and returns true or false

"~=" --Checks if two values are NOT equal and returns true or false

">" --Checks if the left operator is greater than the right

"<" --Checks if the right operator is greater than the left

">=" --Same as > but also checks if it is equal to

"<=" --Same as < but also checks if it is equal to
```
#### Logical
```
"and" --Checks if two conditions are true and returns true

"or" --Checks if either of two conditions is true and returns true

"not" --used to reverse logic i.e. !(i = 1)
```

#### Others
```
".." --used to concatenate two strings

"#" --used to return the length of a string
```

## Special Properties
Has freeform syntax. Simple and efficient

`print("250" + 250) --returns 500.0`
