![JS](/images/js.png)
JavaScript is a popular programming language that has a wide range of applications.
JavaScript was previously used mainly for making webpages interactive such as form validation, animation, etc. Nowadays, JavaScript is also used in many other areas such as server-side development, mobile app development and so on.
# Role of JavaScript in web development
![role of JavaScript](/images/jsrole.png)
# History of JavaScript
firstly was created in 1995 in just 10 days. It was called Mocha.
In 1996 Mocha was named LiveScript and then JavaScript to attract Java developers.
To standardize the language, in 1997 ECMA released ECMAScript 1 (ES1), the first **official standart for JavaScript.**
In 2009 ES5 (ECMAScript 5) is released with lots of great new futures.
In 2015 ES6/ES2015 (ECMAScript 2015) was released:**the biggest update to the language ever!**
2016 till now was released ES2016/ES2017/ES2018/ES2019/ES2020/ES2021/ES2022/ES2023
# How To run JavaScript
There are 3 ways to run JS
1. using console tab of web browsers
2. using Node.js
3. creating new web 

# First Way
![first way](/images/run1.png)
# Second Way
![second way](/images/run2.png)
# Third Way
![third way](/images/run3.png)
# There are 2 ways to create variables in JavaScript
1. let
2. var

# If you are shure that value won't change it's recommended to use const

#var
var is used in older versions of JS
ex: var a

#let
let is new way to declare variables starting in ES6 (ES2015)
ex: let x

#const
the value of variable is constant
ex: const y

there are 2 data types
1. primitives
2. objects (non-primitives)

#primitives
1. number let x = 5
2. string let s = "hello"
3. boolean let tr = true
4. undefined
5. null
6. symbol(very rarely used)
7. bigInt(very rarely used)

# objects(non-primitives)
1. arrays
2. functions
3. many more...

# operators

# arithmetic operators
1. +
2. -
3. *
4. /
5. %
6. ++
7. --

# logical operators
1. &&
2. ||
3. !

# comparison operators
1. <
2. '>'
3. <=
4. '>'=
5. ==
6. !=
7. === (equal value and type)
8. !== (not equal value or not equal type)

# assignment operators
1. =
2. +=
3. -=
4. *=
5. /=
6. %=

# conditions
# 1. if.else condition
let x = 2
if (x > 0) {
    code
}

else if (x == 0) {
    code
}

else {
    code
}

# 2. ternary condition 
condition?true:false

# 3. switch 
let x = 2
switch {
    case 1 :
        console.log('no');
        break;
    case 2 :
        console.log('yes');
}

# loops

# loop for
for (let i = 0; i < 5; i++){
    console.log(i);
}

#loop while
let i = 0
while (i < 3) {
    console.log(i);
    i++;
}

#functions

#declaration
function sum (let a, let b) {
    return a + b;
}

console.log(34, 5);


#expression

#arrow
let sum (let a, let b) => {
    return a + b;
}

console.log(34, 5);

#anonymus
let sum = function (let a, let b) {
    return a + b;
}

console.log(3 ,5);

#IIFE
var x = 5;
(function (a, b)) {
    console.log(a + b);
}()