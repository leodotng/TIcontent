# Big O notation

Big O notation is used in Computer Science to describe the performance or complexity of an algortihm. Big O specifically describes the worst-case scenario, and can be used to describe the execution time retuire or the space used(eg in memory or on disk by an algorithm).




## O(1) describes an algorithm that will always exectute in the same time (or space) regardless of the size of the input data set.

```
bool IsFirstElementNull(IList<string> elements)
{
    return elements[0] == null;
}
```


## O(N) describes an algorithm whose performance will grow linearly and in direct proportion to the size of the input data set.

```
bool ContainsValue(IList<string> elements, string value)
{
    foreach (var element in elements)
    {
        if (element == value) return true;
    }
    return false;
}
```

##O(N^{2})