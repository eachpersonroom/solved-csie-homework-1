Download Link: https://assignmentchef.com/product/solved-csie-homework-1
<br>
<strong>Problem 1 – Tower of Hanoi (Programming) </strong>

<strong>Problem Description</strong>

Tower of Hanoi is a classic mathematical game, which consists of three vertical pegs and several disks of different sizes. Robert, an extraordinarily handsome guy, is good at playing Tower of Hanoi optimally.

Once, he played the games repeatedly for a few days and nights until he was too tired and suddenly fell into sleep. After he woke up, he forgot what he had done for the current game. Moreover, he might even make some wrong moves.

You, a big fan of Robert, are eager to help him. Given the total number of disks and the game’s current state, please tell him whether he is on the right way. That is, there is an optimal solution containing the current state. Also, if he is on the right way, please tell him the minimum number of remaining steps to finish the game. Since the number of remaining steps might be extremely large, you should tell him the number modulo 998<em>,</em>244<em>,</em>353.

<strong>Input</strong>

The first line of the input contains an integer <em>n</em>, indicating the number of disks in his current game. The disks are numbered from 1 to <em>n </em>(from small to big). Also, the pegs are numbered from 1 to 3

(from left to right).

The following three lines contain (<em>k<sub>i </sub></em>+ 1) space-separated integers: the first integer <em>k<sub>i </sub></em>of the <em>i</em><sup>th </sup>line indicates the number of disks on the <em>i</em><sup>th </sup>peg, and the following <em>k<sub>i </sub></em>integers are the disks’ numbers from top to bottom on this peg.

3

<ul>

 <li>1 ≤ <em>n </em>= <sup>P </sup><em>k<sub>i </sub></em>≤ 100000</li>

</ul>

<em>i</em>=1

<ul>

 <li>The input is guaranteed to be a valid state of the game.</li>

</ul>

<table width="603">

 <tbody>

  <tr>

   <td width="328"><strong>Test Group 0 (0 %)</strong>•   Sample Input<strong>Test Group 1 (20 %)</strong>•   <em>n </em>≤ 10</td>

   <td width="275"><strong>Test Group 3 (20 %)</strong>•   The current state is on the right way.<strong>Test Group 4 (30 %)</strong>•   No other constraints.</td>

  </tr>

 </tbody>

</table>

<strong>Test Group 2 (30 %)</strong>

<ul>

 <li><em>n </em>≤ 50</li>

</ul>

<strong>Output</strong>

If he had moved correctly, output an integer indicating the minimum number of remaining steps to finish the game modulo 998<em>,</em>244<em>,</em>353. Otherwise, output “-1” (without quotes).




<strong>Sample Input 1                            Sample Input 2                           Sample Input 2</strong>

3                                                     3                                                     5

<ul>

 <li>3 1 3       1 3</li>

 <li>2 1 0          1 2</li>

</ul>

0                                                      2 2 1                                                3 5 4 1

<strong>Sample Output 1                          Sample Output 2                        Sample Output 2</strong>

4                                                     -1                                                   5

<strong>Problem 2 – Hellish Gag (Programming)</strong>

<strong>Problem Description</strong>

<em>The description is adapted from a true story.</em>

Designing ADA Homework #1, the TA −10<sup>11 </sup>has come up with a dark story as a problem description. Because ADA is a course fulfilled with hopes and happiness, his depressing story is considered a hellish gag, and the TA is banished to the uttermost depths of the hell.

Upon noticing −10<sup>11</sup>’s arrival, Hades, the king of the underworld, decides to grant him an opportunity to resurrect. “If you are able to solve this algorithm problem, you will get a chance to be back to the world.”, said Hades, “Here comes the problem. 99% deceased cannot solve it…”

However, −10<sup>11 </sup>is getting pale and turns unable to solve the problem. To ask for your help, he tells you this story by setting the exact problem in your Homework #1. Please save −10<sup>11 </sup>from the hell (so he could get back to the world and set another problem in your next ADA Homework).

<strong>Input</strong>

