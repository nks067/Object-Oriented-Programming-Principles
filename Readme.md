# Object-oriented programming  

    Object-oriented programming (OOP) organize software as a collection of discreate object that incorporate both data structure and behaviors. 

    Objects contain data, in the form of fields (often known as attributes or properties), and code in the form of procedures (often known as methods). 

## Some Important point about object oriented programing. 

    1. Each Objects have its own identity. 

    2. Each class describe a possibly infinite no set of individual objects. Each object is said to be instance of an class. 

    3. Each instance of a class (Object) has its own value for each attribute but share the attribute name and operation. 

    4. Object-oriented programming is a conceptual process independent of a programing language. 
 

## Why OOP?  

    OOP makes code organized, reusable, and easy to maintain; It follows the DRY method (Don’t Repeat Yourself). Benefits of OOP include security; OOP prevents unwanted access to data, or exposing proprietary code through encapsulation and abstraction  

    In OOP everything is an object. Classes form the blueprint for how data & behaviors are structured. 

    Objects are created for specific instances of a class. As a programmer, you might create a dog class (blueprint) as a standard way to organize all the important information about dogs, and then instantiate an individual dog as an object created from the dog class - like your dog Fluffy. 

## OOPs Concepts Building Blocks: 

* Class 

    In a nutshell, classes are essentially user defined data types. Classes are where the programmer creates a blueprint where they define some attributes and behaviors. Individual objects are instantiated, or created from this blueprint.  

    For Example: - 

    we define Animal as class. This Animal class have name, age and food as an attribute and eat as behavior (Method) 

    ![Class](https://github.com/nks067/Object-Oriented-Programming-Principles/blob/master/img/Animal.png)

* Object 

    Objects are instances of classes created with specific data, for example cat is an instance of the animal class and it contain value for each attribute.

    ![Object](https://github.com/nks067/Object-Oriented-Programming-Principles/blob/master/img/Cat.png)

* Attribute 

    Attributes are the information that is stored. Attributes are defined in the Class template. When objects are instantiated, individual objects contain data stored in the Attributes field. 

    For Example, cat object has value store in name, age and food field. 
 

* Method 

    Methods represent behaviors. Methods perform actions; methods might return information about an object, or update an object’s data.  

    For Example, the animal class have a method eat that display the food information eaten by a particular animal object. 

    Note: -  

    Operation is an action or transformation that an object performs. A specific implementation of operation by a certain class is called method. 


## Four principles of OOP 

* Encapsulation 

    Encapsulation is containing all important information inside an object, and only exposing selected information to the outside world. Then, when an object is instantiated from the class, the data and methods are encapsulated in that object.  

    Encapsulation allows us to protect the data stored in a class from system-wide access. We can implement encapsulation keeping the fields (class variables) private and providing public. 

    By making fields private no one can see what’s behind the object’s curtain. 

* Abstraction 

    Abstraction hides the implementation details while just presenting the feature to the outside world. 

    For example, you don’t have to know all the details of how the engine works to drive a car. The engineering is hidden from the driver. 

    In terms of OOP when we use any object and call method then we don't need to bother about internal implementation of that method. So, in above mention example when we have animal object(cat) then we simply call eat () method without knowing the implementation of eat method. 

* Polymorphism 

    Polymorphism allows the same method to execute different behaviors. 

* Inheritance 
    Inheritance allows classes to inherit features of other classes. Put another way, parent classes extend attributes and behaviors to child classes. Inheritance supports reusability – if basic attributes and behaviors are defined in a parent class, child classes can be created extending the functionality of the parent class, and adding additional attributes and behaviors. 

    For Example, we have a Dog class. French Bulldogs are a special type of dog that requires more attention than your average dog. We can create a child class French Bulldog from the parent class Dog, and then add behaviors. 

    ![Inheritance](https://github.com/nks067/Object-Oriented-Programming-Principles/blob/master/img/Inheritance.png)

 
 

## Benefits of OOP 

 
 
 
 

 