# Python_90_days
# Day_1
Counting distinct numbers from a given array

from __future__ import division
n = int(raw_input())
heights = [int(x) for x in raw_input().split()]

#Step 1 - Make Set
distinctHeights = set(heights)

#Step 2 - Summation of Set
sumOfDistinctHeights = sum(distinctHeights)

#Step 3 - Length of Set
totalDistinctHeights = len(distinctHeights)

#Step 4 - Take Average
average = sumOfDistinctHeights/totalDistinctHeights

#Step 5 - Print Output
print average
