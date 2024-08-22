# SET
About set in set category data type
-> To store multiple values of same or different data types with uniqe values in a single object is called set category data type.
-> Set category data types are 2 types
   1)Set
   2)Frozen set
1)set:
-> set is a pre_deifined class.
Notation: {val1,val2,,,,,valn}
-> Set never mentain insertion order
-> So we can't perform indexing, slicing.
-> set is immutable because it can't perform item assignment.
-> set is mutable because we can perform operations in same address.
=> They are two types of set
   i) Empty set
   syntax: setobj = set()
           setobj ={}     => It is not empty set, it is dict.

   ii)non-empty set()
   syntax:  setobj = {val1,val2,,,,,valn}

   **set functions**
   1)add()
   syntax: setobj.add(value)

   2)clear()
   syntax: setobj.clear()

   3)remove()
   syntax: setobj.remove(value)

   4)discard()
   syntax:  setobj.discard(value)

   5)pop()
   syntax: setobj.pop()
   This fuction delete last value of object

   6)copy()
   syntax: s1=s2.copy()

   7)isdisjoint()
   syntax: s1.disjoint(s2)

   8)issuperset()
   syntax: s1.issuperset(s2)
   ->If s1 has all elements of s2 then s1 is superset of s2.
   ->s1 is also superset of set()
   ->Every set is superset to it's self.

   9)issubset()
   syntax: s1.issubset(s2)
   -> if s2 has all elements of s1 then s2 called subset of s1.
   ->set() is subset of s2.
   ->every set is subset to it's self.

   10)union()
   syntax: s3 =s1.union(s2)
   -> This Function is used for combining OR Mergining all the Unique Elements of setobj1 and setobj2 and placed the 
    elements in setobj3.

    11)intersection()
    Syntax:   setobj3=setobj1.intersection(setobj2)
    ->This Function is used for Obtaining the Common Elements Between setobj1 and setobj2.
    ->If no commen elements between setobj1 and setobj2 then this function gives set().

    12. difference()
    Syntax:   setobj3=setobj1.difference(setobj2)
    ->This Function Removes the common Elements from setobj1 and setobj2 and takes the Remaining Elements from 
    setobj1 and place them in setobj3.

    13. symmetric_difference()--Most imp---Maths Denoated as Delta
    Syntax:   setobj3=setobj1.symmetric_difference(setobj2)
    ->This Function Removes the common Elements from setobj1 and setobj2 and takes the Remaining Elements from 
    setobj1 and setobj2  and place them in setobj3.

    14. difference_update()
    Syntax:   setobj1.difference_update(setobj2)
    ->This Function Removes the common Elements from setobj1 and setobj2 and takes the Remaining Elements from 
    setobj1 and place them in setobj1 itself.

    15. symmetric_difference_update()
    ->Syntax:  setobj3=setobj1.symmetric_difference_update(setobj2)
    ->This Function Removes the common Elements from setobj1 and setobj2 and takes the Remaining Elements from 
    setobj1 and setobj2  and place them in setobj1 itself.

    16. update()
    Syntax:   setobj3=setobj1.update(setobj2)
    ->This function is used for Adding all Elements of setobj2 to setobj1( setobj1 updated with setobj2 elements)
     and setobj3 contain Nothing which is denoted as None.

   
