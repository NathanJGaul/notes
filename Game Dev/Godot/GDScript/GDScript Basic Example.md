# GDScript Basic Example

    # A file is a class!
    
    # Inheritance
    
    extends BaseClass
    
    # Member Variables
    
    var a = 5
    var s = "Hello"
    var arr = [1, 2, 3]
    var dict = {"key": "value", 2:3}

    # Constants

    const ANSWER = 42
    const THE_NAME = "Charly"

    # Enums

    enum {UNIT_NEUTRAL, UNIT_ENEMY, UNIT_ALLY}
    enum Named {THING_1, THING_2, ANOTHER_THING = -1}

    # Built-in Vector Types

    var v2 = Vector2(1, 2)
    var v3 = Vector3(1, 2, 3)

    # Function

    func some_function(param1, param2):
      var local_var = 5

      if param1 > local_var:
        print(param1)
      elif param2 > 5:
        print(param2)
	  else:
	    print("Fail!")

      for i in range(20):
        print(i)

      while param2 != 0:
        param2

> Written with [StackEdit](https://stackedit.io/).
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTExNDc1OTczODNdfQ==
-->