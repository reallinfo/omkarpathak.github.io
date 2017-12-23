---
    layout: default
    title: Pygorithm
    permalink: /projects/pygorithm/
---

# Pygorithm
What is the project all about?

- A Python module to learn all the major algorithms on the go!
- Users just have to import the required module and they can use the functions, see the code and time complexities

## Results

* To sort your list

{% highlight python %}
    >>> from pygorithm.sorting import bubble_sort
    >>> my_list = [12, 4, 3, 5, 13, 1, 17, 19, 15]
    >>> sorted_list = bubble_sort.sort(my_list)
    >>> print(sorted_list)
    >>> [1, 3, 4, 5, 12, 13, 15, 17, 19]
{% endhighlight %}

* To get the code for function used

{% highlight python %}
    >>> from pygorithm.sorting import bubble_sort
    >>> code = bubble_sort.get_code()
    >>> print(code)
{% endhighlight %}

* To get the time complexity of an algorithm

{% highlight python %}
    >>> from pygorithm.sorting import bubble_sort
    >>> time_complexity = bubble_sort.time_complexities()
    >>> print(time_complexity)
{% endhighlight %}

**Source Code**: [Github](https://github.com/OmkarPathak/pygorithm)