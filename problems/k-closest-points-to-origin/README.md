<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](https://github.com/openset/leetcode/tree/master/problems/equal-rational-numbers "Equal Rational Numbers")
　　　　　　　　　　　　　　　　
[Next >](https://github.com/openset/leetcode/tree/master/problems/subarray-sums-divisible-by-k "Subarray Sums Divisible by K")

## [973. K Closest Points to Origin (Medium)](https://leetcode.com/problems/k-closest-points-to-origin "最接近原点的 K 个点")

<p>We have a list of <code>points</code>&nbsp;on the plane.&nbsp; Find the <code>K</code> closest points to the origin <code>(0, 0)</code>.</p>

<p>(Here, the distance between two points on a plane is the Euclidean distance.)</p>

<p>You may return the answer in any order.&nbsp; The&nbsp;answer is guaranteed to be unique (except for the order that it is in.)</p>

<p>&nbsp;</p>

<div>
<p><strong>Example 1:</strong></p>

<pre>
<strong>Input: </strong>points = <span id="example-input-1-1">[[1,3],[-2,2]]</span>, K = <span id="example-input-1-2">1</span>
<strong>Output: </strong><span id="example-output-1">[[-2,2]]</span>
<strong>Explanation: </strong>
The distance between (1, 3) and the origin is sqrt(10).
The distance between (-2, 2) and the origin is sqrt(8).
Since sqrt(8) &lt; sqrt(10), (-2, 2) is closer to the origin.
We only want the closest K = 1 points from the origin, so the answer is just [[-2,2]].
</pre>

<div>
<p><strong>Example 2:</strong></p>

<pre>
<strong>Input: </strong>points = <span id="example-input-2-1">[[3,3],[5,-1],[-2,4]]</span>, K = <span id="example-input-2-2">2</span>
<strong>Output: </strong><span id="example-output-2">[[3,3],[-2,4]]</span>
(The answer [[-2,4],[3,3]] would also be accepted.)
</pre>

<p>&nbsp;</p>

<p><strong>Note:</strong></p>

<ol>
	<li><code>1 &lt;= K &lt;= points.length &lt;= 10000</code></li>
	<li><code>-10000 &lt; points[i][0] &lt; 10000</code></li>
	<li><code>-10000 &lt; points[i][1] &lt; 10000</code></li>
</ol>
</div>
</div>

### Related Topics
  [[Heap](https://github.com/openset/leetcode/tree/master/tag/heap/README.md)]
  [[Sort](https://github.com/openset/leetcode/tree/master/tag/sort/README.md)]
  [[Divide and Conquer](https://github.com/openset/leetcode/tree/master/tag/divide-and-conquer/README.md)]

### Similar Questions
  1. [Kth Largest Element in an Array](https://github.com/openset/leetcode/tree/master/problems/kth-largest-element-in-an-array) (Medium)
  1. [Top K Frequent Elements](https://github.com/openset/leetcode/tree/master/problems/top-k-frequent-elements) (Medium)
  1. [Top K Frequent Words](https://github.com/openset/leetcode/tree/master/problems/top-k-frequent-words) (Medium)
