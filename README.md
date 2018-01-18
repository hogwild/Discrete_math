# Discrete_math: the Exercises

## Week 1:
#### Chapter 1.1
###### Exercises 6 (p13):
(a) True. Because 288 is the largest of the three numbers.
(b) True. 5MP is higher than 4MP.
(c) False.
(d) False. The hypothesis of the conditional statements is true and the conclusion is false.
(e) False. because the first part of the biconditional statement is false and the second part is true. (or we can say, the truth values of the first part and the second part of the biconditional statement are different.)

###### Exercises 8
(a) I did not buy a lottery ticket this week.
(b) I bought a lottery ticket this week, or, I won the million dollar jackpot.
(c) If I bought a lottery ticket this week, then I won the million dollar jackpot.
(d) I bought a lottery ticket this week and I won the million dollar jackpot.
(e) I bought a lottery ticket this week if and only if I won the million dollar jackpot.
(f) If I did not buy a lottery ticket this week, then I did not win the million dollar jackpot.
(g) I did not buy a lottery ticket this week and I did not win the million dollar jackpot.
(h) I did not buy a lottery ticket this week, or I bought a lottery ticket this week and won the million dollar jackpot.

###### Exercises 10
(a) The election is not decided.
(b) The election is decided, or the votes have been counted.
(c) The election is not decided or the votes have been counted.
(d) If the votes have been counted then the election is decided.
(e) If the votes have not been counted then the election is not decided.
(f) If the election is not decided then the votes have not been counted.
(g) The election is decided if and only if the votes have been counted.
(h) Neither the votes have been counted nor the election is not decided and the votes have been counted.

###### Exercises 26 (p15)
(a) You get a A in this course if and only if you learn how to solve discrete mathematics problems.
(b) You will be informed and conversely if and only if you read the newspaper everyday.
(c) It rains if and only if it is a weekend day.
(d) You can see the wizard if and only if he is not in.

###### Exercises 28
(a)
- converse: If I stay at home, then it will snow today.
- contrapostive: If I do not stay at home, then it will not snow today.
- inverse: If it does not snow today, then I will not stay at home.
(b)
- converse: It is a sunny summer day whenever I go to the beach.  
- contrapostive: It is not a sunny summer day whenever I do not go to the beach.
- inverse: I do not go to the beach whenever it is not a sunny summer day.
(c)
- converse: When I sleep until noon, it is necessary that I stay up late.
- contrapostive: When I do not sleep until noon, it is not necessary that I stay up late.
- inverse: When I do not stay up late, it is not necessary that I sleep until noon.

###### Exercises 34
(a)
p | p$\oplus$p
--- | ---
T | F
F | F

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3


(b)
p | $\neg$ p | p $\oplus$ $\neg$ p
--- | --- | ---
T|F|T
F|T|T
(c)
p|q| $\neg$ q| p $\oplus$ $\neg$ q
---|---|---|---
T|T|F|T
T|F|T|F
F|T|F|F
F|F|T|T

(d)
p|q| $\neg$ p| $\neg$ q| $\neg$ p $\oplus$ $\neg$ q
-|-|-|-|-
T|T|F|F|F
T|F|F|T|T
F|T|T|F|T
F|F|T|T|F
(e)
p|q| $\neg$ q|p $\oplus$ q|p $\oplus$ $\neg$ q|(p $\oplus$ q) $\vee$ (p $\oplus$ $\neg$ q)
-|-|-|-|-|-
T|T|F|F|T|T
T|F|T|T|F|T
F|T|F|T|F|T
F|F|T|F|T|T

(f)
p|q| $\neg$ q|p $\oplus$ q|p $\oplus$ $\neg$ q|(p $\oplus$ q) $\wedge$ (p $\oplus$ $\neg$ q)
-|-|-|-|-|-
T|T|F|F|T|F
T|F|T|T|F|F
F|T|F|T|F|F
F|F|T|F|T|F


#### Chapter 1.2
###### Exercises 4 (p22)
$w \rightarrow s \vee d$
###### Exercises 12 (p23)
- $l$ : "the file system is not locked"
- $q$ : "new messages will be queued"
- $n$ : "the system is functioning normally"
- $b$ : "new messages are sent to the message buffer"

1. $l\rightarrow q$
2. $l\leftrightarrow n$
3. $\neg q\rightarrow b$
4. $l\rightarrow b$
5. $\neg b$

If the system is consistent, then there exist at least one truth value of each proposition variable such that all the proposition in the system specifications are true.

Suppose there exists consistency in the system, we know that $b$ is False from 5. From 3 and 4, it can be found that if $l$ is False, then $q$ should be True. Obviously, 1 holds with such settings, and for 2, it will also hold by setting $n$ to be False. Therefore, the system is consistent.

###### Exercises 17
- $f$ : the first prof. needs coffee
- $s$ : the second prof. needs coffee
- $t$ : the third prof. needs coffee
- $e$ : everyone wants coffee.

1. f
2. s
3. $\neg t$

$f\wedge s\wedge t\rightarrow\neg t$

###### Exercises 18
- $j$ : Jasmine attends
- $s$ : Samir attends
- $k$ : Kanti attends
1. $j\rightarrow \neg s$
2. $s\rightarrow k$
3. $\neg k\vee j$

suppose $j$ is false, then from 3 $k$ is false, and from 2, $s$ will be false, so, none will come. suppose $j$ is True, from 1, $s$ should be False, but $k$ can be either true or false. So, two friend can be invited, or just Jasmine, or nobody.

###### Exercises 23
- $p$ : "A is knave"
- $q$ : "B is knave"
1. $p\wedge q$

if 1 is True, then A is a knave which is conflict to the fact that "knave lies". Thus, 1 is False. So, A is lying, which means A is knave, thus $q$ is False, i.e., B is a knight.

###### Exercises 24
- $p$ : "A is a knight"
- $q$ : "B is a knight"
- $s$ : "C is a knight"

1. $p\rightarrow \neg s$
2. $q\rightarrow p$
3. $s\rightarrow \neg s$

From 3, we know that s is False. So, C can be a knave or spy. We suppose C is a knave, then from 1, we can see A can be a knight or spy, and from 2, if $q$ is True, then B and A are both knights, so $q$ has to be  False, thus, B is a spy. If A is a spy, then from 2, we know $q$ should be false, but the only type left is knight, which is conflict with $q$ is false. Finally, if we set c as a spy, then, from 1, we know $p$ can be True or False, i.e., A can be a knight or knave. From 2, we know that A and B are the same type if we want 2 holds (because the spy has been assigned to C already).


#### Chapter 1.3
