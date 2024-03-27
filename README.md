# typescript

## Class 2
- tsc filename.ts = conversion of typescript to javascript
- node filename.js = run code of javascript in javascript
- tsc -v = for check that typesript is installed or not



## Class 3
- tsc -init = ye likhnay say aik tscconfig.json kay name ki aik file bn jate hai jis main desription hoti hai
- npm init -y = ye hmay package bna krdeti hai
- npm i @types/node -D = ye bhi packages install krdeta hai
- variable have three types:
    1. var name = "AHSAN RAZA" = ye zyda use nhi krtay
    2. let a = "AHSAN RAZA" = Variable repeat mhi krsktay ha
    3. const a ="Ahsan Raza = Aik constant bnadega jis ki value kbhi bhi cahnge nhi hogi
- variable ko string define krkay "" (inverted comas) main hi likhna hai wrna error aayega.
- agr wohi variable ko edit krna hoga tou let nhi likhengay sirf variable ka name hi likhengay is trha:
```typescript
let color="blue";
console.log(color);
color="purple";
console.log(color);
```
**Output**:
>blue<br>purple<br>

but agr hmay exchnage krna hoga tou is trha likhengay:
```typescript
let color="blue";
color="purple";
console.log(color);
```
**Output**:
>purple



## Class 4
### Cases:
- camel'C'ase: ahsanRaza   
- snake'_'case: ahsan_Raza
- 'P'ascal'C'ase: AhsanRaza



### Legal:
Ye start main likh skte hn
- _
- capital letter
- $
- small 

### Illegal
Ye start main likh skte hn
- numbers (1, 2, 3,...)
- special characters (@, #, $, %, +, -, ...)

### Primitive datatypes:
- string: textual data.
- number: numbers and floating point number(decimal). It has maximum limit.
- boolean: true and false.
- null: has no value
- float: decimal values
- undefined: declared but not initialized
- unknown
- BigInt: this is use when number type limit is full/maximum
- any: any datatype is use in any.
- symbol: unmuttable and unique.



## Class 5
- type anotation: variable ki type define krna type anotation kehlati hai
- type inference: variable ki type define nhi ki ho aur typescript khud indentify krle value ko dekh kr tou isko type inference kehtay hai
- let :jb variable main  koi value nhi dengay tou jb run krengay tou answer "undefined" aayega.
- for const:value dena zrori hai otherwise error occur.



## Class 6
### types of error:
- Syntax error: spelling/gramatical mistake
- type error: asa hi hai jaysy log ki jagh logger kridya woh type error hai
- assignability error: jo type diye ho aur us kay oppostie wale type use krdengay tou ye error aajayega

### Strings
- stringconcatination: `console.log("My name is "+ variable)`
- template literal: `console.log('My name is ${variable}')`

## class-7
### operators
 - addition(+)
 - subtraction (-)
 - multiplication (*)
 - division (/)
 - exponantation(**) (power)
 - Modules (%) (remainder)
 - Unary operators (++) (--)
 - 
 - 
 - 
 - 
 - 