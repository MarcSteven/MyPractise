# MyPractise
In  this demo I mainly wanna decription use struct to create your project.As we all know Struct is value type,so it don't have referecne issue .But How to use struct and class?
You can make a good choice based on the following rules:
Firstly,Both structs and enums are value types, whereas classes are reference types. When designing with structs, we can ask the compiler to enforce immutability. With classes, we have to enforce it ourselves.

Secondly,How memory is managed differs. Structs can be held and accessed directly, whereas class instances are always accessed indirectly through their references. Structs are not referenced but instead copied. Structs have a single owner, whereas classes can have many owners.

Thirdly,Unless a class is marked as final, it can always be inherited from. With structs and enums, inheritance is not possible. Instead, to share code using structs and enums, we need to use different techniques such as composition, generics, and protocol extensions.”

