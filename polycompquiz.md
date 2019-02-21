Polymorphism & Composition Homework - Quiz
Polymorphism

1. What does the word 'polymorphism' mean?
    "many formed"- essentially it is the idea of something being able to manifest itself in different forms.

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.
    In Java, polymorphism is when an object(s) can be realised as 2 or more different types (achieved via casting).
    An example would be when an a class Object (say "x") implements additional methods from an interface (say "y").
    The object is now polymorphic in that it can be treated equally validly as "x" or "y".

3. What can we use to implement polymorphism in Java?
    Abstract Classes and/or interfaces

4. How many 'forms' can an object take when using polymorphism?
    As many as necessary but always at least 2.

5. Give an example of when you could use polymorphism.
    When you have a collection of objects that have a shared property (that being the property that matters)
    but which also have their own properties/methods that you might also need to access.
    A specific example was in the Theme Park homework. A rollercoaster was an attraction was something that could be reviewed
    and subject to a price change.
    In this respect it was important that Rollecoaster could be considered both an "ITicketed" object and an "IReviewed" object
    whilst in a sense still being a rollercoaster.

Composition
6. What do we mean by 'composition' in reference to object-oriented programming?
    Composition is what is used to implement HAS-A type relationships. In Java this is achieved
    via the use of interfaces where classes can implement additional methods.

7. When would you use composition? Provide a simple example in Java.
    You might have a collection of similar classes but you need some of
    these to also be able to have additional methods.
    An example might be if you have a collection of shapes. Some of those might be 2-D
    and some of those might be 3-D. 3-D shapes "have a" volume whereas 2-D don't
    Composition would allow the 3-D shapes to have a "volume" method by implementing and interface.

8. What is/are the advantage(s) of using composition?
    It means that specified behaviours/methods are only acquired by those objects that require them.
    In inheritance all classes would in inherit the methods of the abstract class
    even if some of those class did not actually need the additional methods.

9. What happens to the behaviours when the object composed of them is destroyed?
    They're gone too as, due to the fact that the Object HAS the behaviours, the behaviours cannot exist without the object.
