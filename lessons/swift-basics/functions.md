#FUNCTIONS

 Alright alright. Let's get into the nitty gritty of FUNCTIONS.
 
 ```swift 
   func functionThing(){
    ///empty function   
   }
 ```
 
 That's an empty function. Pretty straightforward right?
 
 Good. Let's talk about parameters then.
 
 ```swift 
   func printWord(word: String){
    print(word)   
   }
   
   //More than one parameter
   
   func printWords(word1: String, word2: String){
    print(word1 + " " + word)
   }
 ```
 
 Make sure you know what data type you're gonna take in when declaring your parameters.
 
 Coolio. On to return types.
 
```swift 
   func addNums(int1: Int, int2: Int){
    return int1+int2
   }
 ```
 
 When calling a function make sure you fill in the appropriate parameters.
 
 ```swift 
   func addNums(int1: Int, int2: Int){
    return int1+int2
   }
   
   print(addNums(1,9))
   //prints 10
 ```
 
 Pretty basic right? Challenge time!
 
 #END OF THE LESSON CHALLENGE THING
 
 1. Create a function called ```calculateTipTotal```. This function should calculate the tip for a dollar cost and return the total bill.
 
 2. Create a function that checks if a number is divisible by 3 (The modulo operator, %, should be helpful here). It should return either true or false.
 
 3. Create a function that creates a todo list (an array) for Godzilla. It should do 3 things: add things to the list, delete things from the list, and replace things. It should return the final array.
