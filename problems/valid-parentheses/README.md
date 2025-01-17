<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](https://github.com/openset/leetcode/tree/master/problems/remove-nth-node-from-end-of-list "Remove Nth Node From End of List")
　　　　　　　　　　　　　　　　
[Next >](https://github.com/openset/leetcode/tree/master/problems/merge-two-sorted-lists "Merge Two Sorted Lists")

## [20. Valid Parentheses (Easy)](https://leetcode.com/problems/valid-parentheses "有效的括号")

<p>Given a string containing just the characters <code>&#39;(&#39;</code>, <code>&#39;)&#39;</code>, <code>&#39;{&#39;</code>, <code>&#39;}&#39;</code>, <code>&#39;[&#39;</code> and <code>&#39;]&#39;</code>, determine if the input string is valid.</p>

<p>An input string is valid if:</p>

<ol>
	<li>Open brackets must be closed by the same type of brackets.</li>
	<li>Open brackets must be closed in the correct order.</li>
</ol>

<p>Note that an empty string is&nbsp;also considered valid.</p>

<p><strong>Example 1:</strong></p>

<pre>
<strong>Input:</strong> &quot;()&quot;
<strong>Output:</strong> true
</pre>

<p><strong>Example 2:</strong></p>

<pre>
<strong>Input:</strong> &quot;()[]{}&quot;
<strong>Output:</strong> true
</pre>

<p><strong>Example 3:</strong></p>

<pre>
<strong>Input:</strong> &quot;(]&quot;
<strong>Output:</strong> false
</pre>

<p><strong>Example 4:</strong></p>

<pre>
<strong>Input:</strong> &quot;([)]&quot;
<strong>Output:</strong> false
</pre>

<p><strong>Example 5:</strong></p>

<pre>
<strong>Input:</strong> &quot;{[]}&quot;
<strong>Output:</strong> true
</pre>

### Related Topics
  [[Stack](https://github.com/openset/leetcode/tree/master/tag/stack/README.md)]
  [[String](https://github.com/openset/leetcode/tree/master/tag/string/README.md)]

### Similar Questions
  1. [Generate Parentheses](https://github.com/openset/leetcode/tree/master/problems/generate-parentheses) (Medium)
  1. [Longest Valid Parentheses](https://github.com/openset/leetcode/tree/master/problems/longest-valid-parentheses) (Hard)
  1. [Remove Invalid Parentheses](https://github.com/openset/leetcode/tree/master/problems/remove-invalid-parentheses) (Hard)
  1. [Check If Word Is Valid After Substitutions](https://github.com/openset/leetcode/tree/master/problems/check-if-word-is-valid-after-substitutions) (Medium)

### Hints
<details>
<summary>Hint 1</summary>
An interesting property about a valid parenthesis expression is that a sub-expression of a valid expression should also be a valid expression. (Not every sub-expression) e.g.

<pre>
{ { } [ ] [ [ [ ] ] ] } is VALID expression
          [ [ [ ] ] ]    is VALID sub-expression
  { } [ ]                is VALID sub-expression
</pre>

Can we exploit this recursive structure somehow?
</details>

<details>
<summary>Hint 2</summary>
What if whenever we encounter a matching pair of parenthesis in the expression, we simply remove it from the expression? This would keep on shortening the expression. e.g.

<pre>
{ { ( { } ) } }
      |_|

{ { (      ) } }
    |______|

{ {          } }
  |__________|

{                }
|________________|

VALID EXPRESSION!
</pre>
</details>

<details>
<summary>Hint 3</summary>
The <b>stack</b> data structure can come in handy here in representing this recursive structure of the problem. We can't really process this from the inside out because we don't have an idea about the overall structure. But, the stack can help us process this recursively i.e. from outside to inwards.
</details>
