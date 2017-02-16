#CONTROL FLOW

Let's get right into it homies. Starting with...

##IF STATEMENTS 

```swift
  let isTrue = true
  
  if isTrue {
    print("Eyy lmao it's true")
  } else {
    print("You dumb cuz it's false")
  }
  //prints "Eyy lmao it's true"
```
You may notice that we don't use parenthesis in these ```if``` statements. They are optional in Swift.

Make sense? Let's continue.

##FOR-IN LOOPS

For-in loops are essentially for loops but with a few modifications. Let's look at them.

```swift
  for x in 1..<5 {
    print(x)
  }
  //prints 1 2 3 4
```

Ok... what did we just do? 

The first part of a for-in loop is declaring a variable. Then we give this variable something to loop through.

Let's look at some other examples

```swift
  //loop through an array
  let coolArray: [String] = ["this", "array", "is", "pretty", "dank"]
  
  for coolString in coolArray {
    print(coolString) 
  }
  //prints "this" "array" "is" "pretty" "dank"
  
  //loop less than and equal to
  for num in 1...5{
    print(num)
  }
  //print 1 2 3 4 5
```

##WHILE LOOPS 
```swift
  var x: Int = 0
  
  while x < 60 {
    x+=1
    //there is no ++ in swift
  }
  print(x)
  //Print 60
```

##SWITCH 

Switch statements reall cool cuz it's basically a giant if statement with multiple cases. Example time.

```swift
  let coolGuy = "Jeremy"
  
  switch coolGuy {
  //First declare what thing you're checking. In this case it's the variable coolGuy
  case "Raymond:
    print("Shut up Raymond!")
  case "Makayla":
    print("Why are you complaining to me???")
  case "Yev":
    print("lol")
  case "Jeremy":
    print("Who else could it be?")
  default:
    print("Who?")
  }
  
  //prints "Who else could it be?"
```

So what you're gonna do is come up with each different possibility. However, you need to come up with a default case.


#END OF THE LESSON CHALLENGE THING

1. Let's start this thing easy. Create an loop that will print from 0 to one billion.

2. Let's create a switch statement on what city Godzilla will destroy today. Create different cases for New York, San Francisco, Dallas, and Tulsa. Print "Take that Wall Street", "Take that Western Hippies", "Howdie", and "Where's Tulsa?" for each respective case. Your default case will be "Error! City not found!" 


