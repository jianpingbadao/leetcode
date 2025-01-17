<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](https://github.com/openset/leetcode/tree/master/problems/largest-unique-number "Largest Unique Number")
　　　　　　　　　　　　　　　　
[Next >](https://github.com/openset/leetcode/tree/master/problems/connecting-cities-with-minimum-cost "Connecting Cities With Minimum Cost")

## [1134. Armstrong Number (Easy)](https://leetcode.com/problems/armstrong-number "阿姆斯特朗数")

<p>The k-digit number <code>N</code> is an Armstrong number if and only if the k-th power of each digit sums to N.</p>

<p>Given a positive integer <code>N</code>, return true if and only if it is an Armstrong number.</p>

<p>&nbsp;</p>

<p><strong>Example 1:</strong></p>

<pre>
<strong>Input: </strong><span id="example-input-1-1">153</span>
<strong>Output: </strong><span id="example-output-1">true</span>
<strong>Explanation: </strong>
153 is a 3-digit number, and 153 = 1^3 + 5^3 + 3^3.
</pre>

<p><strong>Example 2:</strong></p>

<pre>
<strong>Input: </strong><span id="example-input-2-1">123</span>
<strong>Output: </strong><span id="example-output-2">false</span>
<strong>Explanation: </strong>
123 is a 3-digit number, and 123 != 1^3 + 2^3 + 3^3 = 36.
</pre>

<p>&nbsp;</p>

<p><strong>Note:</strong></p>

<ol>
	<li><code>1 &lt;= N &lt;= 10^8</code></li>
</ol>

### Related Topics
  [[Math](https://github.com/openset/leetcode/tree/master/tag/math/README.md)]

### Hints
<details>
<summary>Hint 1</summary>
Check if the given k-digit number equals the sum of the k-th power of it's digits.
</details>

<details>
<summary>Hint 2</summary>
How to compute the sum of the k-th power of the digits of a number ? Can you divide the number into digits using division and modulus operations ?
</details>

<details>
<summary>Hint 3</summary>
You can find the least significant digit of a number by taking it modulus 10. And you can remove it by dividing the number by 10 (integer division). Once you have a digit, you can raise it to the power of k and add it to the sum.
</details>
