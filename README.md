# Cpp-two-sum
C++ solution for Two sum problem

Solution Approach
I first tried a brute force method using nested loops (O(n²) time).
Later, I improved the solution using a hash map (unordered_map in C++), which gives O(n) time complexity.

Key idea:

Store each number’s index in a map.

For each element, calculate the complement (target - nums[i]).

If the complement exists in the map, return both indices.
