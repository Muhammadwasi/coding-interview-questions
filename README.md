# Motivation :muscle:

I truly believe that whenever we want to learn something, we should be able to explain it in simple words. 
This practice can help us to break down a concept in simple words. That is also called as **Feynman's Technique**. 
In this repository, I am trying to do the same by simplifying concepts in question answer format.

Instead of simply describing the concept, I formatted the content in question answer manner and all those questions are in collapsible toggle which you can see on click.
It helps us to try to think about the content before seeing the actual answer. 

## Contributions are welcome :hearts:

It is an open source project. Anyone can contribute valuable content in this repository.

* Fix typos or errors
* Add new questions or sections
* Improve questions or sections

# Java

## Strings


<details>
    <summary>Why Strings are immutable?</summary>

1. String needs to be thread safe. Why? because of String Pool.
    * String objects are shared and cached in String Pool between multiple threads. 
If Strings wouldn't be mutable, there is always a risk of some thread changing the shared string. For example, if a thread changes a String "Test1" to "Test2", the new value will be visible to all threads.
2. We use String as a key in Map. If Strings were mutable, anyone can change the value of the strings, and we would lose the actual key.
</details>

<br/>
<details>
  <summary>Difference between String literal vs String object?</summary>

* String literal is a language concept e.g "**It's a literal string**". They are cached and shared in String pools.
* String object is an instance of `java.lang.String` class
</details>

<br/>
<details>
<summary>Difference between == sign and equals?</summary>

* `==` compares the references in heap
* `equals` compares the value of the references, by default. We can also change it as this method can be overridden.
</details>

# License

The resources and code in this repository are available under open source license.

