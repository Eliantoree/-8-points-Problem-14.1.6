# -8-points-Problem-14.1.6
(8 points) Problem 14.1.6

**Download Link:https://programming.engineering/product/8-points-problem-14-1-6/**

Description
5/5 – (2 votes)
(8 points) Problem 14.1.6

Prove that every language with a finite number of strings is the language of some DFA.

(12 points) Problem 14.2.4

A string in {a, · · · , z}∗ is said to be panalphabetic if it contains at least one occurrence of each letter. Examples of panalphabetic strings are

thequickbrownf oxjumpsoverthelazydog

and

jackdawslovemybigsphinxof quartz.

Is the language of panalphabetic strings decidable by a DFA? Prove your answer.


(12 points) Problem 14.3.6

Prove that the DFA from Exercise 14.3.6 is minimal, either by running the minimization algorithm on it or by showing that each pair of states is L5-distinguishable.

(15 points) Problem 14.5.4

Let N be an ordinary NFA with k states. For every letter a ∈ Σ, define a k by k boolean matrix Ma such that Ma(i, j) is true if and only if <i, a, j> ∈ ∆. Define a function f from Σ∗ to the set of k by k boolean matrices by the rules f(λ) = I, f(wa) = f(w)Ma. Prove that w ∈ L(N) if and only if there is a final state f such that the (ι, f) entry of f(w) is true.

(16 points) Problem 14.6.9

Given a nonempty finite language S, consider the language CS = Σ∗SΣ∗ of strings that have

substring in S.

Describe an ordinary NFA for this language. (Note: The Yes-aba language is just C{aba}.)

Prove that the minimal DFA for any such language CS has exactly one final state.

Use the Subset Construction to find a DFA for the language CS where S = {aaa, bbb}. (You may invoke part (b) and not worry about distinguishing the different final states.)

Repeat part (c) for S = {abb, bab, bba}. Let Σ = {a, b}.

(15 points) Problem 14.7.6

Let N be a λ-NFA in which there are two states p and q with transitions <p, λ, q> and <q, λ, p>. Show that there is a λ-NFA N′, with L(N′) = L(N), such that N′ has a single state r instead of p and q. Should r be a final state? What if p or q is the start state? What should be the transitions in and out of r? Should any other transitions from N change? Prove that with your choices, L(N) = L(N′).

(12 points) Problem 14.8.7

In Section 5.5 we gave a recursive algorithm that decides whether the language of a given regular expression is empty.

(a) Prove that if N is a λ − N F A obeying our three rules, L(N) = ∅ if and only if there is no path from the start state to the final state in N.

Prove, by induction on all regular expressions α, that the emptiness tester of Section 5.5 returns false on input α if and only if the λ − N F A constructed from α has a path from the start state to the final state.


(10 + 5 extra ) Problem 14.10.3

(variant from the textbook)

Find a regular expression for the language of strings in {a, b}∗ whose number of a’s and number of b’s are congruent modulo 3. (Hint: Build a DFA and use state elimination. This gets a bit messy. The problem in the textbook has the number of a’s and the number of b both divisible by 3. We’ll give you five extra points for solving the original version.)

Extra Credit

(10 points) Problem 15.6.2

Build a Turing machine Mcopy that when started on input w (i.e., in configuration i□w), halts with the tape contents i□w□w. (Here i is the start state.) You need not give the entire state table as long as your description is clear and complete. Let Σ = {a, b}.
