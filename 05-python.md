# Learn Python

Read Allen Downey's [Think Python](http://www.greenteapress.com/thinkpython/) for getting up to speed with Python 2.7 and computer science topics. It's completely available online, or you can buy a physical copy if you would like.

[![Think Python](img/think_python.png)](http://www.greenteapress.com/thinkpython/)

For quick and easy interactive practice with Python, many people enjoy [Codecademy's Python track](http://www.codecademy.com/en/tracks/python). There's also [Learn Python The Hard Way](http://learnpythonthehardway.org/book/) and [The Python Tutorial](https://docs.python.org/2/tutorial/).

Complete the following exercises to check your ability with Python.

These exercises are implemented with doctests, which are runnable tests inside docstrings. Fill in the function definitions. Correct solutions will make it possible to run (for example) `python -m doctest strings.py` with no messages about failures.

 * [Strings](python/strings.py)
 * [Lists](python/lists.py)


---

How are Python lists and tuples similar and different? Which will work as keys in dictionaries? Why?

Lists and tuples are similar because they are container objects, which mean they contain other data types such as integer (int), str (string), bool (Boolean), etc. Base on the syntax, list uses square bracket while tupple uses round bracket. One noteworthy difference between list and tuple is that list is mutable, which mean we can add or subtract the number of data, while tuple is immutable, which mean we cannot add or subtract the number of data. Since tuple is immutable and list is mutable, then tuple will work as keys in dictionaries while list will not work. 

---


---

How are Python lists and sets similar and different? Give examples of using both. How does performance compare between lists and sets for finding an element. Why?

Like from the previous questions, both lists and sets are container objects, which mean they contain other data type. Also, both sets and lists are mutable, which mean we can add or subtract the number of data. The notable difference between list and set is that list is an ordered container, which mean each data has a number that verify their location in the list. On the other hand, set is not an ordered container, which mean every reoccuring data will only be shown once such that there is no duplicate data in the set. Since list is an ordered container, we can benefit accessing data base on their location in the list. However, we cannot access set by using positinal access since there is no order in the set object. 

---


---

Describe Python's `lambda`. What is it, and what is it used for? Give at least one example, including an example of using a `lambda` in the `key` argument to `sorted`.

Lambda is an awesome feature in python. It acts similar to python function but it requires less effort to create. As a mathematician, lambda function acts more closely related to mathematical function. 

Lambda example>>> g = lambda x: x^2

---


---

Explain list comprehensions. Give examples and show equivalents with `map` and `filter`. How do their capabilities compare? Also demonstrate set comprehensions and dictionary comprehensions.

List comprehensions 

---


Write a Markov text generator, [markov.py](python/markov.py). Your program should be called from the command line with two arguments: the name of a file containing text to read, and the number of words to generate. For example, if `chains.txt` contains the short story by Frigyes Karinthy, we could run:

```bash
./markov.py chains.txt 40
```

A possible output would be:

> show himself once more than the universe and what I often catch myself playing our well-connected game went on. Our friend was absolutely correct: nobody from the group needed this way. We never been as the Earth has the network of eternity.

There are design choices to make; feel free to experiment and shape the program as you see fit. Jeff Atwood's [Markov and You](http://blog.codinghorror.com/markov-and-you/) is a fun place to get started learning about what you're trying to make.
