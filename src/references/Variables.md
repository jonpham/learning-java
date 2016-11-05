# JAVA
**Primitives and References**

##*Variables*
Variables are used to call objects. Since Java is object oriented, everything is an Object. 

There are however two types of objects that a Variable can store.

1) Primitive Types ; store objects which are of a Java Primitive Type
2) Referenced Types (Complex) ; store objects which are constructed from Primitives or other Classes and have a defined class structure. 

###*What is a Variable, Really?*

A Variable is a type-specific reference to a memory address which represents an object. The Type designates the size allocated to the object so the JVM knows that the object occupies memory from the Initial Memory Block + the Memory Allocation Size for the Type. 

|type|name|
|----|----|
|int|count|

_Variable Declaration_
<type> <name> = <initial value>; 

###*Factors which affect Variables Scope*

1) state; local vs instance
2) parameter; as argument by value or reference
3) Global Scope

##Primitive Types

**Boolean & Char**
|Type | Bit Depth | Value Range |Example|
|-----|-----------|-------------|-------|
|boolean|JVM-dependent|*true* or *false*| bool isTrue=false|
|char|16 bits|0 to 65535 (2^16-1)|char x = 'f'|

**Integers**
|Type | Bit Depth | Value Range |Example|
|-----|-----------|-------------|-------|
|byte|8 bits|-128 to 127| byte b = 89 |
|short|16 bits|-32768 to 32767|short s = 24|
|int|32 bits|-2147483648 to 2147483647| int y = -35|
|long|64 bits|(-2^32 to (2^32-1)| long z = 10000 |

**Floating Point Values**
|Type | Bit Depth | Value Range |Example|
|-----|-----------|-------------|-------|
|float|32-bits | Depends | float x = 32.5f |
|double|64-bits | Depends | double y = 32.5 |


