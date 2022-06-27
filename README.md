# Binary-Search-Time-and-Space-complexity
## Searching 
# 1) Binary Search :
       #Finding an element in the array/list.
       #Binary search is a searching technique that is based upon the Divide-and-Conquer Rule.
# Working process:
    In Binary Search,
       # 1.For Binary Search to be performed on any array, the array must be already sorted in 
          any format, that is, either ascending or descending.
       # 2.Find the middle index of the array/list.
       # 3.If the middle element is equal to the search element, Stop Searching and then 
           return 'element is found' at so and so index.
       # 4.If the element that is to be searched is less then the middle element then consider
           the first half as a separate list.
       # 5.Else-If the element that is to be searched is larger then the middle element then 
           consider the second half as a separate list.
       # 6.Repeat Step 2-3-4-5 Until desired result is found.

*Time complexity :           
# a)Best case = O(1)          
# b)Worst case = O(log n)
# c)Average case = O(log n)

*Space complexity :
O(1)
