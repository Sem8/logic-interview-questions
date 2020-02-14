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
Day 1: Pay 1/7 piece                        ( worker: 1 ; you: 6 )      Day 4: Take back 1/7 piece & 2/7 piece, pay 4/7 piece   ( worker: 4 ; you: 3 )
Day 2: Take back 1/7 piece, pay 2/7 piece   ( worker: 2 ; you: 5 )      Day 5: Pay 1/7 piece                                    ( worker: 5 ; you: 2 )
Day 3: Pay 1/7 piece                        ( worker: 3 ; you: 4 )      Day 6: Take back 1/7, pay 2/7                           ( worker: 6 ; you: 1 )
                                                                        Day 7: Pay 1/7                                          ( worker: 7 ; you: 0 )
</p>
</details>