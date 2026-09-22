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

Summarize your learnings from the lab here.

## Lab Questions

### Why are the groups of 1’s (or 0’s) that we select in the KMap able to go across edges?
Since you can visualize the ends of the KMaps as a loop, they would be able to go across the edges.
### Why are the names Sum of Products and Products of Sums?
Sum of Products is since it's finding the ORs of each of the signal from each circuit while the Product of Sums is finding what has already been found and calculating the product of those sums.
### Open the test.v file – how are we able to check that the signals match using XOR?
If it equals the same, the test case would pass since we are looking for the inverse of XOR, the only test case that would pass would be when both signals are equal.
