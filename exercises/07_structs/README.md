# Structs

Rust has three struct types:
* classic C struct
  * named fields
  * fields can be mutable & private
  * fields defined inside {}.

* tuple struct - uple structs have the added meaning the struct name provides but don’t have names associated with their fields; rather, they just have the types of the fields.
  * uses () instead of {}.
* unit struct - Unit-like structs can be useful when you need to implement a trait on some type but don’t have any data that you want to store in the type itself.

# Struct methods:
* similar to functions: we declare them with the fn keyword and a name.
* first parameter is always self.
* start stuct methods with impl (implementation) block declaration.


## Further information

- [Structures](https://doc.rust-lang.org/book/ch05-01-defining-structs.html)
- [Method Syntax](https://doc.rust-lang.org/book/ch05-03-method-syntax.html)
