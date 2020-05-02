# Computational thinking
* Representing and structuring information and ideas
* Systematically processing information with algorithms 

7 key elements
--------------
### loops 
- doing something over and over with a counter to track how many times you do it; they have to terminate after X times or when a certain condition is reached
- for data processing
```
for { counter=1 to 10 } { do something with counter/STATEMENT/S }
```

### conditionals
- control program flow
- for data processing 
- IF x is true, THEN y
```
if (argument to be evaluated as TRUE/FALSE) { STATEMENT 1 } else { STATEMENT 2 }
```

### lists
- aggregating elements together to operate on them as a set
- sequential and numbered ordered set, referred to by index number
- for data representation
```
dogs[0] = "poodle"; dogs[1] = "labradoodle"; dogs[2] = "pitbull";
```

### objects
- composed of elements
- something like a face
- for data representation
- textual form is comprised of name:value pairs:
```
kitchen = { "numForks": 6,
			"ovenSize": large,
			"makeCake": function }
```

### functions
- take an input, operate on it, return something else
- can be defined
- algorithmic implementation of data
- can be used over again even with different "ingredients"
- for data processing
```
makeCake = function(ingredients aka "INPUT"){recipe steps; return cake aka STATEMENT/S}
```

### timers
- animated web content
- can present new element after every few seconds
```
setTimeout( {do something}, 1 day )
```
explanation of above: A list of statements to be executed when timer fires, and amount of time that it will wait before executing statements

### events
- generic name, because an event is hard to define
- when something happens, it is considered an event
- like pressing a button (the event), when it happens, that's when we can execute code
- for structuring how information is processed over time
```
onClick( {do something} )
```
