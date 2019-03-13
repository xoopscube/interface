# Interface 

### Interfaces - the next level of abstraction

Interfaces resemble abstract classes in that they include abstract methods that the programmer must define in the classes that inherit from the interface. In this way, interfaces contribute to code organization because they commit the child classes to abstract methods that they should implement. The use of interfaces becomes very helpful when we work in a team of programmers and want to ensure that all the programmers write the methods that they should work on, or even in the case of a single programmer that wants to commit himself to write certain methods in the child classes.

`An interface commits its child classes to abstract methods that they should implement.`

An **interface** defines the signature operations of an entity, it also sets the communication boundary between two entities, in this case two pieces of software. It generally refers to an abstraction that an asset provides of itself to the outside.

The main idea of an interface is to separate functions from implementations. Any request that matches the signature or interface of an object may also be sent to that object, regardless of its implementation.

Since it does not matter which implementation of a specific class is used, a class can be exchanged easily without changing the code of the calling class.

The concept of an interface is fundamental in most object oriented programming languages. In some, objects are known only through their interfaces so there is no way to access an object without going through it's interface.

### Applicability / Uses

Use an interface when:

* you want to specify how classes exchange messages. I.e., every time, when a class should be reused, or used outside a specific context (package) declare the communication interface as an Interface type
* you have to switch the implementation of a module during run-time at design-time you don't yet know which implementation you will use at compile-time

### Related Patterns

Many other patterns use interfaces, a lot of them depend on the interface pattern.
It is possible to combine the interface pattern with virtually any other pattern to make them more flexible.

* [Interfaces : the next level of abstraction](https://phpenthusiast.com/object-oriented-php-tutorials/interfaces)

* [PHP manual : object interface](http://php.net/manual/en/language.oop5.interfaces.php)

* [PHP manual : class abstraction](http://php.net/manual/en/language.oop5.abstract.php)

Learn more about **Interface** and how to implement from the Wiki documentation examples.

* [XCL : documentation](https://github.com/xoopscube/documentation)
