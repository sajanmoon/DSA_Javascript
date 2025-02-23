# Big O Notation

# Time Complexity

- We will calculate time complexity mainly on a graph of n(lets say number of operartion) and runtime required for it
- <img src="./images/graph.png" alt="Image Description" width="600">
- We will have O(1) > O(n) > O(n²)
- <img src="./images/Examples.png" alt="Image Description" width="600">

## O(1)

- To calculate this things we will need to know the number of operation
- More the number of operation more will be time complexity
- <img src="./images/Screenshot 2025-02-23 124744.png" alt="Image Description" width="600">
- for eg refer to image where arithmetic operation will only take 1 operation
- for eg 2+2 will take same time as compare to 100 + 100

## O(n)

- <img src="./images/Screenshot 2025-02-23 124744.png" alt="Image Description" width="600">
- As we can see the no of operation are incresing in image it will take more runtime so here we will have O(n)
- Because as the operation will the runtime will also be increase, shown in below graph
- <img src="./images/BigOn.png" alt="Image Description" width="600">
- <img src="./images/OnExample.png" alt="Image Description" width="600">
- here we have two O(n) so we will have a O(2n) but still we will count it as a O(n) as we see genral trend no matter cnstants

## O(n²)

- In O(n²) the runtime will increases double in a graph of no of operation
- for eg
- here we have nested loop here we will get a upward curve graph
- <img src="./images/n2example.png" alt="Image Description" width="600">
- <img src="./images/n2graph.png" alt="Image Description" width="600">
- <img src="./images/contantdontmatter.png" alt="Image Description" width="600">
-

# Space Complexity

- How much additional memory do we need to allocate in order to run the code in our algoritm
- Most primitive(booleans, numbers, undefined, null)are contants
- String require O(n) space (where n is a string length)
- Refrence types are genrally O(n),where n is the length for arrays or the number of keys for object
- O(1) example
- <img src="./images/timeO1.png" alt="Image Description" width="600">
- O(n) example
- <img src="./images/timeOn.png" alt="Image Description" width="600">

## logarithm examples (log(n))

- <img src="./images/logexample.png" alt="Image Description" width="600">

-
