<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](https://github.com/openset/leetcode/tree/master/problems/print-in-order "Print in Order")
　　　　　　　　　　　　　　　　
[Next >](https://github.com/openset/leetcode/tree/master/problems/print-zero-even-odd "Print Zero Even Odd")

## [1115. Print FooBar Alternately (Medium)](https://leetcode.com/problems/print-foobar-alternately "交替打印FooBar")

<p>Suppose you are given the following code:</p>

<pre>
class FooBar {
  public void foo() {
&nbsp; &nbsp; for (int i = 0; i &lt; n; i++) {
&nbsp; &nbsp; &nbsp; print(&quot;foo&quot;);
&nbsp;   }
  }

  public void bar() {
&nbsp; &nbsp; for (int i = 0; i &lt; n; i++) {
&nbsp; &nbsp; &nbsp; print(&quot;bar&quot;);
&nbsp; &nbsp; }
  }
}
</pre>

<p>The same instance of <code>FooBar</code> will be passed to two different threads. Thread A will call&nbsp;<code>foo()</code> while thread B will call&nbsp;<code>bar()</code>.&nbsp;Modify the given program to output &quot;foobar&quot; <em>n</em> times.</p>

<p>&nbsp;</p>

<p><strong>Example 1:</strong></p>

<pre>
<b>Input:</b> n = 1
<b>Output:</b> &quot;foobar&quot;
<strong>Explanation:</strong> There are two threads being fired asynchronously. One of them calls foo(), while the other calls bar(). &quot;foobar&quot; is being output 1 time.
</pre>

<p><strong>Example 2:</strong></p>

<pre>
<b>Input:</b> n = 2
<b>Output:</b> &quot;foobarfoobar&quot;
<strong>Explanation:</strong> &quot;foobar&quot; is being output 2 times.
</pre>

### Similar Questions
  1. [Print in Order](https://github.com/openset/leetcode/tree/master/problems/print-in-order) (Easy)
  1. [Print Zero Even Odd](https://github.com/openset/leetcode/tree/master/problems/print-zero-even-odd) (Medium)
