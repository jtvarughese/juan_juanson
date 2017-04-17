Lesson Objectives:
- Explain the relationship between `.new()` and `def initialize()`.
  * '.new()' calls the initialize method 'def initialize()'.

- Define class, subclass, instance, and self.
  * Class is a blueprint which contains all the default attributes & actions of each instance.
  * Subclass is a class within a class. It inherits from a parent class.
  * Instance is an instance of a class or sub class. It is an object generated from that blueprint.
  * Self is a way for the instance to refer to itself. Basically, the equivalent of 'this' in javascript.

- Properly define `instance` and `class` variables.
  * Instance variables are variables available within the instance. Starts with @ symbol.
  * Class variables are variables available within the class.

- Properly define `instance` and `class` methods.
  * Class methods are methods that are called on a class.
  * Instance methods are methods that are called on an instance of a class.

- Distinguish whether a piece of data is best suited to being stored in a local, instance, or class variable.
  * Local variables are only available in the method it was created in.
  * The instance variable has an @ symbol before the variable name. It is only needed within that instance and not the method: a specific value within a class such as @hair_color on a class Person.
  * Class variables have the same properties but different value which would be the instance variables.

- Describe the relationship of `attr_` and "getter" and "setter" methods.
  * 'attr_writer' is the shortcut for setter methods. Setters take the argument and applies it to the parameter to give a value.
  * 'attr_reader' is the shortcut for the getter methods. Getters retrieve the value of the instance variable.
  * 'attr_accessor' is the best of the both worlds. It is the shortcut that emcompasses both the attr writer and reader.

- Distinguish whether a piece of data is best suited to having its accessibility defined by attr_reader,
  attr_writer, attr_accessor or none of the above.
  * 'attr_reader' is best used for pulling the value when it's from a setter. It's much less to type and can be used to "get" the value.
  * 'attr_writer' is best used for the setting the value of instance variables.
  * 'attr_accessor' is best when you need a attr writer and reader. This is a shortcut for both.
