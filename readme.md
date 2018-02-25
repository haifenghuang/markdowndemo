# File `11.my`
## Index

* Lets
  * [a](#a)

* Enums
  * [LogOption](#LogOption)

* Functions
  * [add](#add)
  * [sub](#sub)

* Classes
  * [IndexedNames](#IndexedNames)
  * [Person](#Person)

## Lets

### a
```monkey
let a = 12;
```
variable a is a constant

## Enums

### LogOption
```monkey
enum LogOption{
        Lmicroseconds = (1 << 2),
        Llongfile = (1 << 3),
        Lshortfile = (1 << 4),
        LUTC = (1 << 5),
        LstdFlags = ((1 << 4) | (1 << 5)),
        Ldate = (1 << 0),
        Ltime = (1 << 1)
}
```
The LogOption enum is defined for Log options.

## Functions

### add
```monkey
fn add (x, y)
```
Add two parameters.

### sub
```monkey
fn sub (x, y)
```
Substract two parameters.

## Classes

### IndexedNames
```monkey
class IndexedNames{ ... }
```
Class 'IndexedNames' demonstrate class indexer.

#### Lets
```monkey
let size = 10;
```
constant size, equals to 10.

#### Properties
```monkey
property this[index] { get; set; }
```
This is the indexer property

### Person
```monkey
class Person{ ... }
```
  A Persion class which has three private variable:
       firstName
       lastName
       nickName
  and two methods :'init' and 'Msg'.

 2 A Persion class which has three private variable:
      firstName
      lastName
      nickName
 and two methods :'init' and 'Msg'.

#### Lets
```monkey
let firstName;
```
this is the firstname
```monkey
let lastName;
```
this is the last name

#### Properties
```monkey
property Age { get; set; }
```
This is property Age.
```monkey
property Height { get; set; }
```
This is property Height

#### Functions
```monkey
fn Msg (extra1, extra2, args)
```
Method 'Msg' demonstrate function default values and variable arguements
This is another methods of Person Class.
```monkey
fn init (firstname, lastname, nickname)
```
This is the constructor of the Person class.

***
_Last updated 2018-02-25_
