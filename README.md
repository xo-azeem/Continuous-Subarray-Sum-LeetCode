# Continuous Subarray Sum

LeetCode Q # 523.

Given an integer array nums and an integer k, return true if nums has a good subarray or false otherwise.

A good subarray is a subarray where:

- Its length is at least two, and the sum of the elements of the subarray is a multiple of k.</br>

Note that:

A subarray is a contiguous part of the array.</br>
An integer x is a multiple of k if there exists an integer n such that x = n * k. 0 is always a multiple of k.
 

Example 1:

>Input: nums = [23,2,4,6,7], k = 6</br>
>Output: true</br>
>Explanation: [2, 4] is a continuous subarray of size 2 whose elements sum up to 6.

Example 2:

>Input: nums = [23,2,6,4,7], k = 6</br>
>Output: true</br>
>Explanation: [23, 2, 6, 4, 7] is an continuous subarray of size 5 whose elements sum up to 42. 42 is a multiple of 6 because 42 = 7 * 6 and 7 is an integer.

Example 3:

>Input: nums = [23,2,6,4,7], k = 13</br>
>Output: false</br>

My Solution Analysis:

<div align = "center">

  ![image](https://github.com/xo-azeem/Continuous-Subarray-Sum-LeetCode/assets/171427226/da5520bf-3cd9-49ef-9d0e-560755740fd7)

  Time complexity: O(n).</br>Space complexity: O(n).
</div>
