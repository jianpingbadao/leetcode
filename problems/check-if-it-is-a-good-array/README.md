<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](https://github.com/openset/leetcode/tree/master/problems/minimum-remove-to-make-valid-parentheses "Minimum Remove to Make Valid Parentheses")
　　　　　　　　　　　　　　　　
[Next >](https://github.com/openset/leetcode/tree/master/problems/average-selling-price "Average Selling Price")

## [1250. Check If It Is a Good Array (Hard)](https://leetcode.com/problems/check-if-it-is-a-good-array "检查「好数组」")

<p>Given an array <code>nums</code> of&nbsp;positive integers. Your task is to select some subset of <code>nums</code>, multiply each element by an integer and add all these numbers.&nbsp;The array is said to be&nbsp;<strong>good&nbsp;</strong>if you can obtain a sum of&nbsp;<code>1</code>&nbsp;from the array by any possible subset and multiplicand.</p>

<p>Return&nbsp;<code>True</code>&nbsp;if the array is <strong>good&nbsp;</strong>otherwise&nbsp;return&nbsp;<code>False</code>.</p>

<p>&nbsp;</p>
<p><strong>Example 1:</strong></p>

<pre>
<strong>Input:</strong> nums = [12,5,7,23]
<strong>Output:</strong> true
<strong>Explanation:</strong> Pick numbers 5 and 7.
5*3 + 7*(-2) = 1
</pre>

<p><strong>Example 2:</strong></p>

<pre>
<strong>Input:</strong> nums = [29,6,10]
<strong>Output:</strong> true
<strong>Explanation:</strong> Pick numbers 29, 6 and 10.
29*1 + 6*(-3) + 10*(-1) = 1
</pre>

<p><strong>Example 3:</strong></p>

<pre>
<strong>Input:</strong> nums = [3,6]
<strong>Output:</strong> false
</pre>

<p>&nbsp;</p>
<p><strong>Constraints:</strong></p>

<ul>
	<li><code>1 &lt;= nums.length &lt;= 10^5</code></li>
	<li><code>1 &lt;= nums[i] &lt;= 10^9</code></li>
</ul>

### Related Topics
  [[Math](https://github.com/openset/leetcode/tree/master/tag/math/README.md)]

### Hints
<details>
<summary>Hint 1</summary>
Eq.  ax+by=1 has solution x, y if gcd(a,b) = 1.
</details>

<details>
<summary>Hint 2</summary>
Can you generalize the formula?.  Check Bézout's lemma.
</details>
