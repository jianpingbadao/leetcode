<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](https://github.com/openset/leetcode/tree/master/problems/strobogrammatic-number "Strobogrammatic Number")
　　　　　　　　　　　　　　　　
[Next >](https://github.com/openset/leetcode/tree/master/problems/strobogrammatic-number-iii "Strobogrammatic Number III")

## [247. Strobogrammatic Number II (Medium)](https://leetcode.com/problems/strobogrammatic-number-ii "中心对称数 II")

<p>A strobogrammatic number is a number that looks the same when rotated 180 degrees (looked at upside down).</p>

<p>Find all strobogrammatic numbers that are of length = n.</p>

<p><b>Example:</b></p>

<pre>
<b>Input:</b>  n = 2
<b>Output:</b> <code>[&quot;11&quot;,&quot;69&quot;,&quot;88&quot;,&quot;96&quot;]</code>
</pre>

### Related Topics
  [[Recursion](https://github.com/openset/leetcode/tree/master/tag/recursion/README.md)]
  [[Math](https://github.com/openset/leetcode/tree/master/tag/math/README.md)]

### Similar Questions
  1. [Strobogrammatic Number](https://github.com/openset/leetcode/tree/master/problems/strobogrammatic-number) (Easy)
  1. [Strobogrammatic Number III](https://github.com/openset/leetcode/tree/master/problems/strobogrammatic-number-iii) (Hard)

### Hints
<details>
<summary>Hint 1</summary>
Try to use recursion and notice that it should recurse with <i>n</i> - 2 instead of <i>n</i> - 1.
</details>
