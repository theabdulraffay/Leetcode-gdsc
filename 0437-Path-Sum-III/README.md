<h2><a href="https://leetcode.com/problems/path-sum-iii">437. Path Sum III</a></h2>
<h3>Medium</h3>
<hr>
<p>Given the root of a binary tree and an integer <code>targetSum</code>, return the number of paths where the sum of the values along the path equals <code>targetSum</code>.</p>
<p>The path does not need to start or end at the root or a leaf, but it must go downwards (i.e., traveling only from parent nodes to child nodes).</p>

<p><strong>Example 1:</strong></p>
<pre>
<strong>Input:</strong> root = [10,5,-3,3,2,null,11,3,-2,null,1], targetSum = 8
<strong>Output:</strong> 3
<strong>Explanation:</strong> The paths that sum to 8 are shown.
</pre>

<p><strong>Example 2:</strong></p>
<pre>
<strong>Input:</strong> root = [5,4,8,11,null,13,4,7,2,null,null,5,1], targetSum = 22
<strong>Output:</strong> 3
</pre>

<p><strong>Constraints:</strong></p>
<ul>
<li>The number of nodes in the tree is in the range [0, 1000].</li>
<li>-10<sup>9</sup> ≤ Node.val ≤ 10<sup>9</sup></li>
<li>-1000 ≤ <code>targetSum</code> ≤ 1000</li>
</ul>
