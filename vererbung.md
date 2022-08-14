# Vererbung

...auch _Inheritance_.

- several different classes can have a common origin
- keyword "extends"
- when an object is created, the constructor of its base class is first called
- inheriting class has access to the fields of the base class
- moreover, we can explicitly call the base class constructor in the child class constructor
  -> base class = "superclass"
  -> keyword "super" to indicate the base class

## Vererbungsablauf

(order if you have static variables inside inheriting class and base class)

1. static variables of the base class are initialized
2. static variables of the child class are initialized
3. non-static variables of the base class are initialized
4. the base class constructor starts
5. non-static variables of the child class are initialized
6. the inheriting class constructor starts
