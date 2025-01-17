<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](https://github.com/openset/leetcode/tree/master/problems/median-employee-salary "Median Employee Salary")
　　　　　　　　　　　　　　　　
[Next >](https://github.com/openset/leetcode/tree/master/problems/find-median-given-frequency-of-numbers "Find Median Given Frequency of Numbers")

## [570. Managers with at Least 5 Direct Reports (Medium)](https://leetcode.com/problems/managers-with-at-least-5-direct-reports "至少有5名直接下属的经理")

<p>The <code>Employee</code> table holds all employees including their managers. Every employee has an Id, and there is also a column for the manager Id.</p>

<pre>
+------+----------+-----------+----------+
|Id    |Name 	  |Department |ManagerId |
+------+----------+-----------+----------+
|101   |John 	  |A 	      |null      |
|102   |Dan 	  |A 	      |101       |
|103   |James 	  |A 	      |101       |
|104   |Amy 	  |A 	      |101       |
|105   |Anne 	  |A 	      |101       |
|106   |Ron 	  |B 	      |101       |
+------+----------+-----------+----------+
</pre>

<p>Given the <code>Employee</code> table, write a SQL query that finds out managers with at least 5 direct report. For the above table, your SQL query should return:</p>

<pre>
+-------+
| Name  |
+-------+
| John  |
+-------+
</pre>

<p><b>Note:</b><br />
No one would report to himself.</p>

### Hints
<details>
<summary>Hint 1</summary>
Try to get all the mangerIDs that have count bigger than 5
</details>

<details>
<summary>Hint 2</summary>
Use the last hint's result as a table and do join with origin table at id equals to managerId
</details>

<details>
<summary>Hint 3</summary>
This is a very good example to show the performance of SQL code. Try to work out other solutions and you may be surprised by running time difference.
</details>

<details>
<summary>Hint 4</summary>
If your solution uses 'IN' function and runs more than 5 seconds, try to optimize it by using 'JOIN' instead.
</details>
