<h2><a href="https://leetcode.com/problems/populating-next-right-pointers-in-each-node">116. Populating Next Right Pointers in Each Node</a></h2>
<h3>Medium</h3>
<hr>
<p>You are given a perfect binary tree where all leaves are on the same level, and every parent has two children. The binary tree has the following definition:</p>
<pre>
struct Node {
  int val;
  Node *left;
  Node *right;
  Node *next;
}
</pre>
<p>Populate each next pointer to point to its next right node. If there is no next right node, the next pointer should be set to NULL.</p>
<p>Initially, all next pointers are set to NULL.</p>
<p><strong>Example 1:</strong></p>
<pre>
<strong>Input:</strong> root = [1,2,3,4,5,6,7]
<strong>Output:</strong> [1,#,2,3,#,4,5,6,7,#]
<strong>Explanation:</strong> Given the above perfect binary tree (Figure A), your function should populate each next pointer to point to its next right node, just like in Figure B. The serialized output is in level order as connected by the next pointers, with '#' signifying the end of each level.
</pre>
<p><strong>Example 2:</strong></p>
<pre>
<strong>Input:</strong> root = []
<strong>Output:</strong> []
</pre>
<p><strong>Constraints:</strong></p>
<ul>
<li>The number of nodes in the tree is in the range [0, 2^12 - 1].</li>
<li>-1000 <= Node.val <= 1000</li>
</ul>
<p><strong>Follow-up:</strong></p>
<ul>
<li>You may only use constant extra space.</li>
<li>The recursive approach is fine. You may assume implicit stack space does not count as extra space for this problem.</li>
</ul>
