# Dismathportfolio-AJFrancisco
Anne Janelle N. Francisco

# Week 1
- During our first meeting, we had a short seatwork just to recall the topics about Dismath. I was able to answer number 10 which was about the Euler.
- Sir also introduced to us the Propositions and asked us one by one about it. I was asked if x+9=11 is a proposition and I answered no because we do not know the true value of x which may or may not satisfy the statement.
- On our next meeting, we tacked about gates which was also discussed during our days in Logicir. 
- We answered the exercises (odd numbers) one by one in class. The questions were mainly about translating the equation into a statement with the given phrases. 



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


- 1.3 / 7c: Use De Morgan's laws to find the negation of the statement: Mei walks or takes the bus to class. <br> Answer: Mei does not walk and take the bus to class.

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

- 1.4 / 5: Let P (x) be the statement “x spends more than five hours every weekday in class,” where the domain for x consists of all students. Express each of these quantifications in English.<br> a) ∃xP(x) = There is a student who spends more than give hours every weekday in class.

- 1.4 / 7: Translate these statements into English, where C(x) is “x is a comedian” and F(x) is “x is funny” and the domain consists of all people.<br> c) ∃x(C(x)→F(x)) = There exist if he/she is a comedian, then he/she is funny.

- 1.4 / 11: Let P(x) be the statement “x = x2.” If the domain con- sists of the integers, what are these truth values?<br> b) P(1) = TRUE

- 1.4 / 13: Determine the truth value of each of these statements if the domain consists of all integers.<br> c) ∃n(n = −n) = TRUE

- 1.4 / 17: Suppose that the domain of the propositional function P(x) consists of the integers 0, 1, 2, 3, and 4. Write out each of these propositions using disjunctions, conjunc- tions, and negations.<br> b) ∀xP(x) = Conjunction

- 1.5 / 1: Translate these statements into English, where the domain for each variable consists of all real numbers.<br> b) ∀x∀y(((x ≥ 0)∧(y ≥ 0)) → (xy ≥ 0)) = For all x and for all y, if noth are not negative/positive, then the product is also not negative/positive.

- 1.5 / 3: Let Q(x, y) be the statement “x has sent an e-mail mes- sage to y,” where the domain for both x and y consists of all students in your class. Express each of these quantifi- cations in English.<br> f) ∀x∀yQ(x,y) = All students sent an email message to the whole class.

- Give an example for hypothetical syllogism, ((p → q) ∧ (q → r)) → (p → r).<br> If Punu is cute, then she is cuddly. And if Punu is cuddly, then she is short. Therefore, if Punu is cuddly, then Punu is short.

- Assignment given on June 23, 2016:

- 1.5 / 5: Let W (x, y) mean that student x has visited website y, where the domain for x consists of all students in your school and the domain for y consists of all websites. Ex- press each of these statements by a simple English sen-
tence.<br> c) ∃y W (José Orez, y ) = 

- 1.5 / 7: Let T(x,y)meanthatstudentxlikescuisiney,wherethe domain for x consists of all students at your school and the domain for y consists of all cuisines. Express each of these statements by a simple English sentence.<br> d) ∀x∀z∃y((x̸=z)→¬(T(x,y)∧T(z,y))) =

- 1.5 / 9: Let L(x, y) be the statement “x loves y,” where the domain for both x and y consists of all people in the world. Use quantifiers to express each of these statements.<br> e) There is somebody whom Lydia does not love. = 
