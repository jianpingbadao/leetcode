<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](https://github.com/openset/leetcode/tree/master/problems/valid-palindrome-iii "Valid Palindrome III")
　　　　　　　　　　　　　　　　
[Next >](https://github.com/openset/leetcode/tree/master/problems/longest-arithmetic-subsequence-of-given-difference "Longest Arithmetic Subsequence of Given Difference")

## [1217. Play with Chips (Easy)](https://leetcode.com/problems/play-with-chips "玩筹码")

<p>There are some chips, and the i-th chip is at position <code>chips[i]</code>.</p>

<p>You can perform any of the two following types of moves <strong>any number of times</strong> (possibly&nbsp;zero) <strong>on any chip</strong>:</p>

<ul>
	<li>Move the <code>i</code>-th chip&nbsp;by&nbsp;2 units to the left or to the right with a cost of <strong>0</strong>.</li>
	<li>Move&nbsp;the <code>i</code>-th chip&nbsp;by&nbsp;1 unit to the left or to the right with a cost of&nbsp;<strong>1</strong>.</li>
</ul>

<p>There can be two or more chips&nbsp;at the same position initially.</p>

<p>Return the&nbsp;minimum cost needed to move all the chips to the same position (any position).</p>

<p>&nbsp;</p>
<p><strong>Example 1:</strong></p>

<pre>
<strong>Input:</strong> chips = [1,2,3]
<strong>Output:</strong> 1
<strong>Explanation:</strong> Second chip will be moved to positon 3 with cost 1. First chip will be moved to position 3 with cost 0. Total cost is 1.
</pre>

<p><strong>Example 2:</strong></p>

<pre>
<strong>Input:</strong> chips = [2,2,2,3,3]
<strong>Output:</strong> 2
<strong>Explanation:</strong> Both fourth and fifth chip will be moved to position two with cost 1. Total minimum cost will be 2.
</pre>

<p>&nbsp;</p>
<p><strong>Constraints:</strong></p>

<ul>
	<li><code>1 &lt;= chips.length &lt;= 100</code></li>
	<li><code>1 &lt;= chips[i] &lt;= 10^9</code></li>
</ul>

### Related Topics
  [[Greedy](https://github.com/openset/leetcode/tree/master/tag/greedy/README.md)]
  [[Array](https://github.com/openset/leetcode/tree/master/tag/array/README.md)]
  [[Math](https://github.com/openset/leetcode/tree/master/tag/math/README.md)]

### Hints
<details>
<summary>Hint 1</summary>
The first move keeps the parity of the element as it is.
</details>

<details>
<summary>Hint 2</summary>
The second move changes the parity of the element.
</details>

<details>
<summary>Hint 3</summary>
Since the first move is free, if all the numbers have the same parity, the answer would be zero.
</details>

<details>
<summary>Hint 4</summary>
Find the minimum cost to make all the numbers have the same parity.
</details>
