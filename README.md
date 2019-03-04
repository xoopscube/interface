# Interface 

An abstract data type (ADT) is a mathematical model for data types, where a data type is defined by its behavior (semantics) from the point of view of a user of the data, specifically in terms of possible values, possible operations on data of this type, and the behavior of these operations. This contrasts with data structures, which are concrete representations of data, and are the point of view of an implementer, not a user.

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


Classes in languages like Java and C#, however, also define representation (fields) in addition to behavior (methods). One of the basic tenets of Object-oriented programming is that objects cannot know the representation of other objects even of the same type. However, if you use classes as types, other objects of the same class can know the representation of other objects, even private fields. Therefore, using classes as types breaks Object-oriented programming. (Unfortunately, in both Java and C#, classes are types.)

The only way to do object-oriented programming in Java or C# is to use classes only as factories (i.e. only directly after new) and never as types (i.e. never as the type of a field, return type or parameter type of a method or type argument to a generic type, never cast to a class, never use it with instanceof). And as types, use only interfaces, not classes (and certainly not primitives in Java).

That's what interfaces do: they enable Object-oriented programming in Java and C#. Without them, XOOPSCube Object-oriented programming would simply be impossible in PHP.

[PHP manual : object interface](http://php.net/manual/en/language.oop5.interfaces.php)

Learn more about **Interface** and how to implement from the Wiki documentation examples.