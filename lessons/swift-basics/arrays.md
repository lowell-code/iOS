#ARRAYS

Let's jump right into it. Here's how to create an array in Swift.

```swift
  var swiftArray: [String] = ["one", "two"]
```

Make sure you declare the array type within the square brackets when making the array.

Let's look at some ways we can do stuff with arrays.

```swift
  var swiftArray: [String] = ["one", "two"]
  
  //Count
  print(swiftArray.count)
  //Prints two because there are two elements in the array
  
  //Adding and taking away stuff
  swiftArray.append("three")
  print(swiftArray)
  //Prints ["one", "two", "three"]
  
  swiftArray.insert("two and a half", at: 2)
  print(swiftArray)
  //Prints ["one", "two", "two and a half", "three"]

  
  swiftArray.remove(at: 2)
  print(swiftArray)
  //prints ["one", "two", "three"]
```

Those are some swaggy things to do with those arrays.

#END OF THE LESSON CHALLENGE THING

1. Create an array for Godzilla's morning routine. This should include "wake up", "wash up in the ocean", "floss teeth", "polish scales". Print the array when you're done.

2. Godzilla thinks it's a good idea to destroy Dallas for change. Add "destroy Dallas" to the list and print it when you're done.

3. Godzilla's teeth are pretty nice today so let's remove that from the list. Print it again fam.

4. Godzilla wants to eat some nuclear warheads before polishing her scales. Let's add that to the array.
