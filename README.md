# Quiz-2
• What will be the output when running the above code?
Answer: Meow.I am a cat. My name isKurre.
        Woof.I am a dog. My name isVilma.
        Meow.I am a cat. My name isBamse.
        
• What is meant by polymorphism ?
Answer: Polymorphism means "many forms", and it occurs when we have many classes that are related to each other by inheritance. 
        Like we specified in the previous chapter; Inheritance lets us inherit attributes and methods from another class. 
        Polymorphism uses those methods to perform different tasks.
        
• How does polymorphism work in the above program?
Answer: The polymorphism let the program run the method introduceYourself() in the classes Cat,Dog and Animal to perform in array.

• The method introduceYourself of Animal appears to be never called? Why not?
Answer: Because the method introduceYourself was appears in every clases that the array called.

• Comment out the method introduceYourself in Dog. What happens now when you run the program?
Answer: The output will changed to :
        Meow.I am a cat. My name isKurre.
        Morr.I am an animal.
        Meow.I am a cat. My name isBamse.
        
• Where is the name stored for the instances of Cat and Dog? (In what / which classes did you put the instance variable that refers to the name of the animal? Both Cat and Dog, or just in Animal?)
Answer: The instance of name Cat and Dog was stored in both classes which is calss Cat and class Dog.

• How does the code in the test program work?
Answer: First, the super calss which is the Animal will inherit the method introduceYourself() in all of the classes which is the Cat and Dog. After that the main class which is the Lab1Stage1 will call the the method introduceYourself()
        in every clasess by using polymorphism and print it out in two cat and one dog which is three animal by using array.
        
• How does an array work?
Answer: The array may let the program to run out more than one type of the animal by depends on the arrray length for example 3 animal.

• In the above programs we have used a while loop to step through the array and to get information about the animals. But there is a more appropriate loop statement here. What is it?
Answer: we can also use for loop to step through the array.
        for(i=0; i < allAnimals.length; i++){
        allAnimals[i].introduceYourself();
        
