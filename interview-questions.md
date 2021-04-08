# ASSESSMENT 4: Interview Practice Questions
Answer the following questions.

First, without external resources. Challenge yourself to answer from memory.

Then, research the question to expand on your answer. Even if you feel you have answered the question completely on your own, there is always something more to learn. Write your researched answer in your OWN WORDS.  

1. What is an instance variable in Ruby? How is it different from other variables?

  Your answer: instance variables are variables that are only accessible by the object it refers to.

  Researched answer: An instance variable has a name beginning with @, and its scope is confined to whatever object self refers to. Two different objects, even if they belong to the same class, are allowed to have different values for their instance variables. From outside the object, instance variables cannot be altered or even observed (i.e., ruby's instance variables are never public) except by whatever methods are explicitly provided by the programmer. As with globals, instance variables have the nil value until they are initialized. Instance variables of ruby do not need declaration. This implies a flexible structure of objects. In fact, each instance variable is dynamically appended to an object when it is first referenced.



2. What is a block in Ruby?

  Your answer: Ruby blocks are nameless code blocks in which they essentially do the same thing as a method and do not refer to an object. They are enclosed with do/end.

  Researched answer: Blocks consits of chunks of code and function like methods; however they do not belong to an object. A block is always invokes with a function or are passed to a method call. To call a block within a method, yield statements are used. Blocks can be called just like methods from inside the method that is passed to it. 



3. Ruby has an implicit return. What does that mean?

  Your answer: Ruby will automatically return the value of the last line of executable code. It makes it able that a "return" is not needed when coding.

  Researched answer: when return isn't explicitily called within a method then ruby returns the value of the last executed instruction in the method.



4. What is object-oriented programming? How is it different than functional programming?

  Your answer: Object oriented programming is when objects represent what we are programming, while functional programming relies on arguements of the function.

  Researched answer: Functional programming is the form of programming that attempts to avoid changing state and mutable data. In a functional program, the output of a function should always be the same, given the same exact inputs to the function. Object oriented programming is a programming paradigm in which you program using objects to represent things you are programming about (sometimes real world things). These objects could be data structures. The objects hold data about them in attributes. The attributes in the objects are manipulated through methods or functions that are given to the object.



5. What is the difference between a class and an object?

  Your answer: A class provides the blueprints for an object while an object is an instance of a class.

  Researched answer: A class is an entity that determines how an object will behave and what the object will contain. An object is nothing but a self-contained component that consists of methods and properties to make a data useful.



6. STRETCH: What is `attr_accessor`?

  Your answer: Attribute accessor allows us to access properties without the need to create a new getter method for every single object attribute. 

  Researched answer: It allows the creation of methods to assign and to read instance variables so one does not have to define the methods themselves.



## Looking Ahead: Terms for Next Week
- MVC
The Model-View-Controller (MVC) is an architectural pattern that separates an application into three main logical components: the model, the view, and the controller. The Model component corresponds to all the data-related logic that the user works with. The View component is used for all the UI logic of the application. Controllers act as an interface between Model and View components to process all the business logic and incoming requests, manipulate data using the Model component and interact with the Views to render the final output.

- PostgreSQL
It is is an advanced, enterprise class open source relational database that supports both SQL (relational) and JSON (non-relational) querying. Essentially a data handler.

- API
An application programming interface is a computing interface that defines interactions between multiple software or mixed hardware-software intermediaries. It defines the kinds of calls or requests that can be made, how to make them, the data formats that should be used, the conventions to follow, etc.

- CRUD
Create, read, update, and delete are the four basic operations of persistent storage.

- Ruby on Rails
Rails is a development tool which gives web developers a framework, providing structure for all the code they write. The Rails framework helps developers to build websites and applications, because it abstracts and simplifies common repetitive tasks.
Rails is written in Ruby, the programming language which is also used alongside Rails. 

- ORM
Object-relational mapping in computer science is a programming technique for converting data between incompatible type systems in object-oriented programming languages.

- Active Record
Active Record facilitates the creation and use of business objects whose data requires persistent storage to a database. It is an implementation of the Active Record pattern which itself is a description of an Object Relational Mapping system.