The first line of the input contains 4 numbers <em>N,a,b,c</em>, denoting the the size of 2 arrays and the 3 constants used in the condition description.

Then, <em>N </em>lines follow, the <em>i</em>-th of which contains two non-negative integers, <em>p<sub>i </sub></em>and <em>z<sub>i</sub></em>, denoting the entries of two arrays.

<ul>

 <li>1 ≤ <em>N </em>≤ 2 × 10<sup>6</sup></li>

 <li>1 ≤ <em>a </em>≤ 10<sup>9</sup></li>

 <li>0 ≤ <em>b </em>≤ 10<sup>9</sup></li>

 <li>−10<sup>9 </sup>≤ <em>c </em>≤ 10<sup>9</sup></li>

 <li></li>

</ul>

<strong>Test Group 0 (0 %)                                     Test Group 1 (10 %)                               Test Group 2 (5 %)</strong>

<ul>

 <li>Sample Input <em>N </em>≤ 2000           • <em>b </em>= 0</li>

</ul>

<strong>Test Group 3 (15 %)</strong>

<ul>

 <li>(<em>a,b,c</em>) = (1<em>,</em>1<em>,</em>0)</li>

 <li>[<em>z</em><sub>1</sub><em>,z</em><sub>2</sub><em>,…,z<sub>N</sub></em>] is a permutation of [0<em>,</em>1<em>,…,N </em>− 1].</li>

</ul>

<strong>Test Group 4 (30 %)                                                                           Test Group 5 (40 %)</strong>

<ul>

 <li>All <em>z<sub>i</sub></em>’s are distinct. No additional constraint.</li>

</ul>

<strong>Output</strong>

<em>N</em>

Output 1 integer, the summation <sup>X</sup><em>d<sub>i</sub></em>.

<em>i</em>=1

<strong>Sample Input 1                            Sample Input 2                           Sample Input 3</strong>

4 1 0 0                                              4 1 1 2                                             4 2021 0 1111111

0 0                                                   1 47                                                123 4

0 0                                                   3 22                                                567 8

0 0                                                   7 81                                                901 2

0 0                                                   5 65                                                345 6

<strong>Sample Output 1                          Sample Output 2                        Sample Output 3</strong>

0                                                     3                                                     3

<strong>Explanation</strong>

<ul>

 <li>In the first test case, (<em>d</em><sub>1</sub><em>,d</em><sub>2</sub><em>,d</em><sub>3</sub><em>,d</em><sub>4</sub>) = (0<em>,</em>0<em>,</em>0<em>,</em>0), so the required is 0 + 0 + 0 + 0 = 0.</li>

 <li>In the second test case, (<em>d</em><sub>1</sub><em>,d</em><sub>2</sub><em>,d</em><sub>3</sub><em>,d</em><sub>4</sub>) = (2<em>,</em>1<em>,</em>0<em>,</em>0), so the required is 2 + 1 + 0 + 0 = 3.</li>

 <li>In the third test case, (<em>d</em><sub>1</sub><em>,d</em><sub>2</sub><em>,d</em><sub>3</sub><em>,d</em><sub>4</sub>) = (1<em>,</em>0<em>,</em>1<em>,</em>1), so the required is 1 + 0 + 1 + 1 = 3.</li>

</ul>

<strong>Problem 3 – ADA Rectangle (Programming) (15 points)</strong>

<strong>Problem Description</strong>

Given <em>N </em>points (<em>p</em><sub>1</sub><em>,p</em><sub>2 </sub>··· <em>,p<sub>n</sub></em>) on a 2-dimensional (2D) plane, we define two points <em>p<sub>i </sub></em>and <em>p<sub>j </sub></em>as a good pair if there exists a rectangle satisfying the following conditions:

<ol>

 <li>The sides of the rectangle are parallel to the X-axis and Y-axis.</li>

 <li>The rectangle contains these two points <em>p<sub>i</sub>,p<sub>j </sub></em>only; no other points fall within this rectangle.</li>

</ol>

How many good pairs of points are there in total?

<strong>Input</strong>

The first line of the input contains one integer <em>N</em>, denoting the number of points.

