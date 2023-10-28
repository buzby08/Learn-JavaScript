The console is the place where the computer outputs messages to the user.
Most of the things that a computer does is done in the background, and us 
users do not see. To output something in JS, we use the console.log method. 
***console is an object in JS, more details later***

``` javascript
console.log(49); // This is the same as pythons 'print' statement.
//          ^^ Everything in the parenthesis is outputed.
```

Just like any language, JS has different data types. Some of these are:
 - **Number**: Any number (incl. numbers with decimals)
 - **BigInt**: Any number greater than 2^(53) - 1 (or -(2^53)) 
 - **String**: A group of characters (denoted by single quotes ('...') or double quotes ("...")
 - **Boolean**: true or false. These are the only two values. Think of them as on and off.
 - **Null**: The intentional abcence of a value
 - **Undefined**: denoted by keyword 'undefined' (without quotes). It means that the given value doesn't exist
 - **Symbol**: New addition to language. Don't worry about these (for now)
 - **Object**: Collection of related data

``` javascript
console.log(hello); // wouldn't work. This is because JS assumes hello is a variable, which is undefined. Instead, to print 'hello', us the below
console.log("hello") // Good :)

```
