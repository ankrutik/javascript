# Javascript Notes

[TOC]



## Variables

```javascript
let a = 34,
		b = 34,
		c = "asd";
		
const pi = 3.142;

// do not use var 
var v_a = 12;
```

Do not use the deprecated `var`. When vars are used before being initialised, the error thrown is not very intuitive.  

## Types

`typeof variable_name` will return the type.

## Operators

Standard mathematical operators supported.

Incerement and decrement as usual.

## Numbers

```
let number_a = 1.3 + 1.1;
document.write(number_a);

>> 2.4000000000000004 
```

Be careful with float precision.