## [1.Convert Minutes into Seconds](https://edabit.com/challenge/8q54MKnRrm89pSLmW)

**Answer**


``js

convert(5) ➞ 300

convert(3) ➞ 180

convert(2) ➞ 120


function convert(minutes) {
	
}


function convert(minutes) {
	return minutes*60
}

``

## [2.Area of a Triangle](https://edabit.com/challenge/3CaszbdZYGN4otQD8)


**Answer**

`js

triArea(3, 2) ➞ 3

triArea(7, 4) ➞ 14

triArea(10, 10) ➞ 50

function triArea(base, height) {
	
}

function triArea(base, height) {
	return(base*height)/2
}

``


## [3.Return the First Element in an Array](https://edabit.com/challenge/QaApgtePE6QrCZ64o)


**Answer**

``js

getFirstValue([1, 2, 3]) ➞ 1

getFirstValue([80, 5, 100]) ➞ 80

getFirstValue([-500, 0, 50]) ➞ -500

function getFirstValue(arr) {
	
}

function getFirstValue(arr) {
    return arr[0]
}

``

## [4.Convert Hours into Seconds](https://edabit.com/challenge/6AnQqiEjkJdZrWhPS)


**Answer**
``js

howManySeconds(2) ➞ 7200

howManySeconds(10) ➞ 36000

howManySeconds(24) ➞ 86400

function howManySeconds(hours) {
	
}

function howManySeconds(hours) {
	return(hours*3600)
}

``

## [5.Return the Remainder from Two Numbers](https://edabit.com/challenge/Q2j5FTFtsk7PdzrQk)

**Answer**
``js

remainder(1, 3) ➞ 1

remainder(3, 4) ➞ 3

remainder(-9, 45) ➞ -9

remainder(5, 5) ➞ 0


function remainder(x, y) {
	
}

function remainder(x, y) {
	return(x % y)
}

``

## [6.Return Something to Me!](https://edabit.com/challenge/MvZK536X7fyrWH8Qc)

**Answer**

``js

giveMeSomething("is better than nothing") ➞ "something is better than nothing"

giveMeSomething("Bob Jane") ➞ "something Bob Jane"

giveMeSomething("something") ➞ "something something"


function giveMeSomething(a) {
	
}

function giveMeSomething(a) {
	return("something"+" "+a)
}

``


===========================================================================================


## [7.Sum of Polygon Angles](https://edabit.com/challenge/fBJyQSe5Jmbm9hPAG)

**Answer**

``js

sumPolygon(3) ➞ 180

sumPolygon(4) ➞ 360

sumPolygon(6) ➞ 720



function sumPolygon(n) {
	
}



function sumPolygon(n) {
	return (n - 2) * 180
}

``
## [8.Basic Variable Assignment](https://edabit.com/challenge/ZNwHGgHvsdnYwJ5WK)

**Answer**

``js 

nameString("Mubashir") ➞ "MubashirEdabit"

nameString("Matt") ➞ "MattEdabit"

nameString("javaScript") ➞ "javaScriptEdabit"


function nameString(name){
	var b == "Edabit"
	var result == name + b
  	return result
}

function nameString(name){
	var b = "Edabit"
	var result = name + b
  	return result
}

``


## [9.Convert Hours and Minutes into Seconds](https://edabit.com/challenge/JesaFi5ntBEbGT8bu)

**Answer**

``js


convert(1, 3) ➞ 3780

convert(2, 0) ➞ 7200

convert(0, 0) ➞ 0


function convert(hours, minutes) {

}


function convert(hours, minutes) {
	return  (hours*3600) + (minutes*60)
}

``


## [10.Equality Check](https://edabit.com/challenge/BGvTMfwxYDRbtaTJ3)

**Answer**

``js

checkEquality(1, true) ➞ false
// A number and a boolean: the value and type are different.

checkEquality(0, "0") ➞ false
// A number and a string: the type is different.

checkEquality(1,  1) ➞ true
// A number and a number: the type and value are equal.


function checkEquality(a, b) {
  
}

function checkEquality(a, b) {
    return a === b
}

``



