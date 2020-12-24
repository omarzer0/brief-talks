# brief-talks
1-Singleton Design Pattern: is used when only one instance of a class
can be initialized and can not have multiple instances of that class

it is used oftenly with database instance, when you need only one 
instance across the app and every one who will use the database has
to use the same instance without creating one for its own.

------------------------------------------------------------------------

2-Builder Design Pattern: is mainly used to build a complex object using
simple smaller objects step by step until the Builder class returns the
final complete object

used when have a complex object that can be broken down into a smaller
parts (classes) each of them construct a step (stage) that can be added
together to complete the final object for example building a House class
that has Roof class , Floor class ,Basement class and so on, We can build
each of them and add them together to finally construct the House.

-----------------------------------------------------------------------

3-we use dependency injection to inject the dependency into the dependent
rather than have it in the dependent.

it has a several benefits like changing the dependency during run time,
but the actual use can be represented by Car class which depends on several
components like wheels , engine ,mirrors ,and so on.

so if we want to change let's say the wheels, we will have to change the 
car class to have the new wheels. But with DI you can inject the wheels
to the Car class so the Car will not be concerned with the wheels creation 
and how to implement them.

The DI is like a middle man who the Car class asks him for wheels and he
provides the car with the necessary wheels without having the car to be 
concerned of how the wheels will be created



