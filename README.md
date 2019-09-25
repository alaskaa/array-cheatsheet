# Array Cheatsheet

Cheatsheet for a bunch of array methods I forget all the time - what did unshift do again?


# Methods

StackEdit stores your files in your browser, which means all your files are automatically saved locally and are accessible **offline!**

## Adding & Removing items

### array.push()
Adds one or more items to the end of an array. If called, returns the new length of the array. Modifies the existing array.

### array.pop()
Removes the last item of an array. If called, returns the removed item. Modifies the existing array.

### array.unshift()
Adds one or more items to the beginning of an array. If called, returns the new length of the array. Modifies the existing array

### array.shift()
Removes the first item of an array. If called, returns the the removed item. Modifies the existing array.

## Iterating through the array

### array.map()
Calls a specified function on each item in the array. Returns a new array with new elements that have been created.

### array.forEach()
Calls specified function on each item in the array. It DOESN'T return anything. 

### array.filter()
Filters the array based on a given condition. Returns results in a new array.

### array.sort()
Sorts the array based on given criteria.

### array.every()
Tests whether all items / every item in the array pass the test given by provided function you pass. Returns a boolean value.

### array.some()
Checks whether at least one item in the given array passes the test implemented by the passed in function. Returns boolean value (returns false if it's called on an empty array).

## Splice vs Slice

### array.splice()
Changes the contents of the array by inserting or replacing items in the array

### array.slice()
Creates a shallow copy of the array its being called on. Extracts up to but not including the end. Both beginning and end are optional.


## Merging arrays

### array.concat()
Merges two arrays into a single array.

## Check if a value exists in array

### array.includes()
Checks whether the given value is present in the array. Returns true or false based on the findings.

### array.indexOf()
Returns first index of item where it passes the test function, otherwise it returns -1.

### array.lastIndexOf()
Returns the last index at which a given element can be found in the array, or -1 if it is not present. The array is searched backwards, starting at fromIndex (optional argument, defaults to array.length - 1).

## Other useful utilities

### array.join()
Joins the contents of an array into a string. Defaults to comma separated, if you provide separator, separator will be used instead.

### array.fill()
Fills up an array with given number (first argument). Optional second and third argument that indicate start and end where the number is supposed to be filled in.

### array.find()
Returns value of first element in the array that passes the given test function.

### array.findIndex()
Returns index of first element in array that passes the given test function.

### array.flat()
Creates a new array with flattened structure up to given depth (optional argument).

### array.reverse()
Reverses the contents of an array. Modifies the existing array - destructible.

### array.from()
Creates a new, shallow-copied Array instance from an array-like or iterable object.

### array.of()
Creates an array of the given arguments. Numbers are treated as such, meaning array.of(7) will create an Array [7], not as the usual Array(7) which would create 7 empty slots.


## Returning Array Iterator Objects

### array.entries()
Returns a new Array Iterator object that contains the key/value pairs for each index in the array.

### array.values()
returns a new  Array Iterator object that contains the values for each index in the array.

### array.keys()
returns new Array Iterator object that contains all the keys for each index in the array.

## Other

### array.toString()
Returns a string of the elements in the array - comma separated.

### array.toLocaleString()
The `toLocaleString()` method returns a string representing the elements of the array. The elements are converted to Strings using their `toLocaleString` methods and these Strings are separated by a locale-specific String (such as a comma “,”).

### array.copyWithin()
Shallow copies part of an array to another location in the same array and returns it without modifying its length.


## reduce and reduceRight()

TO DO 


## Check whether Array is really array

### array.isArray()
Returns boolean based on whether argument passed is an array or not. True if an array, false otherwise.
