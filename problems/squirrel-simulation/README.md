<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](https://github.com/openset/leetcode/tree/master/problems/subtree-of-another-tree "Subtree of Another Tree")
　　　　　　　　　　　　　　　　
[Next >](https://github.com/openset/leetcode/tree/master/problems/winning-candidate "Winning Candidate")

## [573. Squirrel Simulation (Medium)](https://leetcode.com/problems/squirrel-simulation "松鼠模拟")

There&#39;s a tree, a squirrel, and several nuts. Positions are represented by the cells in a 2D grid. Your goal is to find the <b>minimal</b> distance for the squirrel to collect all the nuts and put them under the tree one by one. The squirrel can only take at most <b>one nut</b> at one time and can move in four directions - up, down, left and right, to the adjacent cell. The distance is represented by the number of moves.
<p><b>Example 1:</b></p>

<pre><b>Input:</b> 
Height : 5
Width : 7
Tree position : [2,2]
Squirrel : [4,4]
Nuts : [[3,0], [2,5]]
<b>Output:</b> 12
<b>Explanation:</b>
<img src="https://assets.leetcode.com/uploads/2018/10/22/squirrel_simulation.png" style="width: 40%;" />​​​​​
</pre>

<p><b>Note:</b></p>

<ol>
	<li>All given positions won&#39;t overlap.</li>
	<li>The squirrel can take at most one nut at one time.</li>
	<li>The given positions of nuts have no order.</li>
	<li>Height and width are positive integers. 3 &lt;= height * width &lt;= 10,000.</li>
	<li>The given positions contain at least one nut, only one tree and one squirrel.</li>
</ol>

### Related Topics
  [[Math](https://github.com/openset/leetcode/tree/master/tag/math/README.md)]

### Hints
<details>
<summary>Hint 1</summary>
Will Brute force solution works here? What will be its complexity?
</details>

<details>
<summary>Hint 2</summary>
Brute force definitely won't work here. Think of some simple solution. Take some example and make some observations.
</details>

<details>
<summary>Hint 3</summary>
Will order of nuts traversed by squirrel is important or only first nut traversed by squirrel is important?
</details>

<details>
<summary>Hint 4</summary>
Are there some paths which squirrel have to cover in any case? If yes, what are they?
</details>

<details>
<summary>Hint 5</summary>
Did you notice only first nut traversed by squirrel matters? Obviously squirrel will choose first nut which will result in minimum distance.
</details>