The <em>i</em><sup>th </sup>of the following <em>N </em>lines contains two integers <em>x<sub>i</sub>,y<sub>i</sub></em>, indicating the coordinates of the <em>i</em><sup>th </sup>point.

<strong>Test Group 0 (0 %)                                                                               Test Group 2 (35 %)</strong>

<ul>

 <li>1 ≤ <em>N </em>≤ 3 × 10<sup>3</sup></li>

 <li>Sample Input. 1 ≤ <em>x<sub>i </sub></em>≤ <em>N</em></li>

 <li>1 ≤ <em>y<sub>i </sub></em>≤ <em>N</em></li>

 <li>All <em>x<sub>i </sub></em>are distinct.</li>

 <li>All <em>y<sub>i </sub></em>are distinct.</li>

</ul>

<strong>Test Group 1 (20 %)</strong>

<strong>Test Group 3 (45 %)</strong>

<ul>

 <li>1 ≤ <em>N </em>≤ 5 × 10<sup>2 </sup> 1 ≤ <em>N </em>≤ 2 × 10<sup>5</sup></li>

 <li>1 ≤ <em>x<sub>i </sub></em>≤ <em>N </em> 1 ≤ <em>x<sub>i </sub></em>≤ <em>N </em>• 1 ≤ <em>y<sub>i </sub></em>≤ <em>N    </em>• 1 ≤ <em>y<sub>i </sub></em>≤ <em>N</em></li>

 <li>All <em>x<sub>i </sub></em>are distinct. All <em>x<sub>i </sub></em>are distinct.</li>

 <li>All <em>y<sub>i </sub></em>are distinct. All <em>y<sub>i </sub></em>are distinct.</li>

</ul>

<strong>Output</strong>

Print the number of good pairs in a single line.

<strong>Sample Input 1                                                        Sample Output 1</strong>

5                                                                                8

<h1><a name="_Toc18140"></a>1 5</h1>

<h1><a name="_Toc18141"></a>2 2</h1>

5 4

4 1

<h1><a name="_Toc18142"></a>3 3</h1>

<strong>Sample Input 2                                                        Sample Output 2</strong>

<h1><a name="_Toc18143"></a>5                                                                                4</h1>

<a href="#_Toc18140">1                                                                                                                                                             1</a>

<a href="#_Toc18141">2                                                                                                                                                             2</a>

<a href="#_Toc18142">3                                                                                                                                                             3</a>

<a href="#_Toc18143">4                                                                                                                                                             4</a>

<a href="#_Toc18144">5                                                                                                                                                             5</a>




<strong>Sample Input 3                                                        Sample Output 3</strong>

3                                                                                3

<ul>

 <li>2</li>

 <li>1</li>

 <li>3</li>

</ul>

<strong>Hint</strong>

<ol>

 <li>The good pairs in Sample Input 1 are (<em>p</em><sub>1</sub><em>,p</em><sub>2</sub>), (<em>p</em><sub>1</sub><em>,p</em><sub>3</sub>), (<em>p</em><sub>1</sub><em>,p</em><sub>5</sub>), (<em>p</em><sub>2</sub><em>,p</em><sub>4</sub>), (<em>p</em><sub>2</sub><em>,p</em><sub>5</sub>), (<em>p</em><sub>3</sub><em>,p</em><sub>4</sub>), (<em>p</em><sub>3</sub><em>,p</em><sub>5</sub>), (<em>p</em><sub>4</sub><em>,p</em><sub>5</sub>).</li>

 <li>You are also encouraged to use the above picture to find inspiration. When conquering, you can use stacks to maintain the black points, and use binary search to identify how many black points are in the gray scope.</li>

 <li>You can maintain a stack on each of the left and right sides to keep the “needed points”, which are the points blocking the current point or forming a good pair with the current point you are focusing on.</li>

 <li>Instead of std::stack, you can use std::vector to maintain stack and perform binary search algorithm on std::vector directly using std::lower bound.</li>

 <li>GL &amp; HF (Good Luck and Have Fun).</li>

