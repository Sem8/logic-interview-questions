# logic-interview-questions
Questions that are logic puzzles asked during interviews
---

#### 1. You have 8 balls of the same size, 7 balls weight the same and one of them weighs slightly more. Find the heavier ball using a balance and only 2 weighings


<details><summary><b>Answer</b></summary>
<p>

#### Answer: 

Divide the balls into 2 groups of 3 balls in each group and another 2 groups of 1 ball in each group.
That way you can isolate a single ball based on which group is heavier by just weighing no more than 
2 times

</p>
</details>

---

#### 2. You have got someone working for you for 7 days. For their work, you plan to give them a gold bar. But conditions are, 1) you must pay the worker in gold at end of every day,  2) You're only allowed to make 2 breaks in the gold bar. Assume that an equal amount of work is done by the worker every day so you will pay them an equal amount every day. How do you pay? 

<details><summary><b>Answer</b></summary>
<p>

#### Answer: 

If there are 7 pieces in the gold bar, make a cut after the 4th piece and another cut after the 5th piece so you end up with 3 different sized pieces, 4/7 size, 1/7 size and 2/7 size. This is how you can pay each day:
<p>Day 1: Pay 1/7 piece                        ( worker: 1 ; you: 6 )</p>      <p>Day 4: Take back 1/7 piece & 2/7 piece, pay 4/7 piece   ( worker: 4 ; you: 3 )</p>
<p>Day 2: Take back 1/7 piece, pay 2/7 piece   ( worker: 2 ; you: 5 )</p>      <p>Day 5: Pay 1/7 piece                                    ( worker: 5 ; you: 2 )</p>
<p>Day 3: Pay 1/7 piece                        ( worker: 3 ; you: 4 )</p>      <p>Day 6: Take back 1/7, pay 2/7                           ( worker: 6 ; you: 1 )</p>
                                                                               <p>Day 7: Pay 1/7                                          ( worker: 7 ; you: 0 )</p>
</p>
</details>

---

#### 3. In front of you are 3 boxes. One box contains only apples, another box contains only organges, and the last contains both apples and oranges. The 1st box has the label 'apples', the 2nd 'oranges', and the third 'apples and oranges'. But unfortunately, all of the labels are wrong, and you have to fix them so each box has the correct label. You cannot see inside the boxes. But you can ask for a sample from any box. You point to a box, and you get a random fruit from that box. What is the minimum number of samples you need to label all of the boxes correctly. 

<details><summary><b>Answer</b></summary>
<p>

#### Answer: 
<p>We can take advantage of the fact that ALL 3 boxes are labeled incorrectly</p>
<span> 'Apples' </span>  <span> 'Oranges' </span>   <span> 'Apples and Oranges' </span>
<p>We can take a sample from 'Apples and Oranges' and see what the fruit is. And since 'Apples and Oranges' is mislabeled, we know exactly what the fruit is after taking the sample from that box, so if the sample is orange, the label should be orange or vice versa for apple. So, for example if this 3rd box is acually apples, we'll correctly label it apples. The next 2 boxes will be easy to figure out as the other box labeled apples will definitely not be apples, and the other box labeled oranges will definitely not be oranges</p>
<p>Since the box labeled oranges is definitely wrong and apples is already taken, that leaves us with only Apples and Oranges for that box previously mislabeled orange</p>
<p>And now the only remaining label is oranges which goes to the box previously mislabled Apples. And the problem is solved by just getting 1 sample. </p>

</p>
</details>

---

#### 4. Mark a line to make the following equation true: 5 + 5 + 5 + 5 = 555

<details><summary><b>Answer</b></summary>
<p>

#### Answer: 
<p> 545 + 5 + 5 = 555 </p>

</p>
</details>

---

#### 5. A child spent $100.00 to get 100 toy animals. The child bought at least 1 cat, 1 fish and 1 bird and did not buy aany other toys. If a cat costs $10.00, a fish costs $3.00, and a bird costs $0.50, how many of each toy did the child buy? 

<details><summary><b>Answer</b></summary>
<p>

#### Answer: 
<p> c + f + b = 100</p>
<p> 10c + 3f + 0.5b = 100 </p>
<p> b = 100 - c - f </p>
<p>10c + 3f + 0.5(100 - c - f) = 100 --> 10c + 3f + 50 - 0.5c - 0.5f = 100 </p>
<p>9.5c + 2.5f + 50 = 100 --> (x2) --> 19c + 5f + 100 = 200 --> 19c + 5f = 100</p>
<p> f = 100/5 - (19/5)c  -->  f = 20 - (19/5)c</p>
<p> At this point we know, f and c should be whole numbers and c has to be a multiple of 5 to be a whole number since 5 is in it's denominator</p>
<p>For f to be a whole number of at least 1, we know c has to be at least 5 so that we can get 20 - (19/5)*5</p>
<p>So, for lowest numbers of f and c, f can be 1 and c would have to be 5</p>
<p>Since we know b = 100 - c - f  , we can say b = 100 - 5 - 1 so b = 94</p>
<span> f = 1 </span> <span> c = 5 </span> <span> b = 94 </span>
</p>
</details>