<h2><a href="https://leetcode.com/problems/maximum-binary-tree">654. Maximum Binary Tree</a></h2>
<h3>Medium</h3>
<hr>
<p>You are given an integer array <code>nums</code> with no duplicates. A maximum binary tree can be built recursively from <code>nums</code> using the following algorithm:</p>
<ol>
<li>Create a root node whose value is the maximum value in <code>nums</code>.</li>
<li>Recursively build the left subtree on the subarray prefix to the left of the maximum value.</li>
<li>Recursively build the right subtree on the subarray suffix to the right of the maximum value.</li>
<li>Return the maximum binary tree built from <code>nums</code>.</li>
</ol>
<p><strong>Example 1:</strong></p>
<pre>
<strong>Input:</strong> nums = [3,2,1,6,0,5]
<strong>Output:</strong> [6,3,5,null,2,0,null,null,1]
<strong>Explanation:</strong> The recursive calls are as follow:
- The largest value in [3,2,1,6,0,5] is 6. Left prefix is [3,2,1] and right suffix is [0,5].
    - The largest value in [3,2,1] is 3. Left prefix is [] and right suffix is [2,1].
        - Empty array, so no child.
        - The largest value in [2,1] is 2. Left prefix is [] and right suffix is [1].
            - Empty array, so no child.
            - Only one element, so child is a node with value 1.
    - The largest value in [0,5] is 5. Left prefix is [0] and right suffix is [].
        - Only one element, so child is a node with value 0.
        - Empty array, so no child.
</pre>
<p><strong>Example 2:</strong></p>
<pre>
<strong>Input:</strong> nums = [3,2,1]
<strong>Output:</strong> [3,null,2,null,1]
</pre>
<p><strong>Constraints:</strong></p>
<ul>
<li>1 ≤ <code>nums.length</code> ≤ 1000</li>
<li>0 ≤ <code>nums[i]</code> ≤ 1000</li>
<li>All integers in <code>nums</code> are unique.</li>
</ul>
