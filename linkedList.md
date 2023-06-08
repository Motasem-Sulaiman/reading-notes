# Linked List

## What is the Big(O) :
 Big O notation is a mathematical notation that describes the code complexity , it refer to the input relation in your code , the lowest Big(O) the better .

Time complexity : the time that your code need to execute .

Space complexity : the space that your code need .

![](./BigO.png)

examples :




-reading from the array [1,2,3,4,5,6.....]   arr[400]  ===>O(1)  it takes constant amount of time

          function print(n){

          for(let i=0;i<n;i++){ ===> O(n)  depends on the number of n

          console.log(i)}} ===>O(1)    

the big(O) for the function is : O(1) * O(n) ==> O(n)

## What is the LinkedList :
 a sequence of nodes that are connected-linked to each other.

 ![](./Singly-Linked-List1.png)

-Node : each node contains the data for each link.

-Next : each node contains a property called next. This property contains the reference to the next node.

-Head : the head is a reference of type node to the first node in a linked list.

-Tail : the tail is a reference of type node to the last node in a linked list.