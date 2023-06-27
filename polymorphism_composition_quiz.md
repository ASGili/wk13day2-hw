# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?
A: Polymorphism means that given the same input, you can get multiple outputs

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.
A: It means that on different occasions the instance of a class acts as if it is an instance of a different class. If you had an ArrayList<Vehicle> and Vehicle had a subclass called Car then an instance of Car could be polymorphic to a Vehicle and therefore be allowed to populate the ArrayList.

3. What can we use to implement polymorphism in Java?
A: inheritance and interfaces

4. How many 'forms' can an object take when using polymorphism?
A: infinite but only one at a time

5. Give an example of when you could use polymorphism.
A: If you had an ArrayList<Vehicle> and Vehicle had a subclass called Car then an instance of Car could be polymorphic to a Vehicle and therefore be allowed to populate the ArrayList.


# Composition and Aggregation

6. What do we mean by 'composition' in reference to object-oriented programming? A: Composition is when an instance of one class is made up of instances of another class or classes.

7. When would you use composition? Provide a simple example in Java. 
A: Composition is used when creating classes from other classes, such as if an instance of the class of Book had instances of a class of Pages.

8. Give a difference between composition and aggregation?
A: Composition is when the associated classes cannot be uncoupled, aggregation is when they can be.

9. What is/are the advantage(s) of using composition/aggregation?
A: composition is more strict and therefore more secure, aggregation is less strict and therefore more flexible.

10. When using composition, when an object is destroyed, what happens to all the objects it is composed of?
A: They are also destroyed.

11. When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?
A: They can still exist but they are no longer related to the destroyed object.