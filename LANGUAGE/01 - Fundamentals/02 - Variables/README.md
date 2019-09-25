# Variables
In this section we are going to discuss about variables in golang.

## Data Types

1. **Numbers**
In Go language, both signed and unsigned integers are available in four different sizes as shown in the below table. The signed int is represented by int and unsigned integer is represented by uint.

| Data Type         | Description                |
| ------------------|:---------------------------------------:|
| int8              | 8 bit signed integer       |
| int16             | 16 bit signed integer      |
| int32             | 32 bit signed integer      |
| int64             | 64 bit signed integer      |
| uint8             | 8 bit unsigned integer     |
| uint16            | 16 bit unsigned integer    |
| uint32            | 32 bit unsigned integer    |
| uint64            | 64 bit unsigned integer    |
| int               | either 32 or 64 bit        |
| uint              | either 32 or 64 bit        |
| rune              | synonym of int32           |
| byte              | synonym of int8            |
| uintptr           | all the bits of pointer value  |

2. **Floating-Point Numbers**
 In Go language, floating-point numbers are divided into two categories as shown in the below table:

| Data Type         | Description                |
| ------------------|:---------------------------------------:|
| float32              | 32-bit IEEE 754 floating-point number     |
| float64             | 64-bit IEEE 754 floating-point number   |


3. **Complex Numbers**
The complex numbers are divided into two parts are shown in the below table. float32 and float64 are also the part of these complex numbers. The in-built function creates the complex number from its imaginary and real part and in-built imaginary and real function extract those parts.

| Data Type         | Description                |
| ------------------|:---------------------------------------:|
| complex64              | Complex numbers which contain float32 as a real and imaginary component.     |
| complex128             | Complex numbers which contain float64 as a real and imaginary component.   |

4. **Booleans**
The boolean data type represents only one bit of information either true or false. The values of type boolean are not converted implicitly or explicitly to any other type.

5. **Strings**
String data type represents a sequence of Unicode code points. Or in other words, we can say a string is a sequence of immutable bytes, means once a string is created you cannot change that string. A string may contain arbitrary data, including bytes with zero value in the human-readable form.

## Varibale Declaration
**Syntax**
```
var variable_name type = expression
```