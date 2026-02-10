# Lab 04 - SOP/POS and KMaps

In this lab, you’ve learned how to apply KMaps, Sum Of Products and Products of
sums to simplify digital logic equations. Then, you’ve proven out that they work
using an implemented design on your Basys3 boards.

## Rubric

| Item | Description | Value |
| ---- | ----------- | ----- |
| Summary Answers | Your writings about what you learned in this lab. | 25% |
| Question 1 | Your answers to the question | 25% |
| Question 2 | Your answers to the question | 25% |
| Question 3 | Your answers to the question | 25% |

## Lab Summary

In this lab we learned how truth tables and K-maps applied to the BASYS 2 board. We entered the equations we found for the minPOS, maxSOP into our coding files with the variables defined in top.v. In top.v's switches and Leds that were set up to run a 4 variable (A, B, C, D) simulation. We then ran the simulation to figure out if our equations were accurate to our truth tables. Then we were able to apply th ecode to the BASYS 3 board and confirm the hardware was runnin correctly based on our program. 

## Lab Questions

### Why are the groups of 1’s (or 0’s) that we select in the KMap able to go across edges?
The groups of 1's and 0's are able to group across edges because the grid is continuous. This also allows us to make larger groups than if it wasn't applicable.
### Why are the names Sum of Products and Products of Sums?
Product is multiplication and sum is addition. If it is a sum of products we add together multiplied terms. If it is a product of sums we multiply together our sums.
### Open the test.v file – how are we able to check that the signals match using XOR?
In test.v we use XOR logic by only returning true when the values of naive to minterm or maxterm are different. When it returns true if displays a message explaining which SOP or POS was failing. 

