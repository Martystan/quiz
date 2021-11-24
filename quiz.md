# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?

    The word polymorphism means existing in or assuming different forms.

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

    It means that if we have a class of Vehicle, a Car class that inherits from it and implements an interface of IDrive, an instance of a Car class, will be of type Vehicle, Car type and IDrive type, it will be able to take take many forms.

3. What can we use to implement polymorphism in Java?

    We can implement polymorphism through inheritance and interfaces.

4. How many 'forms' can an object take when using polymorphism?

    Depends on the length of the inheritance chain and number of interfaces implemented, I imagine it may be infinite.

5. Give an example of when you could use polymorphism.

    As per example from q2, I would use polymorphism at any time where I see similarities between classes and I expect similar behaviours from certain objects. Therefore if there were another class inheriting from the Vehicle called Bicycle, I would want it to share certain properties with the Car, such as perhaps wheels and brakes. They would also share certain behaviours however they would implement them differently, so it would make sense to implement an interface that would ensure that both vehicles have certain methods such as perhaps IBrake or IStart. If I apply polymorphism the code is much "drier" as I don't have to give certain properties and write certain methods for all the vehicles as I know that they all share them so they can be inherited and interfaces can be implemented as appropriate.



# Composition and Aggregation

6. What do we mean by 'composition' in reference to object-oriented programming?

    Compositions means that objects are a part of other objects. 

7. When would you use composition? Provide a simple example in Java.
    For example a Car that has a property of colour and a model can also have a property of an Engine that is another object which can have a property of size. It can also have methods that can be the used by the Car object. 

8. Give a difference between composition and aggregation?

    With composition, we see an object as being A PART OF another object whereas aggregation refers to a HAS A relationship, where an object has other objects.

9. What is/are the advantage(s) of using composition/aggregation?
    The structure is more flexible as class have only inherit from one other class but it can be composed of many objects.

10. When using composition, when an object is destroyed, what happens to all the objects it is composed of?
     When the object is destroyed all of the objects it is composed of are also destroyed.

11. When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?
        With aggregation objects that the object is composed of exist independently so if the object is destroyed they still exist.