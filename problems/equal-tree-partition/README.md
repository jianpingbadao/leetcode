<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](https://github.com/openset/leetcode/tree/master/problems/maximum-width-of-binary-tree "Maximum Width of Binary Tree")
　　　　　　　　　　　　　　　　
[Next >](https://github.com/openset/leetcode/tree/master/problems/strange-printer "Strange Printer")

## [663. Equal Tree Partition (Medium)](https://leetcode.com/problems/equal-tree-partition "均匀树划分")

<p>
Given a binary tree with <code>n</code> nodes, your task is to check if it's possible to partition the tree to two trees which have the equal sum of values after removing <b>exactly</b> one edge on the original tree.
</p>

<p><b>Example 1:</b><br />
<pre><b>Input:</b>     
    5
   / \
  10 10
    /  \
   2   3

<b>Output:</b> True
<b>Explanation:</b> 
    5
   / 
  10
      
Sum: 15

   10
  /  \
 2    3

Sum: 15
</pre>
</p>


<p><b>Example 2:</b><br />
<pre><b>Input:</b>     
    1
   / \
  2  10
    /  \
   2   20

<b>Output:</b> False
<b>Explanation:</b> You can't split the tree into two trees with equal sum after removing exactly one edge on the tree.
</pre>
</p>

<p><b>Note:</b><br>
<ol>
<li>The range of tree node value is in the range of [-100000, 100000].</li>
<li>1 <= n <= 10000</li>
</ol>
</p>

### Related Topics
  [[Tree](https://github.com/openset/leetcode/tree/master/tag/tree/README.md)]
