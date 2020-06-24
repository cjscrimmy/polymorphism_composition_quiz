# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?
A. Something that can take many different forms.

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.
A. When used in OO design, polymorphism means that an object created based on a class can take different forms.
Example -

    Person person = new Person(); 
    Person person = new Doctor(); 
    Person person = new Lawyer(); 


3. What can we use to implement polymorphism in Java?
A. We can use inheritance to implement polymorphism in Java. 
We can create a parent class and child classes that extend from
the parent class and inherit the parent's properties.

4. How many 'forms' can an object take when using polymorphism?
A. An object can take as many forms as there are child classes 
attached to a parent class as well as the form of the parent class. 
e.g if a parent class has 4 child classes then the object can 
take 5 forms. 

5. Give an example of when you could use polymorphism.
A. Polymorphism could be used when modelling a car
dealership. You can a Vehicle class with default properties
and then a few child classes to model the behaviour associated 
with different types of car.



# Composition

6. What do we mean by 'composition' in reference to object-oriented programming?
A. Composition means that an object is built using other objects inorder to use their 
properties.

7. When would you use composition? Provide a simple example in Java.
A. You would composition when you need an object to make use of behaviour
that another object has already implemented.

Example-

    public class Bicycle{
        private Tyre tyre1; 
        private Tyre tyre2; 
        private Saddle saddle; 
        private Peddle peddle1;
        private Peddle peddle2; 
    }

8. What is/are the advantage(s) of using composition?
A. An advantage is that an can be composed of multiple other objects.
An other advantage is that it helps stop code duplication in multiple places.

9. When an object is destroyed, what happens to all the objects it is composed of?
A. When an object is destoryed, the objects it is composed of are destoryed too.