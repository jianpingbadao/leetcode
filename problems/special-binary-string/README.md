<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](https://github.com/openset/leetcode/tree/master/problems/find-anagram-mappings "Find Anagram Mappings")
　　　　　　　　　　　　　　　　
[Next >](https://github.com/openset/leetcode/tree/master/problems/prime-number-of-set-bits-in-binary-representation "Prime Number of Set Bits in Binary Representation")

## [761. Special Binary String (Hard)](https://leetcode.com/problems/special-binary-string "特殊的二进制序列")

<p>
<i>Special</i> binary strings are binary strings with the following two properties:
</p><p>
<li>The number of 0's is equal to the number of 1's.</li>
<li>Every prefix of the binary string has at least as many 1's as 0's.</li>
</p><p>
Given a special string <code>S</code>, a <i>move</i> consists of choosing two consecutive, non-empty, special substrings of <code>S</code>, and swapping them.  <i>(Two strings are consecutive if the last character of the first string is exactly one index before the first character of the second string.)</i>
</p><p>
At the end of any number of moves, what is the lexicographically largest resulting string possible?
</p>

<p><b>Example 1:</b><br />
<pre>
<b>Input:</b> S = "11011000"
<b>Output:</b> "11100100"
<b>Explanation:</b>
The strings "10" [occuring at S[1]] and "1100" [at S[3]] are swapped.
This is the lexicographically largest string possible after some number of swaps.
</pre>
</p>

<p><b>Note:</b><ol>
<li><code>S</code> has length at most <code>50</code>.</li>
<li><code>S</code> is guaranteed to be a <i>special</i> binary string as defined above.</li>
</ol></p>

### Related Topics
  [[Recursion](https://github.com/openset/leetcode/tree/master/tag/recursion/README.md)]
  [[String](https://github.com/openset/leetcode/tree/master/tag/string/README.md)]

### Similar Questions
  1. [Valid Parenthesis String](https://github.com/openset/leetcode/tree/master/problems/valid-parenthesis-string) (Medium)

### Hints
<details>
<summary>Hint 1</summary>
Draw a line from (x, y) to (x+1, y+1) if we see a "1", else to (x+1, y-1).
A special substring is just a line that starts and ends at the same y-coordinate, and that is the lowest y-coordinate reached.
Call a mountain a special substring with no special prefixes - ie. only at the beginning and end is the lowest y-coordinate reached.
If F is the answer function, and S has mountain decomposition M1,M2,M3,...,Mk,  then the answer is:
reverse_sorted(F(M1), F(M2), ..., F(Mk)).
However, you'll also need to deal with the case that S is a mountain, such as 11011000 -> 11100100.
</details>
