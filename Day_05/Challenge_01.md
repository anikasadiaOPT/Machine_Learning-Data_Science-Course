# The speed Trap (Look up) #

List: 
When searching a number or value from a list,
the computer has to go through each item one by one that is very time consuming. Suppose, we have 1M data in the list and are trying to find -1's index,the search time increases linearly(O(N)) with the size of the data as it can be taken more time to find -1 from that list. 

Set/ Dict:
In contrast, set or dictionary use hashing. Using set, we will get the unique value. The values are accessed by keys in dict.
When we search a value(-1) , the computer called the hashing function to find the memory address(e.g. 0x99) and only reaches to that location.  
So these are less memory efficient because of maintaining hash table  but faster than list as it reaches directly to the location O(1).