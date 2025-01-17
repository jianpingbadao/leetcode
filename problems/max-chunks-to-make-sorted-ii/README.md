<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](https://github.com/openset/leetcode/tree/master/problems/reorganize-string "Reorganize String")
　　　　　　　　　　　　　　　　
[Next >](https://github.com/openset/leetcode/tree/master/problems/max-chunks-to-make-sorted "Max Chunks To Make Sorted")

## [768. Max Chunks To Make Sorted II (Hard)](https://leetcode.com/problems/max-chunks-to-make-sorted-ii "最多能完成排序的块 II")

<p><em>This question is the same as &quot;Max Chunks to Make Sorted&quot; except the integers of the given array are not necessarily distinct, the input array could be up to length <code>2000</code>, and the elements could be up to <code>10**8</code>.</em></p>

<hr />

<p>Given an array <code>arr</code> of integers (<strong>not necessarily distinct</strong>), we split the array into some number of &quot;chunks&quot; (partitions), and individually sort each chunk.&nbsp; After concatenating them,&nbsp;the result equals the sorted array.</p>

<p>What is the most number of chunks we could have made?</p>

<p><strong>Example 1:</strong></p>

<pre>
<strong>Input:</strong> arr = [5,4,3,2,1]
<strong>Output:</strong> 1
<strong>Explanation:</strong>
Splitting into two or more chunks will not return the required result.
For example, splitting into [5, 4], [3, 2, 1] will result in [4, 5, 1, 2, 3], which isn&#39;t sorted.
</pre>

<p><strong>Example 2:</strong></p>

<pre>
<strong>Input:</strong> arr = [2,1,3,4,4]
<strong>Output:</strong> 4
<strong>Explanation:</strong>
We can split into two chunks, such as [2, 1], [3, 4, 4].
However, splitting into [2, 1], [3], [4], [4] is the highest number of chunks possible.
</pre>

<p><strong>Note:</strong></p>

<ul>
	<li><code>arr</code> will have length in range <code>[1, 2000]</code>.</li>
	<li><code>arr[i]</code> will be an integer in range <code>[0, 10**8]</code>.</li>
</ul>

<p>&nbsp;</p>

### Related Topics
  [[Array](https://github.com/openset/leetcode/tree/master/tag/array/README.md)]

### Similar Questions
  1. [Max Chunks To Make Sorted](https://github.com/openset/leetcode/tree/master/problems/max-chunks-to-make-sorted) (Medium)

### Hints
<details>
<summary>Hint 1</summary>
Each k for which some permutation of arr[:k] is equal to sorted(arr)[:k] is where we should cut each chunk.
</details>
