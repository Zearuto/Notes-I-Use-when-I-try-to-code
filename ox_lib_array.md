Shared
lib.array
A table used as a prototype for the Array class. Functions can be used as class methods or standard functions.

lib.array:new
Constructs instance of Array containing the given elements.

lib.array:new(...)
...: any
Returns:

arr: Array
lib.isArray
Determines if the given table is an instance of Array or an array-like table.

lib.array.isArray(tbl)
tbl: table
Returns:

isArray: boolean
lib.array.merge
Combines the elements of two arrays into a new array.

a: Array
b: Array
lib.array.merge(a, b)
Returns:

Array
lib.array.every
Tests if all elements in an array succeed in passing the provided test function.

arr: Array
testFn: function
lib.array.every(arr, testFn)
Returns:

success: boolean
lib.array.filter
Creates a new array containing the elements from an array that pass the provided test function.

arr: Array
testFn: function
lib.array.filter(arr, testFn)
Returns:

arr: Array
lib.array.find
Returns the first element of an array the passes the provided test function.

arr: Array
testFn: function
reverse?: boolean
Iterate over the array in reverse order.
lib.array.find(arr, function(element) end, reverse)
Returns:

element: unknown
lib.array.findIndex
Returns the index of the first element of an array the passes the provided test function.

arr: Array
testFn: function
reverse?: boolean
Iterate over the array in reverse order.
lib.array.findIndex(arr, function(element) end, reverse)
Returns:

index: number
lib.array.indexOf
Returns the index of the first element of an array the matches the provided value.

arr: Array
value: any
reverse?: boolean
Iterate over the array in reverse order.
lib.array.indexOf(arr, value, reverse)
Returns:

index: number
lib.array.forEach
Executes the provided function for each element in an array.

arr: Array
cb: function
lib.array.forEach(arr, function(element) end, reverse)
Returns:

index: number
lib.array.join
Concatenates all elements of an array into a string, separated by commas or the specified seperator.

arr: Array
seperator?: string
lib.array.join(arr, seperator)
Returns:

str: string
lib.array.pop
Removes the last element from an array and returns the value.

arr: Array
lib.array.pop(arr)
Returns:

element: unknown
lib.array.push
Adds the given elements to the end of an array and returns the new array length.

arr: Array
...: any
lib.array.push(arr, ...)
Returns:

length: number
lib.array.shift
Removes the first element from an array and returns the value.

arr: Array
lib.array.shift(arr)
Returns:

element: unknown
lib.array.reduce
The "reducer" function is applied to every element in an array, with the previous result serving as the accumulator.
If an initial value is provided it's used as the accumulator for the first index; otherwise iteration starts at the second index, with the first index as the accumulator.

arr: Array
reducer: function
initialValue?: any
lib.array.reduce(arr, function(accumulator, element, index) end)
Returns:

accumulator: unknown