# The speed Trap (Look up) #

List: 
From list when we wanna find any specific value or number,
we have to go through each item one by one that is very time consuming. 
Suppose, we have 1M data in the list and are trying to find -1,
we can't even count how much time can be taken to find -1 from that list. 

Set/ Dict:
In contrast, set or dictionary use hashing. The values are accessed by keys.
When we search a key(-1) , the key converted into a hash, then it finds the memory address(e.g. 0x99)
and only returns the value.
So these are memory efficient and faster than list.