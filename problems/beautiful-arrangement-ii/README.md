<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](https://github.com/openset/leetcode/tree/master/problems/path-sum-iv "Path Sum IV")
　　　　　　　　　　　　　　　　
[Next >](https://github.com/openset/leetcode/tree/master/problems/kth-smallest-number-in-multiplication-table "Kth Smallest Number in Multiplication Table")

## [667. Beautiful Arrangement II (Medium)](https://leetcode.com/problems/beautiful-arrangement-ii "优美的排列 II")

<p>
Given two integers <code>n</code> and <code>k</code>, you need to construct a list which contains <code>n</code> different positive integers ranging from <code>1</code> to <code>n</code> and obeys the following requirement: <br/>

Suppose this list is [a<sub>1</sub>, a<sub>2</sub>, a<sub>3</sub>, ... , a<sub>n</sub>], then the list [|a<sub>1</sub> - a<sub>2</sub>|, |a<sub>2</sub> - a<sub>3</sub>|, |a<sub>3</sub> - a<sub>4</sub>|, ... , |a<sub>n-1</sub> - a<sub>n</sub>|] has exactly <code>k</code> distinct integers.
</p>

<p>
If there are multiple answers, print any of them.
</p>

<p><b>Example 1:</b><br/>
<pre>
<b>Input:</b> n = 3, k = 1
<b>Output:</b> [1, 2, 3]
<b>Explanation:</b> The [1, 2, 3] has three different positive integers ranging from 1 to 3, and the [1, 1] has exactly 1 distinct integer: 1.
</pre>
</p>

<p><b>Example 2:</b><br />
<pre>
<b>Input:</b> n = 3, k = 2
<b>Output:</b> [1, 3, 2]
<b>Explanation:</b> The [1, 3, 2] has three different positive integers ranging from 1 to 3, and the [2, 1] has exactly 2 distinct integers: 1 and 2.
</pre>
</p>

<p><b>Note:</b><br>
<ol>
<li>The <code>n</code> and <code>k</code> are in the range 1 <= k < n <= 10<sup>4</sup>.</li>
</ol>
</p>

### Related Topics
  [[Array](https://github.com/openset/leetcode/tree/master/tag/array/README.md)]

### Similar Questions
  1. [Beautiful Arrangement](https://github.com/openset/leetcode/tree/master/problems/beautiful-arrangement) (Medium)