</ol>

<strong>Problem 4 – Candies (Programming) (10 points)</strong>

<strong>Problem Description</strong>

Baluteshih brings <em>N </em>candies to his friend, Waynetu. Those candies are lined on the table. Each candy has its own sweetness indicated by an integer. The sweetness of the candies from left to right are <em>a</em><sub>1</sub>, <em>a</em><sub>2</sub>, <em>…</em>, <em>a<sub>N</sub></em>, respectively.

Baluteshih assigns Waynetu an interesting mission. He asks Waynetu to remove some candies from the table, so that the remaining candies on the table are <em>alternative</em>. Formally, we say that a sequence of candies with sweetness <em>b</em><sub>1</sub>, <em>b</em><sub>2</sub>, <em>…</em>, <em>b<sub>k </sub></em>is <em>alternative </em>if <em>b<sub>i </sub></em>× <em>b<sub>i</sub></em><sub>+1 </sub>≤ 0 holds for all 1 ≤ <em>i &lt; k</em>.

With the aforementioned rule, Waynetu hopes to maximize the sum of the sweetness of the candies on the table. Please help Waynetu find the maximum possible sum of the remaining candies’ sweetness and provide a solution to reach the optimal case.

<strong>Input</strong>

The first line contains two integers <em>T</em>, representing the number of testcases, and <em>flag </em>(<em>flag </em>∈ {0<em>,</em>1}), which will be described in the output section.

Each testcase includes two lines: the first line contains an integer <em>N </em>(1 ≤ <em>N </em>≤ 10<sup>5</sup>), and the second line contains <em>N </em>integers <em>a</em><sub>1</sub>, <em>a</em><sub>2</sub>, <em>…</em>, <em>a<sub>N </sub></em>(|<em>a<sub>i</sub></em>| ≤ 10<sup>9</sup>).

It is guaranteed that the sum of <em>N </em>does not exceed 10<sup>5</sup>.

<strong>Test Group 0 (0 %) Test Group 3 (10 %) </strong>• Sample Input.      • <em>flag </em>= 1.

<ul>

 <li><sup>P</sup><em>N </em>≤ 1000.</li>

</ul>

<strong>Test Group 1 (20 %)</strong>

<strong>Test Group 4 (20 %) </strong>• <em>flag </em>= 0.

<ul>

 <li><sup>P</sup><em>N </em>≤ 1000. <em>flag </em>= 1.</li>

</ul>

<strong>Test Group 2 (50 %)</strong>

<ul>

 <li><em>flag </em>= 0.</li>

</ul>

<strong>Output</strong>

For each testcase, please print an integer representing the maximum possible sum of the sweetness in the first line. If <em>flag </em>equals 1 mentioned in the input section, please furthermore print out one optimal way in the second line: an integer <em>k </em>representing the number of candies remaining on the table, followed by <em>k </em>integers <em>i</em><sub>1</sub>, <em>i</em><sub>2</sub>, <em>…</em>, <em>i<sub>k</sub></em>, representing the indices of candies.

<strong>Sample Input 1                                                        Sample Output 1</strong>

1 0                                                                              8

<h1><a name="_Toc18144"></a>5</h1>

3 -1 6 -7 4

<strong>Sample Input 2                                                        Sample Output 2</strong>

<ul>

 <li>0 3</li>

 <li>3</li>

</ul>

1 2 3

4

1 -2 3 -4

<strong>Sample Input 3                                                        Sample Output 3</strong>

3 1                                                                              -1

1                                                                                 1 1

-1                                                                               6

3                                                                                  3 1 2 3

5 0 1                                                                           -1

4                                                                                 1 1

-1 -2 -3 -4

<strong>Hint</strong>

<ol>

 <li>Since each input includes several independent testcases, please carefully clear all results of the current testcase before dealing with the next testcase.</li>

</ol>

<strong>Problem 5 – Time Complexity &amp; Recurrence (Hand-Written) (25</strong>

<strong>points)</strong>

<em>Note</em>: In this problem, if you use any theorem not covered by the lectures, slides, and the textbook, you should prove it first.

