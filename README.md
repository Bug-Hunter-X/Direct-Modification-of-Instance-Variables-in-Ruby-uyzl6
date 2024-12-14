# Direct Modification of Instance Variables in Ruby

This example showcases a common coding error in Ruby related to direct manipulation of instance variables outside the defined methods of a class.  While it might seem convenient, this practice can lead to several problems such as:

* **Maintainability:**  Changes to instance variables are not tracked or managed within the class's methods. This makes debugging and future modification difficult.
* **Encapsulation Violation:** The principle of encapsulation is violated. The internal state of the class is directly exposed.
* **Unexpected Behavior:** This can lead to inconsistencies and unexpected behavior in larger applications.

The solution shows how to use accessor methods to correctly interact with the internal state of a class, enhancing code reliability and maintainability.