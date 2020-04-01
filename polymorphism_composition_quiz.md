# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?
	1. Polymorphism means that somthing can have multiple forms.

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.
	2. It means that we can give the impression of multiple jobs or roles to a single object for exmple, method overloading, in this case we can give the same name to many different methods that all take different parameters but give the impression of a single method handling all cases.

3. What can we use to implement polymorphism in Java?
	3. We can use extends and impliments in a parent class to gain access to other atributes of other classes.

4. How many 'forms' can an object take when using polymorphism?
	4. It can take any number of forms. 

5. Give an example of when you could use polymorphism.
	5. We can use this in OO for example with a single ArrayList<> that takes any object rather than specific class object. In this instance it simplifies the constructors instancevairables. 



# Composition

6. What do we mean by 'composition' in reference to object-oriented programming?
	6. We can bring different parts of our programme together to reuse existing code.

7. When would you use composition? Provide a simple example in Java.
	7. We could pull in an exsisting object into our constructure rather than recreating it with in our new class. 

8. What is/are the advantage(s) of using composition?
	8. It keeps our code clean and easy to read, We dont have multiple parts doing the same job we keep single responsibility code and reuse it. 

9. When an object is destroyed, what happens to all the objects it is composed of?
	9. It depends on wether that code was used elsewhere or not, if it was it would continue to work fine if it was only ever used in the destryoed object it wouldnt do anything if it was never called.