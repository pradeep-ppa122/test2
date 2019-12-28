filter(...)
    filter(function or None, sequence) -> list, tuple, or string

    Return those items of sequence for which function(item) is true.  If
    function is None, return the items that are true.  If sequence is a tuple
    or string, return the same type, else return a list.
    
    map(lambda x,y: x+y, [1,1])
    f = filter(lambda i:i%2 ==0, l)
    g = filter(lambda i:i%2 <>0, l)
    
    >>> for i in l:
...   if(i%2==0):
...     total += i*i
...
>>> total
    