<em>Note</em>: In this problem, you may assume the base, <em>b</em>, for logarithm has constraints <em>b </em>∈ R<em>,b &gt; </em>1.

<ul>

 <li><strong>Asymptotic Notations </strong>(10%)</li>

</ul>

<em>Prove </em>or <em>Disprove</em>.

If you think the statement is correct, you should provide a comprehensive proof.

If you think the statement is incorrect, you should disprove it or give a counterexample.

<ul>

 <li>(2%) ln<em>n</em>! = <em>O</em>(ln<em>n<sup>n</sup></em>)</li>

</ul>

(d) (3%) (ln<em>n</em>)<sup>3 </sup>= <em>o</em>(<em>n</em>)

<ul>

 <li><strong>Solve Recurrences </strong>(15%)</li>

</ul>

Give the tight bound (Θ-bound, <em>e.g., T</em>(<em>n</em>) = Θ(<em>n</em><sup>3</sup>)) of the following recurrence equations.

Assume:         <em>T</em>(<em>n</em>) = 1<em>,</em>∀<em>n </em>≤ 2

<em>Note</em>: Show your derivation thoroughly by using the assigned method.

<ul>

 <li>(2%) <em>T</em>(<em>n</em>) = 2<em>T</em>(<em>n </em>− 1) + 1</li>

</ul>

Please use <strong>brute force </strong>method.

Please use <strong>recursion tree </strong>method.

Please use <strong>master theorem </strong>method.

√          √

(d) (5%) <em>T</em>(<em>n</em>) =            <em>nT</em>( <em>n</em>) + <em>n</em>

Please use <strong>variable transformation </strong>method.

<strong>Problem 6 – Ghost Leg (Hand-Written) (15 points)</strong>

<em>In this problem, please </em><em>briefly explain your solution in text. </em><em>Do not use pseudo code, or you will receive penalty.</em>

“Ghost Leg”, known in Japan as Amidakuji (“Amida lottery” because the paper was folded into a fan shape resembling Amida’s halo), is a method of lottery designed to create random pairings between two sets of the same number of prizes. This is often used to distribute prizes to people, where the number of prizes is the same as the number of people. Ghost Leg consists of vertical lines with horizontal lines connecting two adjacent vertical lines; the horizontal lines are called “legs”. Note that “legs” cannot touch other legs. The number of vertical lines equals the number of people, and at the bottom of each line there is an item – a prize that will be paired with a player. The general rule for this game is: choosing a line on the top, and following it downwards. When a horizontal line is encountered, the player needs to transit to another vertical line and then continue going down. The procedure is repeated until reaching the end of the vertical line, and then the player gets the corresponding prize. Therefore, choosing the line decides which prize you get. You can refer to the link for more details: <a href="https://en.wikipedia.org/wiki/Ghost_Leg.">https://en.wikipedia.org/wiki/Ghost_Leg.</a>

Alan is a party host, and he distributes <em>N </em>prizes to <em>N </em>players by a ghost leg. The party attendees can get a gift based on the game result. However, Alan is not as generous as others think. Instead, he is a cunning person. Alan does not want to give any precious presents to attendees at all, so he assigns his employees to attend the party to collect good gifts and leave consolation prizes to other ignorant players.

You, as Alan’s personal assistant, please help him manipulate the gift distribution result. You have to design an efficient algorithm for this black-box trick to give all good prizes to the designated people. The specific start must reach the planned destination as expected.

Here comes a problem: Now, given a ghost leg board without any horizontal lines, you have <em>k </em>constraints, which assign <em>k </em>starting points with their corresponding prizes. What is the minimum number of horizontal lines to be added in order to satisfy all <em>k </em>constraints?

For example, you have a ghost leg without any horizontal lines as Fig. 1, and the constraints are (c should go to 1), (b should go to 4). Thus, the answer should be 3, and one of the solutions is illustrated in Fig. 2.

To help you solve the problem, we define the property of “inversion”.

