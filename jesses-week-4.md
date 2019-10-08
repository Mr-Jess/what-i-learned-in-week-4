# **Week-4**

## **Monday** 9/30/19

* Boolean Basic Exercise
* Boolean Operator Exercise
* HRM Countdown Year 18

* Booleans is a datatype that returns either of two values either true or false.
* Booleans is used as a function to get the value of a variable, object, conditions,expressions etc. in terms of true or false.

### Syn-text

* `=== (equal)`
* `|| (or)`
* `! (not)`
* `!== ()`
* `<== (less than and equal too)`
* `>== (greater than and equal too)`

### Example of **Booleans**

```
function isInDanger(grade) {
    return grade >=60 && grade <=71;
}

function isCoasting(grade) {
    return grade >=72 && grade<=83;
}

function isSucceeding(grade) {
    return grade >=84 && grade<=92;
}

function differentPeople(name1, name2) {
    return name1 !== name2;
OR  return !(name1 === name2);
}
```

## **Tuesday** 10/1/19

* **if ()** statements

**function shouldIBuyAHamburger(isHungry, hasMoney)**

```
//If were hungry and don't have money rob a bank.///

    if (isHungry && !hasMoney){
        return 'rob a bank';
}
```

```
//If we have money but were not hungry, save money.///

    if (hasMoney && !isHungry){
        return 'save our money';
 }
```

```
//If we have money and were hungry, buy a hamburger.///

    if(hasMoney && isHungry){
        return 'buy a hamburger';
}
```

```
//If we have NO money and were not hungry, don't buy hamburger.///

    if(!hasMoney && !isHungry){
        return 'don\'t buy hamburger';
}
```

* **else ()** statements `(otherwise)`

```

    if(score > 77){
        response = response + 'good job!'
    } else {
        response = response + 'Keep trying!`
    }
```

* **else if ()** combined to check multiple returns or responses. Makes code more readable in this true false string situation.

```
function grader(score){
    let response = ' ';

    if (score > 77)
}
```

### **Fizz and Buzz**

* Divisible by 3 = fizz
* Divisible by 5 = Buzz
* Divisible by 3 or 5 = fizzBuzz
* Divisible by nothing = nothing gives same number back
* `How to check if Divisible check with MOD (%)`
* `example` 5 % 2 `remainder 1`

## Wednesday 10/2/19

### **Ternary** alternative for ifs and else

* Binary Operates VS Unary Operators VS Ternary Operators
* Binary takes two (2) or more things together
* Unary takes in one (1) thing and show results
* **Ternary** takes in three (3) values resulting in one example: (? 'hello' :)

```
example: const response = (greeting === 'hello') ? 'hello back' : 'salutations'
    let response = ' ';

example: let coinFlip = 'heads';
    const result = coinFlip === 'heads' ? 'you win' : 'you lose'
    result; you win

example: const myRoll = 5;
    const yourRoll = 3;
    const dieRollResult = yourRoll > myRoll
```

#### Do and Don't w/ **Ternary**

* Not made for returning code
* Made for resolving to one value then breaking down the three values

## Thursday 10/3/19

* switch statements are extra credential information to research its an alternative too

### **Side Notes**

* **Inclusive** VS **Exclusive**
* inclusive includes all characters or variables
* exclusive means your excluding the last character or variable.
