## Sample Space

Two steps :
- Describe possible outcomes & beliefs about likelihood of outcomes

List (set) of possible outcomes, Ω (omega).

List must be:
- Mutually exclusive
- Collectively exhaustive
- At the "right" granularity

  
| Type       | Definition                                     | Example                       | Sample Space                             |
| ---------- | ---------------------------------------------- | ----------------------------- | ---------------------------------------- |
| Discrete   | Countable outcomes                             | Rolling a die                 | $\{1, 2, 3, 4, 5, 6\}$                   |
| Finite     | Limited number of outcomes                     | Tossing 2 coins               | $\{HH, HT, TH, TT\}$                     |
| Continuous | Uncountably infinite outcomes over an interval | Measuring time or temperature | $\{ t \in \mathbb{R}, 0 \le t \le 60 \}$ |


![Cartesian3](https://github.com/user-attachments/assets/5fc28ac9-ce18-486b-bc9d-a7422c191c55)

## Probability Axioms
1. Non-negativity: P(A) >= 0
2. Normalization: P(S) = 1
3. Additivity(mutually exc): P(AUB) = P(A) + P(B)

## Discrete Probability
P (X = x) = Number of favorable outcome / Total number outcome
S = {1, 2, 3, 4, 5, 6} 
Find P(X=4) = 1/6
Find P(X<=3) = 1/6 + 1/6 + 1/6 = 1/2

## Continuos Probability
P(X=x) = 0 (probability of exact value = 0) 
P(a <= X <= b) = ≤b)= ∫ba f(x)dx

<img width="559" alt="image" src="https://github.com/user-attachments/assets/89df8ef0-0ca4-449d-90be-2009e612640a" />

## Probability Calculation Steps
1. Specify sample space
2. Specify a prbability law
3. Identify an event of interest
4. Calculate

## Countable Additivity Axiom:
If A1, A2, A3,... is an infinite sequence of disjoint events, 
then P(A1, A2, A3,...) = P(A1) + P(A2) + P(A3)+ ...

- Additicity holds only for 'countable' event

## Intersection & Union
| Concept      | Symbol     | Meaning                        |
| ------------ | ---------- | ------------------------------ |
| Intersection | $A \cap B$ | Elements in both A **and** B   |
| Union        | $A \cup B$ | Elements in A **or** B or both |

<img width="664" alt="image" src="https://github.com/user-attachments/assets/3cfc06f9-19a5-433b-9e0e-759566ee7f9d" />

## De Morgan's Laws
<img width="525" alt="image" src="https://github.com/user-attachments/assets/d55ae121-ad51-4e0c-8dd8-414444938c4c" />
<img width="676" alt="image" src="https://github.com/user-attachments/assets/2cf8b3c3-669f-47d7-b072-11a4d0a07337" />

## When does a sequence converge? 
A sequence converges when its terms get closer and closer to a fixed number (called the limit) as n→∞.

Example: 
an = 1/n > {1, 1/2, 1/3, 1/4,...} 
As n→∞, an > 0 

<img width="362" alt="image" src="https://github.com/user-attachments/assets/2830cba2-fdc6-4c16-9ec9-2e35d239f331" />

​## Infinite Seires
The sum of the terms of an infinite sequence. 

<img width="140" alt="image" src="https://github.com/user-attachments/assets/cc218326-9b04-4e95-959d-71c5bc9ed12d" />
if ai >= 0, limit exists

If terms ai, do not all have same sign:
- limit need not exist
- limit may exist but be different if we sum in a different order

- Fact: limit exists and independent of order of summation if <img width="84" alt="image" src="https://github.com/user-attachments/assets/cf178f71-e464-43d2-a466-b6a29a4940bd" />


<img width="518" alt="image" src="https://github.com/user-attachments/assets/5161dac1-6eea-44f8-b275-aa30fbd4f4f5" />


<img width="479" alt="image" src="https://github.com/user-attachments/assets/56cb555b-d04f-4182-88cb-79fe067d74dd" />

## Countable vs Uncountable Infinite Sets
| Feature        | Countable                            | Uncountable                 |
| -------------- | ------------------------------------ | --------------------------- |
| Size           | "Listable"                           | "Too many to list"          |
| Infinite?      | Can be finite or infinite            | Always infinite             |
| Examples       | $\mathbb{N}, \mathbb{Z}, \mathbb{Q}$ | $\mathbb{R}, [0,1]$         |
| In probability | Discrete random variables            | Continuous random variables |


