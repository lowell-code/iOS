#DATA TYPES

So in Swift you can simply declare a variable like we did before like in...

```swift 
var isMrJohnsonCool = "hell yea"
```

... but we can specify what data type each variable is using a colon and then the data type.

Editing that previous example... 

```swift 
var isMrJohnsonCoolSpecific: String = "hell yea"
//love you Mr. Johnson!!!
```

If we were to print these two out they would do the same thing. So you're probably asking... 

**Jeremy, why would I do something tedious like that when I could well... not?**

Well let me tell you famsicles (*ok... never saying that again*) 

When you wanna reset these values we can specify what these values can and can only be. 

For example if you have something like...

```swift 
var numberOfMemes = 20
```

You will not want to accidently reset it to something like...

```swift 
numberOfMemes = "TOMATO"
```

If we were to specify the previous example it would look something like this:

```swift 
var numberOfMemes: Int = 20
// We can properly reset it now to this
numberOfMemes = 5000000000000
```

Here are some other data types:

- Int - A whole number.
- Float - A decimal number.
- Double - A double precision decimal number.
- Bool - A boolean value. Can be true or false.
- Character - A single unicode character.
- String - A collection of Character. Used to make words or sentences.

#END OF THE LESSON CHALLENGE THING
Let's go back to our previous Godzilla example. Think about the different data types necessary for each one.

1. Name of Godzilla.

2. Amount of letters in Godzilla.

3. If Godzilla is hungry or nah.

4. Amount of buildings Godzilla destroys.

5. Cost of repairing those buildings Godzilla just destroyed.

6. How pissed the government is at Godzilla.

7. Amount of memes that come out of this terrible tragedy.
