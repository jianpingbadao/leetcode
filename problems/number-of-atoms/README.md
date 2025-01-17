<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](https://github.com/openset/leetcode/tree/master/problems/split-linked-list-in-parts "Split Linked List in Parts")
　　　　　　　　　　　　　　　　
[Next >](https://github.com/openset/leetcode/tree/master/problems/minimum-window-subsequence "Minimum Window Subsequence")

## [726. Number of Atoms (Hard)](https://leetcode.com/problems/number-of-atoms "原子的数量")

<p>Given a chemical <code>formula</code> (given as a string), return the count of each atom.
</p><p>
An atomic element always starts with an uppercase character, then zero or more lowercase letters, representing the name.
</p><p>
1 or more digits representing the count of that element may follow if the count is greater than 1.  If the count is 1, no digits will follow.  For example, H2O and H2O2 are possible, but H1O2 is impossible.
</p><p>
Two formulas concatenated together produce another formula.  For example, H2O2He3Mg4 is also a formula.  
</p><p>
A formula placed in parentheses, and a count (optionally added) is also a formula.  For example, (H2O2) and (H2O2)3 are formulas.
</p><p>
Given a formula, output the count of all elements as a string in the following form: the first name (in sorted order), followed by its count (if that count is more than 1), followed by the second name (in sorted order), followed by its count (if that count is more than 1), and so on.</p>

<p><b>Example 1:</b><br />
<pre>
<b>Input:</b> 
formula = "H2O"
<b>Output:</b> "H2O"
<b>Explanation:</b> 
The count of elements are {'H': 2, 'O': 1}.
</pre>
</p>

<p><b>Example 2:</b><br />
<pre>
<b>Input:</b> 
formula = "Mg(OH)2"
<b>Output:</b> "H2MgO2"
<b>Explanation:</b> 
The count of elements are {'H': 2, 'Mg': 1, 'O': 2}.
</pre>
</p>

<p><b>Example 3:</b><br />
<pre>
<b>Input:</b> 
formula = "K4(ON(SO3)2)2"
<b>Output:</b> "K4N2O14S4"
<b>Explanation:</b> 
The count of elements are {'K': 4, 'N': 2, 'O': 14, 'S': 4}.
</pre>
</p>

<p><b>Note:</b>
<li>All atom names consist of lowercase letters, except for the first character which is uppercase.</li>
<li>The length of <code>formula</code> will be in the range <code>[1, 1000]</code>.</li>
<li><code>formula</code> will only consist of letters, digits, and round parentheses, and is a valid formula as defined in the problem.</li>
</p>

### Related Topics
  [[Stack](https://github.com/openset/leetcode/tree/master/tag/stack/README.md)]
  [[Recursion](https://github.com/openset/leetcode/tree/master/tag/recursion/README.md)]
  [[Hash Table](https://github.com/openset/leetcode/tree/master/tag/hash-table/README.md)]

### Similar Questions
  1. [Decode String](https://github.com/openset/leetcode/tree/master/problems/decode-string) (Medium)
  1. [Encode String with Shortest Length](https://github.com/openset/leetcode/tree/master/problems/encode-string-with-shortest-length) (Hard)
  1. [Parse Lisp Expression](https://github.com/openset/leetcode/tree/master/problems/parse-lisp-expression) (Hard)

### Hints
<details>
<summary>Hint 1</summary>
To parse formula[i:], when we see a `'('`, we will parse recursively whatever is inside the brackets (up to the correct closing ending bracket) and add it to our count, multiplying by the following multiplicity if there is one.

Otherwise, we should see an uppercase character: we will parse the rest of the letters to get the name, and add that (plus the multiplicity if there is one.)
</details>
