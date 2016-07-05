# Dismathportfolio-AJFrancisco
Anne Janelle N. Francisco

# Week 1
- During our first meeting, we had a short seatwork just to recall the topics about Dismath. I was able to answer number 10 which was about the Euler.
- Sir also introduced to us the Propositions and asked us one by one about it. I was asked if x+9=11 is a proposition and I answered no because we do not know the true value of x which may or may not satisfy the statement.
- On our next meeting, we tacked about gates which was also discussed during our days in Logicir. 
- We answered the exercises (odd numbers) one by one in class. The questions were mainly about translating the equation into a statement with the given phrases. 
- I answered the following in class today (June 16, 2016)

| Question (Chapter 1.1) |  Question | Answer|
|:------------------------:|---------|:-----:|
| 8-c | p: I bought a lottery ticket this week.<br/> q: I won the million dollar jackpot.<br/> Express p → q as an English sentence. | If I bought a lottery ticket this week, then I won the million dollar jackpot. |
| 11-b | p: It is below freezing.<br/> q: It is snowing.<br/> Write "It is below freezing but not snowing" using p and q and logical connectives (including negations). | p ∧ -q |
| 15-a | p: Grizzly bears have been seen in the area.<br/> q: Hiking is safe on the trail.<br/> r: Berries are ripe along the trail. Write "Berries are ripe along the trail, but grizzly bears have not been seen in the area." using p, q, and r and logical connectives (including negations). | r ∧ -p |
| 17-b | Determine whether "If 1 + 1 = 3, then 2 + 2 = 4." is true or false. | True |
| 19-c | Determine whether "The prerequisite for the course is a course in number theory or a course in cryptography." an inclusive or, exclusive or, is intended. | Inclusive |
| 25-b | Write "For you to win the contest it is necessary and sufficient that you have the only winning ticket." in the form of "p if and only if q" in English | You will win the contest, if and only if, you have the only winning ticket. |
| 29-a | How many rows appear in a truth table for "p →¬p" | 2^1 = 2
<br/>


- Assignment (June 21, 2016)
- 1.1 / 31c

  | p | q | -q | p v -q | (p v -q) → q |
| :--- | :---:| ---: | ---: | ---: |
| T | F | T | T | F |
| F | T | F | F | T |
| T | T | F | T | T |
| F | F | T | T | F |

- 1.1 / 33d

  | p | q | -p | p ↔ q | p ↔ q | (p ↔ q)  ⊕  (-p ↔ q)|
| :--- | :---:| ---: | ---: | ---: | ---: |
| T | F | F | F | T | T |
| F | T | T | F | T | T |
| T | T | F | T | F | T |
| F | F | T | T | F | T |

- 1.1 / 35e

  | p | q | -p | p ↔ q | -p ↔ q | (p ↔ q) v (-p ↔ q)|
| :--- | :---:| ---: | ---: | ---: | ---: |
| T | F | F | F | T | T |
| F | T | T | F | T | T |
| T | T | F | T | F | T |
| F | F | T | T | F | T |

- 1.1 / 37f

  | p | -p | q | -q | r | -p ↔ -q | q ↔ r | (-p ↔ -q) ↔ (q ↔ r) |
| :--- | :---:| ---: | ---: | ---: | ---: | ---: | ---: |
| F | T | F | T | T | F | F | T |
| F | T | T | F | F | T | F | F |
| F | T | F | T | F | F | T | F |
| F | T | T | F | T | T | T | T |
| T | F | T | F | F | F | F | T |
| T | F | F | T | T | T | F | F | 
| T | F | T | F | T | F | T | F |
| T | F | F | T | F | T | T | T |


# Week 2
- I answered the following in class today (June 21, 2016):


- 1.3 / 7c: Use De Morgan's laws to find the negation of the statement: Mei walks or takes the bus to class. <br><b> Answer: Mei does not walk and take the bus to class.</b>

- 1.3 / 17: Show that ¬(p ↔ q) and p ↔ ¬q are logically equivalent.

  | p | q | p ↔ q | ¬(p ↔ q) | (p ↔ ¬q) |
| :--- | :---:| ---: | :---:| :---:|
| T | F | F | T | T |
| T | T | T | F | F |
| F | F | T | F | F |
| F | T | F | T | T |

- Special exercise, find the logical equivalence <br> Given: ( p ∧ (p → q)) → q <br> Step by step process:

  | Given: ( p ∧ (p → q)) → q | Name of Law |
| :--- | :---:|
| ( p ∧ (¬p v q)) → q | Implication of logical equivalence <br> p → q ≡ ¬p v q |
| [(p ∧ ¬p) v (p ∧ q)] → q | Distributive law |
| [ F v (p ∧ q)] → q | Negation law |
| [(F v p) ∧ (F v q)] → q | Distributive law |
| (p ∧ q) → q | Identity law |
| ¬(p ∧ q) v q | Implication of logical equivalence <br> p → q ≡ ¬p v q |
| (¬p v ¬q) v q | De Morgan's law |
| ¬p v (¬q v q) | Associative law |
| ¬p v T | Negation law |
| T | Domination law |

- Disjuntion = OR, conjunction = AND, negation = NOT
- I answered the following in class today (June 23, 2016):

- 1.4 / 5: Let P (x) be the statement “x spends more than five hours every weekday in class,” where the domain for x consists of all students. Express each of these quantifications in English.<br><b> a) ∃xP(x) = There is a student who spends more than give hours every weekday in class.</b>

- 1.4 / 7: Translate these statements into English, where C(x) is “x is a comedian” and F(x) is “x is funny” and the domain consists of all people.<br><b> c) ∃x(C(x)→F(x)) = There exist if he/she is a comedian, then he/she is funny.</b>

