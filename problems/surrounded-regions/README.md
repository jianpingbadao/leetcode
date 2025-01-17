<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](https://github.com/openset/leetcode/tree/master/problems/sum-root-to-leaf-numbers "Sum Root to Leaf Numbers")
　　　　　　　　　　　　　　　　
[Next >](https://github.com/openset/leetcode/tree/master/problems/palindrome-partitioning "Palindrome Partitioning")

## [130. Surrounded Regions (Medium)](https://leetcode.com/problems/surrounded-regions "被围绕的区域")

<p>Given a 2D board containing <code>&#39;X&#39;</code> and <code>&#39;O&#39;</code> (<strong>the letter O</strong>), capture all regions surrounded by <code>&#39;X&#39;</code>.</p>

<p>A region is captured by flipping all <code>&#39;O&#39;</code>s into <code>&#39;X&#39;</code>s in that surrounded region.</p>

<p><strong>Example:</strong></p>

<pre>
X X X X
X O O X
X X O X
X O X X
</pre>

<p>After running your function, the board should be:</p>

<pre>
X X X X
X X X X
X X X X
X O X X
</pre>

<p><strong>Explanation:</strong></p>

<p>Surrounded regions shouldn&rsquo;t be on the border, which means that any <code>&#39;O&#39;</code>&nbsp;on the border of the board are not flipped to <code>&#39;X&#39;</code>. Any <code>&#39;O&#39;</code>&nbsp;that is not on the border and it is not connected to an <code>&#39;O&#39;</code>&nbsp;on the border will be flipped to <code>&#39;X&#39;</code>. Two cells are connected if they are adjacent cells connected horizontally or vertically.</p>

### Related Topics
  [[Depth-first Search](https://github.com/openset/leetcode/tree/master/tag/depth-first-search/README.md)]
  [[Breadth-first Search](https://github.com/openset/leetcode/tree/master/tag/breadth-first-search/README.md)]
  [[Union Find](https://github.com/openset/leetcode/tree/master/tag/union-find/README.md)]

### Similar Questions
  1. [Number of Islands](https://github.com/openset/leetcode/tree/master/problems/number-of-islands) (Medium)
  1. [Walls and Gates](https://github.com/openset/leetcode/tree/master/problems/walls-and-gates) (Medium)
