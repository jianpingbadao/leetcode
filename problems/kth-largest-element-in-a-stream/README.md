<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](https://github.com/openset/leetcode/tree/master/problems/search-in-a-sorted-array-of-unknown-size "Search in a Sorted Array of Unknown Size")
　　　　　　　　　　　　　　　　
[Next >](https://github.com/openset/leetcode/tree/master/problems/binary-search "Binary Search")

## [703. Kth Largest Element in a Stream (Easy)](https://leetcode.com/problems/kth-largest-element-in-a-stream "数据流中的第K大元素")

<p>Design a class to find&nbsp;the <strong>k</strong>th largest element in a stream. Note that it is the kth largest element in the sorted order, not the kth distinct element.</p>

<p>Your&nbsp;<code>KthLargest</code>&nbsp;class will have a constructor which accepts an integer <code>k</code> and an integer array <code>nums</code>, which contains initial elements from&nbsp;the stream. For each call to the method <code>KthLargest.add</code>, return the element representing the kth largest element in the stream.</p>

<p><strong>Example:</strong></p>

<pre>
int k = 3;
int[] arr = [4,5,8,2];
KthLargest kthLargest = new KthLargest(3, arr);
kthLargest.add(3);&nbsp; &nbsp;// returns 4
kthLargest.add(5);&nbsp; &nbsp;// returns 5
kthLargest.add(10);&nbsp; // returns 5
kthLargest.add(9);&nbsp; &nbsp;// returns 8
kthLargest.add(4);&nbsp; &nbsp;// returns 8
</pre>

<p><strong>Note: </strong><br />
You may assume that&nbsp;<code>nums</code>&#39; length&nbsp;&ge;&nbsp;<code>k-1</code>&nbsp;and <code>k</code> &ge;&nbsp;1.</p>

### Related Topics
  [[Heap](https://github.com/openset/leetcode/tree/master/tag/heap/README.md)]

### Similar Questions
  1. [Kth Largest Element in an Array](https://github.com/openset/leetcode/tree/master/problems/kth-largest-element-in-an-array) (Medium)
