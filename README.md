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

p | p $\oplus$ p
--- | ---
T | F
F | F

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
###### Exercises 6: verifying the first De Morgan law (p.34)
$p$|$q$|$p\wedge q$|$\neg(p\wedge q)$|$\neg p$|$\neg q$|$\neg p \vee \neg q$
-|-|-|-|-|-|-
T|T|T|F|F|F|F
T|F|F|T|F|T|T
F|T|F|T|T|F|T
F|F|F|T|T|T|T

###### Exercises 8:
(a)  
$p$ : "Kwame will take a job in industry"  
$q$ : "Kwame will go to graduate school"  
Negation: $\neg (p\vee q)$  
$\neg (p\vee q)\equiv \neg p\wedge \neg q$  
Kwame will neither take a job in industry nor go to graduate school.  
(b)  
$p$ : "Yoshiko knows Java "  
$q$ : "Yoshiko knows calculus"  
Negation: $\neg(p\wedge q)\equiv \neg p\vee\neg q$  
Yoshiko does not know Java or calculus.  
(c)  
$p$ : "James is young"
$q$ : "James is strong"  
Negation: $\neg(p\wedge q)\equiv \neg p\vee \neg q$  
James is not young or not strong.  
(d)  
$p$ : "Rita will move to Oregon"  
$q$ : "Rita will move to Washington"  
Negation: $\neg(p\vee q)\equiv \neg p\wedge \neg q$  
Rita will neither move to Oregon nor Washington.

###### Exercises 14:   
Determine whether $(\neg p\wedge(p\rightarrow q))\rightarrow\neg q$ is a tautology.  

$p$|$q$|$\neg p$|$p\rightarrow q$|$\neg p\wedge(p\rightarrow q)$|$\neg q$|$(\neg p\wedge(p\rightarrow q))\rightarrow \neg q$
:---:|:---:|:---:|:---:|:---:|:---:|:---:
T|T|F|T|F|F|T
T|F|F|F|F|T|T
F|T|T|T|T|F|F
F|F|T|T|T|T|T

Therefore, it is not a tautology.  
###### Exercises 22:
Show that $(p\rightarrow q)\vee (p\rightarrow r)$ and $p\rightarrow (q\vee r)$ are logically equivalent.  
logically equivalent: compound proposition that have the same truth values in all possible cases. (i.e., $p\leftrightarrow q$ is a tautology.)  

Suppose $(p\rightarrow q)\vee (p\rightarrow r)$ is False. So, we can know that $p$ is True, $q$ and $r$ are both False. In such a case, it holds that $p\rightarrow (q\vee r)$ is False. Now, considering when $(p\rightarrow q)\vee (p\rightarrow r)$ is True:  
1. If $p$ is False, then $p\rightarrow (q\vee r)$ is always True.  
2. If $p$ is True, then at least one of $q$ and $r$ is True. So, $q\vee r$ is always True, and $p\rightarrow (q\vee r)$ is True.  

Therefore, the above statement holds.

#### Chapter 1.4
###### Exercises 2: (p53)
(a) True  
(b) false  
(c) false  
(d) True  

###### Exercises 8:
(a) If the animal is a rabbit, then it hops.  
(b) Every animal is a rabbit and it hops.
(c) There is an animal, if it is a rabbit, then it hops.
(d) There is an animal, it is a rabbit and it hops.

###### Exercises 14:
(a) True  
(b) True  
(c) True  
(d) False, it does not holds when $x\le 0$.

###### Exercises 18:
$x \in \{ -2, -1, 0, 1, 2\}$  
(a) $\vee_{x\in\{ -2, -1, 0, 1, 2\}}P(x)$  
(b) $P(-2)\wedge P(-1)\wedge P(0)\wedge P(1)\wedge P(2)$  
(c) $\neg P(-2)\vee \neg P(-1)\vee \neg P(0)\vee \neg P(1)\vee \neg P(2)$  
(d) $\neg P(-2)\wedge \neg P(-1)\wedge \neg P(0)\wedge \neg P(1)\wedge \neg P(2)$  
(e) $\neg\exists xP(x)$ = $\forall\neg P(x)$, so, we have $\neg P(-2)\wedge\neg P(-1)\wedge P(0)\wedge P(1)\wedge P(2)$  
(f) $\neg\forall xP(x)$ = $\exists x \neg P(x)$ so, we have $\neg P(-2)\vee\neg P(-1)\vee\neg P(0)\vee\neg P(1)\vee\neg P(2)$

###### Exercises 20: rewrite with negations, disjunctions, and conjunctions only.
$x\in \{-5, -3, -1, 1, 3, 5\}$  
(a) $\exists xP(x)$:  
$P(-5)\vee P(-3)\vee P(-1)\vee P(1)\vee P(3)\vee P(5)$  

