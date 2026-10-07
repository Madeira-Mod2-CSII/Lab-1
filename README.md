# Lab 1: String, List \& Function Review

## Exercise 1: 
Write a function ```username(first, last)``` that returns a person's username. It should be the last name followed by an underscore and first inital of the first name. For instance, ```username("Ebert", "Eric")``` should return ```Ebert_E```.

*Hint:* Use concatenation and string indexing.

## Exercise 2: 

Write a function ```noVowels(text)``` that returns a version of the string ```text``` with all vowels replaced with a space. For example, ```noVowels("nextTerm")``` should return ```n xtT rm```. **Hint:** Use the ```replace``` method and a list of vowels.

Documentation for ```replace``` can be found here:
[replace](https://docs.python.org/3/builtins/stdtypes.html#str.replace)


## Exercise 3: 

Suppose you develop a code that replaces a string with all even indexed characters followed by all odd indexed characters:

- ```computers -> cmuesoptr```

Write a function ```encode(word)``` that returns the encoded version of the word.

*Hint:* A nice trick is to use slicing. You can find a description of slicing here:
[slicing](https://python-reference.readthedocs.io/en/latest/docs/brackets/slicing.html)


## Exercise 4: 

Write a function ```decode(word)``` that reverses the process from the encode function.


*Note:* These exercises are taken from *Discovering Computer Science* by Jessen Havill