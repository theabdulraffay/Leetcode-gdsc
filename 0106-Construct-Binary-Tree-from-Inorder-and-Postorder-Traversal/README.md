<h2><a href="https://leetcode.com/problems/construct-binary-tree-from-inorder-and-postorder-traversal">106. Construct Binary Tree from Inorder and Postorder Traversal</a></h2>
<h3>Medium</h3>
<hr>
<p>Given two integer arrays <code>inorder</code> and <code>postorder</code> where <code>inorder</code> is the inorder traversal of a binary tree and <code>postorder</code> is the postorder traversal of the same tree, construct and return the binary tree.</p>
<p><strong>Example 1:</strong></p>
<pre>
<strong>Input:</strong> inorder = [9,3,15,20,7], postorder = [9,15,7,20,3]
<strong>Output:</strong> [3,9,20,null,null,15,7]
</pre>
<p><strong>Example 2:</strong></p>
<pre>
<strong>Input:</strong> inorder = [-1], postorder = [-1]
<strong>Output:</strong> [-1]
</pre>
<p><strong>Constraints:</strong></p>
<ul>
<li>1 ≤ inorder.length ≤ 3000</li>
<li><code>postorder.length == inorder.length</code></li>
<li>-3000 ≤ inorder[i], postorder[i] ≤ 3000</li>
<li><code>inorder</code> and <code>postorder</code> consist of unique values.</li>
<li>Each value of <code>postorder</code> also appears in <code>inorder</code>.</li>
<li><code>inorder</code> is guaranteed to be the inorder traversal of the tree.</li>
<li><code>postorder</code> is guaranteed to be the postorder traversal of the tree.</li>
</ul>