- 1.4 / 11: Let P(x) be the statement “x = x2.” If the domain con- sists of the integers, what are these truth values?<br><b> b) P(1) = TRUE</b>

- 1.4 / 13: Determine the truth value of each of these statements if the domain consists of all integers.<br><b> c) ∃n(n = −n) = TRUE</b>

- 1.4 / 17: Suppose that the domain of the propositional function P(x) consists of the integers 0, 1, 2, 3, and 4. Write out each of these propositions using disjunctions, conjunc- tions, and negations.<br><b> b) ∀xP(x) = Conjunction</b>

- 1.5 / 1: Translate these statements into English, where the domain for each variable consists of all real numbers.<br><b> b) ∀x∀y(((x ≥ 0)∧(y ≥ 0)) → (xy ≥ 0)) = For all x and for all y, if noth are not negative/positive, then the product is also not negative/positive.</b>

- 1.5 / 3: Let Q(x, y) be the statement “x has sent an e-mail mes- sage to y,” where the domain for both x and y consists of all students in your class. Express each of these quantifi- cations in English.<br><b> f) ∀x∀yQ(x,y) = All students sent an email message to the whole class.</b>

- Give an example for hypothetical syllogism, ((p → q) ∧ (q → r)) → (p → r).<br><b> If Punu is cute, then she is cuddly. And if Punu is cuddly, then she is short. Therefore, if Punu is cuddly, then Punu is short.</b>

- Special exercise, find the logical equivalence <br> Given: [(p v q) ∧ (-p v r)] → (q v r)<br> Step by step process:

  | Given: [(p v q) ∧ (-p v r)] → (q v r)| Name of Law |
| :--- | :---:|
| -[(p v q) ∧ (-p v r)] v (q v r) | Implication of logical equivalence <br> p → q ≡ ¬p v q |
| --[(p v q) v (-p v r)] v (q v r) | De Morgan's law |
| --[(p v -p) v (q v r)] v (q v r ) | Associative law |
| --[ T v (q v r)] v (q v r ) | Negation law |
| --[ T v (q v q) v (r v r)] | Associative law |
| --[ T v q v r ] | Idempotent law |
| T | Domination law |

- Assignment given on June 23, 2016:

- 1.5 / 5: Let W (x, y) mean that student x has visited website y, where the domain for x consists of all students in your school and the domain for y consists of all websites. Express each of these statements by a simple English sentence.<br><b> c) ∃y W (José Orez, y ) = Jose Orez has visited some websites.</b>

- 1.5 / 7: Let T(x,y)mean that student x likes cuisine y,wherethe domain for x consists of all students at your school and the domain for y consists of all cuisines. Express each of these statements by a simple English sentence.<br><b> d) ∀x∀z∃y((x̸=z)→¬(T(x,y)∧T(z,y))) = For every pair of distinct students at your school, there is some cuisine that at least one them does not like.</b>

- 1.5 / 9: Let L(x, y) be the statement “x loves y,” where the domain for both x and y consists of all people in the world. Use quantifiers to express each of these statements.<br><b> e) There is somebody whom Lydia does not love. = ∃y -L(Lydia,y)</b>

# Week 3
- Assignment given on June 28, 2016

- 1.7 / 5: Prove that if m + n and n + p are even integers, where m, n, and p are integers, then m + p is even. What kind of proof did you use?

  | m + n = even and n + p = even | Steps |
| :--- | :---|
| m + n = 2s and n + p = 2u | Since they are even integers, let the sum be 2(integer) |
| m + n + n + p = 2s + 2u | We add both equations together |
| m + 2n + p = 2s + 2u | Equations now added |
| m + 2n + p - 2n = 2s + 2u - 2n | We now subtract 2n from both sides of the equation |
| m + p = 2s + 2u -2n | Factor out the 2 from the right side |
| m + p = 2(s + u - n) | Consider (s + u - n) as one integer |
  <b>Therefore, m + p is an even integer. We used direct proof.</b>

- 1.7 / 19: Prove the proposition P (0), where P (n) is the proposition “If n is a positive integer greater than 1, then n2 > n.” What kind of proof did you use?<br><b>0 is not an integer, therefore the proposition is vacuosuly true.</b>


# Week 4
- I answered the following in class today (July 5, 2016):

- 1.7 / 37: Show that the propositions p1, p2, p3, p4, and p5 can be shown to be equivalent by proving that the conditional statements p1 → p4, p3 → p1, p4 → p2, p2 → p5, and p5 → p3 are true.<br><b>[(p1 → p4) ∧ (p4 → p2) ∧ (p2 → p5) ∧ (p5 → p3) ∧ (p3 → p1)] → (p1 → p1)<br><b>We used hypothetical syllogism.</b></b>

- 1.7 / 29: Prove or disprove that if m and n are integers such that mn = 1, then either m = 1 and n = 1, or else m = −1 and n = −1.

  | m and n are integers |
| :--- |
| mn = 1 ; m=1 and n=1 OR m=-1 and n=-1 |
| mn=1 → {[(m=1) ∧ (n=1)] OR [(m=-1) ∧ (n=-1)]} ; p → (q v r) |
| Using p is equal to mn=1, we can get the equations m=1/n. |
| From q, we substitute the value of m to the equation from p. m=1/n, 1=1/n, n=1. <br>This satisfies the given n=1. |
| From r, we substitute the value of m to the equation from p. m=1/n, -1=1/n, n=-1. <br>This satisfies the given n=-1. |
| <b>We used direct proof.</b> |

