Dictionary
===============

**Dictionary constructor:**

    * `a_dict = {}`
    * `a_dict =  dict()`
    * `a_dict = {key : value for key, value in sequence}`
    * `a_dict = dict.fromkeys(sequence)`

* Dictionary is a collection data type
* Dictionary store data as key-value pair
* Keys are distinct
* Indexed(keys are distinct and can be used as index)
* Dictionary can contain heterogeneous data type(different types of data eg. int, str, float, list, tuple, dict, queue, stack, tree...)
* Mutable
* Itarable(Default iterator is key)

**Add an element:**

    * `a_dict[key] = value`

**Remove an element:**

    
    * `clear()`
    
        * Remove all the key-value pairs in a_dict.
    
    * `pop(i)`
    
        * Pop the given key and return the popped pair
    
    * `popitem()`
    
        * Pop the last key-value pair and return the popped pair.
    
    * `del`
    
        * `del a_dict[key]`, Delete the key-value pair in a_dict
        * `del a_dict`, Delete a_dict

**Access the elements of dictionary:**

    * By key
    
        * a_dict[key], key should be present in a_dict else raise an exception.
    
    * `get(key[, default_value])`
    
        * `a_dict.get(key)` returns the value associated with given key, if key is not present None
        * `a_dict.get(key, default_value)` returns the value associated with given key, if key is not present it return the default_value.

**Other functionalities:**

    
    * `copy()`

        * Copy the dictionary to new dictionary
    
    * `keys()`

        * Returns dict_keys([key1, key2, ...])
    
    * `values()`

        * Returns the dict_values([value1, value2, ...])
    
    * `update()`

        * Update the dictionary with given key-value pair.
    
    * `items()`

        * Returns dict_item((key1, value1), (key2, value2), ...)
    
    * `setdefault(key[, value])`

        * Return value of key in dictionary if key exists, else set value of key in it
