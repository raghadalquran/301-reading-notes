# SUMMARY #

**What is functional programming?**
Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data
**Pure functions benefits**
The code’s definitely easier to test. We don’t need to mock anything. So we can unit test pure functions with different contexts:
- Given a parameter A → expect the function to return value B.
- Given a parameter C → expect the function to return value D.
When data is immutable, its state cannot change after it’s created.
If you want to change an immutable object, you can’t. Instead, you create a new object with the new value.
### pure functions + immutable data = referential transparency ###
- You’ve probably already heard about filter, map, and reduce. Let's take a look at these.

**Filter**

Given a collection, we want to filter by an attribute. The filter function expects a true or false value to determine if the element should or should not be included in the result collection. Basically, if the callback expression is true, the filter function will include the element in the result collection. Otherwise, it will not.


**Map**

The idea of map is to transform a collection.
The map method transforms a collection by applying a function to all of its elements and building a new collection from the returned values.
