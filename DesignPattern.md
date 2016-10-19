book refers to - “Design Patterns: Elements of Reusable object-Oriented Software”

1. Factory Method: 

	# Intent
	By defining an interface, you are allowed to device which class to instantiate. This lets a class defer its instantiation to subclasses.

	# Main idea
	Use abstract classes to define and maintain relationships between classes, and objects. Usually a factory method is used to generate an instance of an object. It encapsulates the knowledge a subclass creates and move it out of the main framework.

	# Consequences
	According to the book, there are two main consequences. Provides hooks for subclasses, and Connects parallel class hierarchies.

	# My explanation of implementation
	Create abstract class for a type of class, eg. a pizza store class. This serves as the factory methods’ base. Other subclasses would implement and “new” corresponding objects, e.g. cheese pizza store class would use a method to generate a “CheesePizza” class.