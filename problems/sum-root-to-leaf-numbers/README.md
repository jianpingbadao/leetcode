<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](https://github.com/openset/leetcode/tree/master/problems/longest-consecutive-sequence "Longest Consecutive Sequence")
　　　　　　　　　　　　　　　　
[Next >](https://github.com/openset/leetcode/tree/master/problems/surrounded-regions "Surrounded Regions")

## [129. Sum Root to Leaf Numbers (Medium)](https://leetcode.com/problems/sum-root-to-leaf-numbers "求根到叶子节点数字之和")

<p>Given a binary tree containing digits from <code>0-9</code> only, each root-to-leaf path could represent a number.</p>

<p>An example is the root-to-leaf path <code>1-&gt;2-&gt;3</code> which represents the number <code>123</code>.</p>

<p>Find the total sum of all root-to-leaf numbers.</p>

<p><strong>Note:</strong>&nbsp;A leaf is a node with no children.</p>

<p><strong>Example:</strong></p>

<pre>
<strong>Input:</strong> [1,2,3]
    1
   / \
  2   3
<strong>Output:</strong> 25
<strong>Explanation:</strong>
The root-to-leaf path <code>1-&gt;2</code> represents the number <code>12</code>.
The root-to-leaf path <code>1-&gt;3</code> represents the number <code>13</code>.
Therefore, sum = 12 + 13 = <code>25</code>.</pre>

<p><strong>Example 2:</strong></p>

<pre>
<strong>Input:</strong> [4,9,0,5,1]
    4
   / \
  9   0
&nbsp;/ \
5   1
<strong>Output:</strong> 1026
<strong>Explanation:</strong>
The root-to-leaf path <code>4-&gt;9-&gt;5</code> represents the number 495.
The root-to-leaf path <code>4-&gt;9-&gt;1</code> represents the number 491.
The root-to-leaf path <code>4-&gt;0</code> represents the number 40.
Therefore, sum = 495 + 491 + 40 = <code>1026</code>.</pre>

### Related Topics
  [[Tree](https://github.com/openset/leetcode/tree/master/tag/tree/README.md)]
  [[Depth-first Search](https://github.com/openset/leetcode/tree/master/tag/depth-first-search/README.md)]

### Similar Questions
  1. [Path Sum](https://github.com/openset/leetcode/tree/master/problems/path-sum) (Easy)
  1. [Binary Tree Maximum Path Sum](https://github.com/openset/leetcode/tree/master/problems/binary-tree-maximum-path-sum) (Hard)
  1. [Smallest String Starting From Leaf](https://github.com/openset/leetcode/tree/master/problems/smallest-string-starting-from-leaf) (Medium)
