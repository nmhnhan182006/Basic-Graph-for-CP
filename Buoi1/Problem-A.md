# A - VALIDATE THE MAZE
There are many algorithms to generate maze. After generating the maze we’ve to validate whether it’s a valid maze or not. A valid maze has exactly one entry point and exactly one exit point (exactly 2 openings in the edges) and there must be at least one path from the entry point to exit point.
<p align="center"><img width="256" height="256" alt="Image" src="https://github.com/user-attachments/assets/d21bb0b9-237f-4c73-8a16-3129ad988098" /></p>
Given a maze, just find whether the maze is "valid" or "invalid".

### Input
The first line consists of an integer $t$, the number of test cases. Then for each test case, the first line consists of two integers $m$ and $n$, the number of rows and columns in the maze. Then contains the description of the matrix $M$ of order $m \times n$. $M[i][j] = $ # represents a wall and $M[i][j] =$ '.' represents a space.

### Output
For each test case find whether the maze is "valid" or "invalid".
### Constraints
$1 \leqslant t \leqslant 10000$

$1 \leqslant m \leqslant 20$

$1 \leqslant n \leqslant 20$

### Example
<div style="display: flex; justify-content: center;">
<table style="width:85%; border-collapse: collapse;">
<tr>
<th align="center" style="width:150px; border-bottom: 2px solid #333; padding: 15px; background-color: #f9f9f9;">Input</th>
<th align="center" style="width:150px; border-bottom: 2px solid #333; padding: 15px; background-color: #f9f9f9;">Output</th>
</tr>
<tr>
<td valign="top" style="padding: 12px; border-right: 1px solid #ddd;">
<pre><code>
6
4 4
####
#..#
#..#
5 5
#.###
#..##
##..#
#.#.#
###.#
1 1
.
5 1
#
#
.
.
#
2 2
#.
.#
3 4
#..#
#.##
#.##
</code></pre>
</td>
<td valign="top" style="padding: 12px; text-align: center;">
<pre><code>
valid
valid
invalid
valid
invalid
invalid
</code></pre>
</td>
</tr>
</table>
</div>