(b) $\forall xP(x)$:  
$P(-5)\wedge P(-3)\wedge P(-1)\wedge P(1)\wedge P(3)\wedge P(5)$

(c) $\forall x((x\neq 3)\rightarrow P(x))$ = $\forall x(\neg(x\neq 3)\vee P(x))$ :  
$(\neg(-5\neq 3)\vee P(-5))\wedge (\neg(-3\neq 3)\vee P(-3))\wedge(\neg(-1\neq 3)\vee P(-1))\wedge(\neg(1\neq 3)\vee P(1))\wedge(\neg(3\neq 3)\vee P(3))\wedge(\neg(5\neq 3)\vee P(5))$  

(d) $\exists x((x\ge 0)\wedge P(x))$ :  
$((-5\ge 0)\wedge P(-5))\vee((-3\ge 0)\wedge P(-3))\vee((-1\ge 0)\wedge P(-1))\vee((1\ge 0)\wedge P(1))\vee((3\ge0)\wedge P(3))\vee((5\ge0)\wedge P(5))$  

(e) $\exists x(\neg P(x))\wedge\forall x((x < 0)\rightarrow P(x))$:
$\neg P(-5)\vee\neg P(-3)\vee\neg P(-1)\vee\neg P(1)\vee\neg P(3)\vee\neg P(5)\wedge((\neg(-5<0)\vee P(5))\wedge(\neg(-3<0)\vee P(3))\wedge(\neg(-1<0)\vee P(-1))\wedge(\neg(1<0)\vee P(1))\wedge(\neg(3<0)\vee P(3))\wedge(\neg(5<0)\vee P(5)))$

###### Exercises 26:
(a) $U(x)$ : $x$ has visited Uzbekistan; $S(x)$ : $x$ is in your school
- the domain of $x$ is the people in the school:
  - $\exists xU(x)$
- the domain of $x$ is all the people in the world:
  - $\exists x(R(x)\wedge U(x))$

(b) $C(x)$ : $x$ has studied C++; $Y(x)$ : $x$ is in your class
- the domain of $x$ is the students in your class
  - $\forall xC(x)$
- the domain of $x$ is the people in the world
  - $\forall x (Y(x)\rightarrow C(x))$

(c) $S(x)$: $x$ is in your school; $B(x)$: $x$ has a bicycle; $M(x)$: $x$ has a motocycle.
- the domain of $x$ is the students in your class
  - $\neg\forall x(B(x)\wedge M(x))$
- the domain of $x$ is the people in the world
  - $\neg\forall x(S(x)\rightarrow B(x)\wedge M(x))$

(d) $H(x)$: $x$ is happy; $S(x)$: $x$ is in your school
- the domain of $x$ is the people in your school
  - $\neg\forall xH(x)$
- the domain of $x$ is the people in the world
  - $\neg\forall x(S(x)\wedge H(x))$

(e) $S(x)$: $x$ is in your class; $T(x)$: $x$ is born in 20th century
- the domain of $x$ is the people in your class
  - $\forall xT(x)$
- the domain of $x$ is the people in the world
  - $\forall x(S(x)\rightarrow T(x))$


###### Exercises 28:
(a) $P(x)$: $x$ is in the correct place  
$\exists x(\neg P(x)) \equiv \neg\forall xP(x)$

(b) $P(x)$: $x$ is in the correct place; $C(x)$: $x$ is in excellent condition; $T(x)$: $x$ is tool    
$\forall x(T(x)\rightarrow P(x)\wedge C(x))$

(c) $P(x)$: $x$ is in the correct place; $C(x)$: $x$ is in excellent condition;  
$\forall x(P(x)\wedge C(x))$

(d) $P(x)$: $x$ is in the correct place; $C(x)$: $x$ is in excellent condition;  
$\neg\exists xP(x)\wedge(\neg\exists xC(x))$

(e) $P(x)$: $x$ is in the correct place; $C(x)$: $x$ is in excellent condition;  
$\exists x(\neg P(x)\wedge C(x))$, alternatively, $\exists x(P(x)\rightarrow C(x))$

###### Exercises 30:
(a) $P(1, 3)\vee P(2, 3)\vee P(3, 3)$  
(b) $P(1, 1)\wedge P(1, 2)\wedge P(1, 3)$  
(c) $\neg P(2, 1)\vee\neg P(2, 2)\vee\neg P(2, 3)$  
(d) $\neg P(1, 2)\wedge\neg P(2, 2)\vee\neg P(3, 2)$

###### Exercises 36:
(a) $x\in \{0, 1\}$  
(b) $x\in \{\sqrt{2}, -\sqrt{2}\}$  
(c) $x = 0$
