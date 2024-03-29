<h2><a href="https://leetcode.com/problems/reverse-bits/description/">190. Reverse Bits</a></h2>
<h3>Easy</h3>
<hr>
<p>Reverse bits of a given 32 bits unsigned integer.</p>
<p>Note:</p>
<ul>
  <li>Note that in some languages, such as Java, there is no unsigned integer type. In this case, both input and output will be given as a signed integer type. They should not affect your implementation, as the integer's internal binary representation is the same, whether it is signed or unsigned.</li>
  <li>In Java, the compiler represents the signed integers using 2's complement notation. Therefore, in Example 2 above, the input represents the signed integer -3 and the output represents the signed integer -1073741825.</li>
</ul>
<p><strong>Example 1:</strong></p>
<pre>
<strong>Input:</strong> n = 00000010100101000001111010011100
<strong>Output:</strong> 964176192 (00111001011110000010100101000000)
<strong>Explanation:</strong> The input binary string 00000010100101000001111010011100 represents the unsigned integer 43261596, so return 964176192 which its binary representation is 00111001011110000010100101000000.
</pre>
<p><strong>Example 2:</strong></p>
<pre>
<strong>Input:</strong> n = 11111111111111111111111111111101
<strong>Output:</strong> 3221225471 (10111111111111111111111111111111)
<strong>Explanation:</strong> The input binary string 11111111111111111111111111111101 represents the unsigned integer 4294967293, so return 3221225471 which its binary representation is 10111111111111111111111111111111.
</pre>
<p><strong>Constraints:</strong></p>
<ul>
  <li>The input must be a binary string of length 32.</li>
</ul>
<p><strong>Follow up:</strong> If this function is called many times, how would you optimize it?</p>
