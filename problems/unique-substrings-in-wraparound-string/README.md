<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](https://github.com/openset/leetcode/tree/master/problems/count-the-repetitions "Count The Repetitions")
　　　　　　　　　　　　　　　　
[Next >](https://github.com/openset/leetcode/tree/master/problems/validate-ip-address "Validate IP Address")

## [467. Unique Substrings in Wraparound String (Medium)](https://leetcode.com/problems/unique-substrings-in-wraparound-string "环绕字符串中唯一的子字符串")

<p>Consider the string <code>s</code> to be the infinite wraparound string of "abcdefghijklmnopqrstuvwxyz", so <code>s</code> will look like this: "...zabcdefghijklmnopqrstuvwxyzabcdefghijklmnopqrstuvwxyzabcd....".</p>

<p>Now we have another string <code>p</code>. Your job is to find out how many unique non-empty substrings of <code>p</code> are present in <code>s</code>. In particular, your input is the string <code>p</code> and you need to output the number of different non-empty substrings of <code>p</code> in the string <code>s</code>.</p>

<p><b>Note:</b> <code>p</code> consists of only lowercase English letters and the size of p might be over 10000.</p>

<p><b>Example 1:</b><br />
<pre>
<b>Input:</b> "a"
<b>Output:</b> 1

<b>Explanation:</b> Only the substring "a" of string "a" is in the string s.
</pre>
</p>

<p><b>Example 2:</b><br />
<pre>
<b>Input:</b> "cac"
<b>Output:</b> 2
<b>Explanation:</b> There are two substrings "a", "c" of string "cac" in the string s.
</pre>
</p>

<p><b>Example 3:</b><br />
<pre>
<b>Input:</b> "zab"
<b>Output:</b> 6
<b>Explanation:</b> There are six substrings "z", "a", "b", "za", "ab", "zab" of string "zab" in the string s.
</pre>
</p>

### Related Topics
  [[Dynamic Programming](https://github.com/openset/leetcode/tree/master/tag/dynamic-programming/README.md)]

### Hints
<details>
<summary>Hint 1</summary>
One possible solution might be to consider allocating an array size of 26 for each character in the alphabet. (Credits to @r2ysxu)
</details>
