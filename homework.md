POLYMORPHISM

1.	What does the word 'polymorphism' mean?

Poly(many)morphism(forms).


2.	What does it mean when we apply polymorphism to OO design? Give a simple Java example.

When we apply polymorphism to a design, we give our class many different forms. Java example: cars, motorbikes and buses can inherit from their abstract parent class Vehicle. 


The child classes can a add their own attributes and behaviour while still being treated as a vehicle object. We can reuse this code and make it as flexible as we want.


3.	What can we use to implement polymorphism in Java?

Inheritance and interfaces.


4.	How many 'forms' can an object take when using polymorphism?

As many forms as the word being used can cover with it’s own meaning. 


5.	Give an example of when you could use polymorphism.

We can use polymorphism to create subcategories such as Animal being a parent class to dog and cat.


COMPOSITION AND AGGREGATION 

6.	What do we mean by 'composition' in reference to object-oriented programming?

Composition is used for parts of an object that can’t be independent on their own(like car parts; engine, steering wheel, etc…). 


7.	When would you use composition? Provide a simple example in Java.

When your components has-a relationship with it's parent class. 


8.	Give a difference between composition and aggregation?

Composition is used when an object is composed of one or more other objects that cannot exist independently, while aggregation is used when an object is part of another object but can exist independently of it.


9.	What is/are the advantage(s) of using composition/aggregation?

Helps you to create more effective, maintainable, and scalable software systems.


10.	When using composition, when an object is destroyed, what happens to all the objects it is composed of?

If destroyed, then composition becomes dead code.


11.	When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?

The relationship attached to the destroyed object will be dead code, but the components of aggregation can still useable as it has it's own life cycle. 

