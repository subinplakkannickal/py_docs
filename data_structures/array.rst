Array
===============

* Array is a collection of items stored together in sequence of memory location
* Array can store only homogeneous data type
* Data in the array can be accessed by index
* Memory location of next item in array  is depended on data type of array 

+-------+---------------------------+-----------+
| Type  | CType                     | size(byte)|
+=======+===========================+===========+
| B/b   |unsigned/signed char       | 1         | 
+-------+---------------------------+-----------+
| u     | Python Unicode            | 2         |
+-------+---------------------------+-----------+
| H/h   | Unsigned/signed short     | 2         | 
+-------+---------------------------+-----------+
| I/i   | Unsigned/signed int       | 2         | 
+-------+---------------------------+-----------+
| L/l   | UnSigned/signed long      | 4         | 
+-------+---------------------------+-----------+
| f     | Float                     | 4         |
+-------+---------------------------+-----------+
| Q/q   | Unsigned/signed long long | 8         | 
+-------+---------------------------+-----------+
| d     | Double                    | 8         | 
+-------+---------------------------+-----------+

**Functionalities**

* `append(x)`
* `insert(i, x)`
* `pop(i)`
* `remove(i)`
* `index(x)`
* `reverse()`
