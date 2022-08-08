# Generics

Generics introduces the concept of type parameters which makes it possible to design classes and methods that defer the specification of one or more types until the class or method is declared and instantiated by client code.

By using a generic type parameter T, you can write a single class that other client code can use without incurring the cost or risk of runtime casts or boxing operations.

Generic classes and methods combine reusability, type safety, and efficiency in a way that their non-generic counterparts cannot.

Generics are most frequently used with collections and the methods that operate on them.

The type parameter T is used in several locations where a concrete type would ordinarily be used to indicate the type of the item stored in the list. 

In the given implementation, it is used as the type of a method parameter in the CalculateSalary method.
