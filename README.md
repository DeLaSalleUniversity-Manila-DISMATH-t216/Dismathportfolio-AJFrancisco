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

- 1.8 / 1: Prove that n2 + 1 ≥ 2n when n is a positive integer with 1≤n≤4.

  | Proof by cases | ** |
| :--- | :--- |
| <b>@ n = 1</b><br>1^2 + 1 ≥ 2^1<br>2 ≥ 2<br>Correct! | <b>@ n = 2</b><br>2^2 + 1 ≥ 2^2<br>4 + 1 ≥ 4<br>5 ≥ 4<br>Correct! |
| <b>@ n = 3</b><br>3^2 + 1 ≥ 2^3<br>9 + 1 ≥ 8<br>10 ≥ 8<br>Correct! | <b>@ n = 4</b><br>4^2 + 1 ≥ 2^4<br>16 + 1 ≥ 16<br>17 ≥ 16<br>Correct! |<br>

- Here are some exercises my classmates guided me through:

- 1.7 / 29: Prove or disprove that if m and n are integers such that mn = 1, then either m = 1 and n = 1, or else m = −1 and n = −1.

  | m and n are integers |
| :--- |
| mn = 1 ; m=1 and n=1 OR m=-1 and n=-1 |
| mn=1 → {[(m=1) ∧ (n=1)] OR [(m=-1) ∧ (n=-1)]} ; p → (q v r) |
| Using p is equal to mn=1, we can get the equations m=1/n. |
| From q, we substitute the value of m to the equation from p. m=1/n, 1=1/n, n=1. <br>This satisfies the given n=1. |
| From r, we substitute the value of m to the equation from p. m=1/n, -1=1/n, n=-1. <br>This satisfies the given n=-1. |
| <b>We used direct proof.</b> |

- Assignment for July 7, 2016
- 1.8 / 7: Prove the triangle inequality, which states that if x and y are real numbers, then |x| + |y| ≥ |x + y| (where |x| represents the absolute value of x, which equals x if x ≥ 0 and equals −x if x < 0).
  We use <b>Exhaustive proof</b>
  * Case 1<br>x ≥ 0 ; y ≥ 0<br>|x| + |y| = x + y = |x+y|
  * Case 2<br>x < 0 ; y < 0<br>|x| + |y| = |-x| + |(-y)| = |-(x+y)| = |x+y|
  * Case 3<br>x ≥ 0 ; y < 0<br>|x| + |y| = x + (-y) > x + y = |x + y|

- I was able to answer the following in class today (July 7, 2016)
  * 2 / 1.c: List the members of these sets, {x|x is the square of an integer and x < 100}<br><b>1,2,3,4,5,6,7,8,9,10,11</b>
  * 2 / 4.b: For each of these pairs of sets, determine whether the first is a subset of the second, the second is a subset of the first, or neither is a subset of the other. The set of fruits, the set of citrus fruits.<br><b>The second set is the subset of the first set.</b>
  * 2 / 7.b: For each of the following sets, determine whether 2 is an element of that set. {x ∈ R|x is the square of an integer}<br><b>No</b>
  * 2 / 9.d: Determine whether each of these statements is true or false. ∅ ⊂{0}.<br><b>0 is a subset to every set, so true.</b>
  * 2 / 10.d: Determine whether these statements are true or false. {∅} ∈ {{∅}}.<br><b>True</b>
  * 2 / 11.d: Determine whether each of these statements is true or false. {x}∈{{x}}.<br><b>True</b>
  * 2 / 21.a: Find the power set of each of these sets, where a and b are distinct elements. {a}.<br><b>{0,{a}}</b>
  * 2 / 24.a: Determine whether each of these sets is the power set of a set, where a and b are distinct elements. ∅.<br><b>Yes, power set of a null set.</b>
  
- I was able to answer the following in class today
  * 2.1 / 1.b: List the members of these sets, {x | x is the square of an integer and x < 100}<br>
  * 2.1 / 4.b: For each of these pairs of sets, determine whether the first is a subset of the second, the second is a subset of the first, or neither is a subset of the other.<br>
  * 2.1 / 7.b: For each of the following sets, determine whether 2 is an element of that set.<br>
  * 2.1 / 9.d: Determine whether each of these statements is true or false, d) ∅ ⊂ {0}
  * 2.1 / 10.d: Determine whether these statements are true or false, d) {∅} ∈ {{∅}}  <br>
  * 2.1 / 11.d: Determine whether each of these statements is true or false, d) {x} ∈ {{x}}<br>

# Week 5
- QUIZ 1 and CALL OFF

# Week 6

| Function | Definition |
|:---|:--|
| One to One Function | One domain is to one codomain |
| Onto Function | One domain can have two codomains |
| One to One AND not Onto Function | One domain is to one codomain, but there is one codomain that has no domain |
| Onto AND not One to One Function | There is one codomain that has two domains |
| One to One AND Onto Function | One domain is to one codomain |
| Neither One to One NOR Onto Function | There is one codomain that has two domains AND one codomain that has no domain |
| Not a function | There is a domain that has two codomains |

- I was able to answer the following in class today
  * 2.3 / 3c: Determine whether f is a function from the set of all bit strings to the set of integers if: f (S) is the smallest integer i such that the ith bit of S is 1 and f (S) = 0 when S is the empty string, the string with no bits.<br><b>Not a function</b>
  * 2.3 / 5a: Find the domain and range of these functions. Note that in each case, to find the domain, determine the set of elements assigned values by the function: the function that assigns to each bit string the number of ones in the string minus the number of zeros in the string.<br><b>Domain = set of bit strings and Range = set of integers</b>

- Assignment
- 2.3 / 17: Consider these functions from the set of teachers in a school. Under what conditions is the function one-to-one if it assigns to a teacher his or her:
  * a) office. <b>It depends if its office sharing or not</b>
  * b) assigned bus to chaperone in a group of buses taking students on a field trip. <b>It depends if one chaperone is assigned with one or two buses.</b>
  * c) salary. <b>Not one to one function. Some salaries depend of the number of years of the teacher or his/her professionalism.</b>
  * d) social security number. <b>One to one function because no to numbers should be alike.</b>
