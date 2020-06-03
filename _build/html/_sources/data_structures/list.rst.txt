List
===============
| List is a built in data structure in python. Lists are used to store hetrogeneous data in sequencial order.
| List is a mutable data structure, so it means that an element of list can be manipulated.
| The elements of list can be accessed by index.

**List construction:**

    A list can be created in following ways in  python.

    * `a_list = []`
    * `a_list = list()`
    * `a_list = [i for i in sequence]` (List comprehension)

**Add elements to list:**

    * `append(x)`

        * `append` will add an object to the end of the list.
        * `a_list.append(element)`, The element can be any python object like `int`, `str`, `float`, `list`, `tuple`, `dict` or any other ojects.

    * `extend(b_list)`

        * Add elements to the end of list.
        * a_list.extend(object), object can be any type of sequence.

    * `insert(i, x)`

        * Adding an element to the given index
        * `a_list.insert(i, object)`, `i` should be an integer and object can be any python object.

**Remove an element:**

    * `remove(obj)`

        * Remove the object from the list.
        * a_list.remove(object), object should be present in `a_list`

    * `pop(*i)`

        * Remove the element at the given index if index passes else the last element and return the popped element. 
        * `a_list.pop(i)`, Pop the element at `i` and return. I should be an integer and < `len(a_list)`
        * `a_list.pop()`, pop the last element and return.

    * `del`

        * Delete the a_list object.
        * `del a_list`

**Access the elements of list:**

    * `By index`

        * `a_list[i]`, `i` should be an integer and < `len(a_list)`.

    * `By slicing`

        * `a_list[:]`, Return all elements in `a_list`
        * `a_list[i1:i2]`, Return all elements in `a_list` from index i1 to `i2` excluding `i2`.
        * `a_list[i1:i2:s]`, Return all elements in `a_list` from index i1 to `i2` in step s excluding `i2`.
        * `a_list[::-1]`, Return all elements in `a_list` in reverse order.

**Other functionalities:**

    * `sort()`

        * `sort()` Sort the existing list. Eg. `a_list.sort()`, ** `sorted(list)` Return a new list which is sorted. Eg. `sorted(a_list)`.

    * `count(obj)`

        * Return the number of occurrence of obj in `a_list`

    * `index(obj)`

        * Return the position of the first occurrence of obj in `a_list`

