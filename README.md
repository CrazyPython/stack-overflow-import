# StackOverflow Importer

Do you ever feel like all you're doing is copy/pasting from Stack Overflow?

Yeah. I thought so. Let's take it one step further.

```{python3}
Python 3.5.0 (v3.5.0:374f501f4567, Sep 13 2015, 02:16:59) [MSC v.1900 32 bit (Intel)] on win32
>>> from stackoverflow import quick_sort, split_into_chunks

>>> print(quick_sort.sort([1, 3, 2, 5, 4]))
[1, 2, 3, 4, 5]
>>> print(list(split_into_chunks.chunk("very good chunk func")))
['very ', 'good ', 'chunk', ' func']
>>> print("gotta take a break")
gotta take a break
>>> from time import time
>>> t1 = time()
>>> from stackoverflow import time_delay
>>> print("that's enough, let's continue coding", time() - t1)
that's enough, let's continue coding 5.7283220291137695
>>> print("I wonder who made split_into_chunks", split_into_chunks.__author__)
I wonder who made split_into_chunks https://stackoverflow.com/a/35107113
>>> print("but what's the license? Can I really use this?", quick_sort.__license__)
but what's the license? Can I really use this? CC BY-SA 3.0
>>> assert("nice, attribution!")
```