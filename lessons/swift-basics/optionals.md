#OPTIONALS

Ok so this was the topic that fladoodled with my mind the most when I first was trying to learn Swift, so I will try to explain this to the best of my ability.

An optional is kinda like a Shrodinger's Cat situation for Swift. In other words, an optional has the *option* to not contain a value in it.

Confused already? Let's make an example.

An optional is declared by placing a question mark next to the variable's data type.

```swift
  var maybeAString: String? = "meh"
```

But you guys will say **Uhhh... Jeremy, that's just a basic variable with a questin mark you stupid, incapable leader.**

To that I say **Ouch** and **You misspelled question mark** and **That question mark makes a huge difference**

Putting a question mark there means that there doesn't need a value or not just yet. 

We could've easily done this...

```swift
  var maybeAString: String?
```

And we would not need to do anything at all. We would get no errors, and we wouldn't need to assign any values to it if we don't want to.
 
**But why tho...**
 
Say you wanted to have a variable but you wanted to not set the value immediately, like a text box that will take in a user input. 
You wouldn't want to set that text value immediately if there's no text to save just yet.
 
But we cannot simply call on optionals like we do normally because there might be no value at all to save, and this will cause an annoying error.
 
To get an optionals value we need to **unwrap** it.
 
Just like in real life we can do this two ways, forcefully or passive aggresively (better known as *implicitly*).
 
To forcefully unwrap an optional we add an exclamation point at the end of the declaration.
 
```swift 
 var optionalString: String? = "optional"
 print(optionalString!)
 //prints optional
```
 
Forcing unwrapping is easy and great if you know that there will be a value there for sure, but it has a higher chance of totally wrecking your code. Forceful unwrapping does not check if there is an actual value in the variable. So it can actually be unwrapping nothing.
 
The safer but more tedious option is implicit unwrapping.
 
```swift 
  var optionalString: String? = "optional"
  
  if optionalString != nil {
    print(optionalString!)
   } else {
    print("No value for optionalString")
   }
```
 
Implicit unwrapping uses an ```if``` statement to check if there is an actual value to the optional and is the overall safer way to deal with optionals. (*We'll cover Swift if statements later*)

#END OF THE LESSON CHALLENGE THING
Think of some cases where an optional will be used and if it will be better if you implicitly or forced unwrapped it.
 
