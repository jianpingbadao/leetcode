<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](https://github.com/openset/leetcode/tree/master/problems/majority-element-ii "Majority Element II")
　　　　　　　　　　　　　　　　
[Next >](https://github.com/openset/leetcode/tree/master/problems/power-of-two "Power of Two")

## [230. Kth Smallest Element in a BST (Medium)](https://leetcode.com/problems/kth-smallest-element-in-a-bst "二叉搜索树中第K小的元素")

<p>Given a binary search tree, write a function <code>kthSmallest</code> to find the <b>k</b>th smallest element in it.</p>

<p><b>Note: </b><br />
You may assume k is always valid, 1 &le; k &le; BST&#39;s total elements.</p>

<p><strong>Example 1:</strong></p>

<pre>
<strong>Input:</strong> root = [3,1,4,null,2], k = 1
   3
  / \
 1   4
  \
&nbsp;  2
<strong>Output:</strong> 1</pre>

<p><strong>Example 2:</strong></p>

<pre>
<strong>Input:</strong> root = [5,3,6,2,4,null,null,1], k = 3
       5
      / \
     3   6
    / \
   2   4
  /
 1
<strong>Output:</strong> 3
</pre>

<p><b>Follow up:</b><br />
What if the BST is modified (insert/delete operations) often and you need to find the kth smallest frequently? How would you optimize the kthSmallest routine?</p>

### Related Topics
  [[Tree](https://github.com/openset/leetcode/tree/master/tag/tree/README.md)]
  [[Binary Search](https://github.com/openset/leetcode/tree/master/tag/binary-search/README.md)]

### Similar Questions
  1. [Binary Tree Inorder Traversal](https://github.com/openset/leetcode/tree/master/problems/binary-tree-inorder-traversal) (Medium)
  1. [Second Minimum Node In a Binary Tree](https://github.com/openset/leetcode/tree/master/problems/second-minimum-node-in-a-binary-tree) (Easy)

### Hints
<details>
<summary>Hint 1</summary>
Try to utilize the property of a BST.
</details>

<details>
<summary>Hint 2</summary>
Try in-order traversal. (Credits to @chan13)
</details>

<details>
<summary>Hint 3</summary>
What if you could modify the BST node's structure?
</details>

<details>
<summary>Hint 4</summary>
The optimal runtime complexity is O(height of BST).
</details>