<strong>Inversion: </strong>Given a sequence of unique numbers <em>B </em>= <em>b</em><sub>1</sub><em>,b</em><sub>2</sub><em>,…,b<sub>n</sub></em>, an inversion is a pair of numbers <em>b<sub>i </sub></em>and <em>b<sub>j </sub></em>in this sequence such that <em>i &lt; j </em>and <em>b<sub>i </sub>&gt; b<sub>j</sub></em>. Let <em>I</em>(<em>B</em>) be the set of inversions in <em>B</em>. For example, if <em>B </em>= 1<em>,</em>3<em>,</em>5<em>,</em>2, <em>I</em>(<em>B</em>) = {(3<em>,</em>2)<em>,</em>(5<em>,</em>2)}, and the number of inversions is 2 (|<em>I</em>(<em>B</em>)| = 2).

Please answer the questions below.

<ul>

 <li>(4pt) Given an unsorted and unique sequence <em>B </em>with <em>n </em>numbers, please design an efficient algorithm to calculate the number of inversions |<em>I</em>(<em>B</em>)| in <em>O</em>(<em>N </em>log<em>N</em>) time.</li>

 <li>(3pt) Explain why your algorithm runs in <em>O</em>(<em>N </em>log<em>N</em>).</li>

 <li>(2pt) Prove that the number of exchanges when performing bubble sort on the sequence <em>S </em>equals the number of inversions in <em>S</em>.</li>

 <li>(4pt) Describe an <em>O</em>(<em>N </em>log<em>N</em>) algorithm that calculates the minimum number of horizontal lines in the ghost leg when |<em>constraints</em>| ≤ <em>N</em>.</li>

 <li>(2pt) Prove the correctness of your algorithm in the previous problem.</li>

</ul>

<strong>Problem 7 – Unfair Lucas (Hand-Written) (10 points)</strong>

Far Far Away Kingdom has a custom that all philosophers gather at a round table to keep their friendship, and they hire a chef to prepare some dishes for them. Supposed that the round table is big enough to fit <em>N </em>philosophers, and their indices are shown in the picture below. Lucas is a chef standing in the center of the round table, and he needs to prepare some dishes for all philosophers.

Because Lucas is not familiar with all philosophers, he decides to prepare some tasty dishes for the philosophers who are friendly and awful dishes for other philosophers. However, Lucas is afraid of being accused of his unfair treatment, so he decides to choose a <em>contiguous </em>part of philosophers to get tasty dishes, such that the possibility of being charged disparate treatment is minimized. (Note: The contiguous part of philosophers means that you can choose the philosophers whose indices are <em>n,</em>1<em>,</em>2<em>,</em>3 to eat tasty dishes, but you cannot choose the philosophers whose indices are <em>n,</em>1<em>,</em>3<em>,</em>4 because of skipping the 2<sup>nd </sup>philosopher.)

Given the friendliness value <em>f<sub>i </sub></em>for <em>i </em>= 1<em>,</em>2<em>,</em>3<em>,…,N</em>, of the <em>i</em><sup>th </sup>philosopher, please help Lucas find out a contiguous part of philosophers such that the total friendliness value of those chosen philosophers is maximized. Moreover, he hopes that at least one philosopher can have tasty dishes.

<ul>

 <li>(2%) Consider 10 philosophers and their friendliness values <em>f </em>= [−3<em>,</em>0<em>,</em>6<em>,</em>4<em>,</em>0<em>,</em>−1<em>,</em>−2<em>,</em>3<em>,</em>−3<em>,</em>9]. What is the maximum total of friendliness values?</li>

 <li>(3%) Please design an algorithm with both time complexity and space complexity in <em>O</em>(<em>N</em>) in the worst case. Briefly explain your algorithm and prove its time complexity.</li>

 <li>(5%) Now, Lucas wants to make his friends happier, so he decides to skip <em>at most </em>one philosopher in the contiguous part to give tasty dishes such that the maximum total friendliness value can be increased. After applying this policy, please design an algorithm with both time complexity and space complexity in <em>O</em>(<em>N</em>) in the worst case. Briefly explain your algorithm and prove its time complexity.</li>

</ul>