<h2><a href="https://leetcode.com/problems/divisor-game">1025. Divisor Game</a></h2>
<h3>Easy</h3>
<hr>
<p>Alice and Bob take turns playing a game, with Alice starting first.</p>
<p>Initially, there is a number <code>n</code> on the chalkboard. On each player's turn, that player makes a move consisting of:</p>
<ul>
<li>Choosing any <code>x</code> with <code>0 &lt; x &lt; n</code> and <code>n % x == 0</code>.</li>
<li>Replacing the number <code>n</code> on the chalkboard with <code>n - x</code>.</li>
</ul>
<p>Also, if a player cannot make a move, they lose the game.</p>
<p>Return <code>true</code> if and only if Alice wins the game, assuming both players play optimally.</p>

<p><strong>Example 1:</strong></p>
<pre>
<strong>Input:</strong> n = 2
<strong>Output:</strong> true
<strong>Explanation:</strong> Alice chooses 1, and Bob has no more moves.
</pre>

<p><strong>Example 2:</strong></p>
<pre>
<strong>Input:</strong> n = 3
<strong>Output:</strong> false
<strong>Explanation:</strong> Alice chooses 1, Bob chooses 1, and Alice has no more moves.
</pre>

<p><strong>Constraints:</strong></p>
<ul>
<li>1 ≤ <code>n</code> ≤ 1000</li>
</ul>
