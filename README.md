# My Dismath Portfolio

  John Carlo G. Victory

## Week 1:
  * Discrete Mathematics deals with mathematical proofs
  * Proof - chain of logical deduction leading to the proposition from a base set of axioms
    - Statement is either true or false
    - Mathematical reasoning
  * We learned about 
    - Truth Tables
    - Propositions:
      - inverse of p→q which is ¬p → ¬q
      - converse of p→q which is q → p
      - contrapositive of p→q which is ¬q → ¬p
    - Logical Connectives:
      - (¬) Negation
      - (∧) Conjunction
      - (∨) Disjunction
      - (⊕) Exclusive Disjunction
      - (→) Implication
      - (↔) Biconditional
  * Math Expression:
    - ¬p = val(¬p) = 1-val(*p)
    - ∧ = val(p∧q) = min(val(p),val(q))
    - ∨ = val(p∨q) = max(val(p),val(q))
    - ⊕ = val(p) != val(q) = T, otherwise F
    - → = val(p) <= val(q) = T, otherwise F
    
## Week 2:
  * We've learned all about the Logical Equivalences / Laws
    - (pvF≡p | p∧T≡p)                             Identity
    - (pvT≡T | p∧F≡F)                             Domination
    - (p∧¬p≡F | p∨¬p≡T)                           Negation
    - (¬(¬p)≡p )                                  Double Negation
    - (p∨p≡p | p∧p≡p)                             Idempotent
    - (q∨p≡q∨p | p∧q≡q∧p)                         Commutative
    - ((p∨q)∨r≡p∨(q∨r) | (p∧q)∧r≡p∧(q∧r))         Assosiactive
    - (p∨(q∧r)≡(p∨q)∧(p∨r) | p∧(q∨r)≡(p∧q)∨(p∧r)) Distributive
    - (¬(p∧q)≡¬p∨¬q | ¬(p∨q)≡¬p∧¬q)                De Morgan's
    - (p∨(p∧q)≡p | p∧(p∨q)≡p)                     Absorbtion
  - Remember: Laws are Reversible.
  * Other Laws:
    - (p→q≡¬pv¬q)                                 Implication
    - (¬T≡F | ¬F≡T)                               Using negation on T and F
    - (p→q≡¬q→¬p)                                 Contrapositive
  * Quantifiers:
    - (∀(x))                                      Universal; "for all..."
      - T = p(x) is true for every x
      - F = there is an x for which p(x) is false.
    - (∃(x))                                      Existential; "there exist..."
      - T = there is an x for which p(x) is true.
      - F = p(x) is false for every x.
  * Predicate Logic = includes the internal structure in terms of SUBJECT and PREDICATE.
  * Propositional Logic = Deals with proposition as a whole.
  
## Week 3:
  * we were given a few examples about negation quantifiers and nested quantifiers.
    - two quantifier is nested if one is within the scope of the other.
  * We've learned about the rules of inference.
    - Argument = sequence of statement that ends with a conclusion
    - Valid = the argument must follow from the truth.
    - Fallacy = common form of incorrect reasoning which lead to invalid arguments.
  
  - Premise = statement composed of one or more proposition
    - P1 = "If I am a woman, then I will rule the world"
    - P2 = "I am a woman"
    
    - ∴ = "I will rule the world."
        - Valid 
        - Logical Expression: 
        - p→q
        - p
        - ∴ q
  * Tautology = statement that is always true.
    - (p ∧ (p → q)) → q               Modus Ponens            (p; p → q; ∴ q)
    - (¬q ∧ (p → q)) → ¬p	            Modus Tollens           (¬q; p → q; ∴ ¬p)
    - ((p → q) ∧ (q → r)) → (p → r)   Hypothetical Syllogism  (p → q; q → r; ∴ p → r)
    - ((p ∨ q) ∧ ¬p) → q              Disjunctive Syllogism   (p v q; ¬p; ∴ q)
    - p → (p ∨ q)                     Addition                (p; ∴ p v q) 
    - (p ∧ q) → p                     Simplification          (p ∧ q; ∴ p)
    - ((p) ∧ (q)) → (p ∧ q)           Conjunction             (p; q; ∴ p ∧ q)
    - ((p ∨ q) ∧ (¬p ∨ r)) → (q ∨ r)  Resolution              (p v q; ¬p v r; ∴ q v r)
      - There were several examples given to understand more about the rules of inference.
  
## Week 4:
  * We've learned the different methods of proof:
    - Direct
        - Assume p is TRUE.
        - Show that q must be TRUE.
    - Contraposition
       - ¬q → ¬p
        - Assume ¬q is TRUE.
        - Show that ¬p must be TRUE. 
    - Vacuous
      - ¬p → (p → q)
        - Show that q is FALSE.
        - because p → q must be true when p is FALSE.
    - Trivial
      - Q → (P → Q)
        - Show that q is TRUE.
        - It follows that p → q must also be TRUE.
    - Contradiction
      - ¬(Premise) = T
        - Assume that the premise is not true.
        - Show that the premise will end up in contradiction.

## Week 5:
  * We've continued to discuss about proof of contradiction
    - In contradiction, you must remember the rule:
      - A/B | A,B ∈ Z
      - B ≠ 0
      - A,B should have no common factor except ± 1.
  * We've also tackled the negation of implication
    - If p is true, then q is true.
      - There is atleast one case when p is true then q is false.
  * Proof by Equivalence (Biconditional) was also introduced.
    - p ↔ q, then
    - p → q is true and
    - q → p is also true.
  * There were several examples given on both Contradiction and Equivalence lessons.
  * Remeber: "When you have eliminated all which is impossible, then whatever remains, however improbable, must be the truth." - Sir Arthus Conan Doyle.
  
## Week 6:
  * Today we've recalled about Set Theories.
    - Union
    - Intersection
    - Set Difference
    - Symmetric Difference
    - Ø ≠ {Ø}
  * Set Membership
    - ∈ and ∉
  * Set Builder Notation
    - { x | some property x satisfies }
      - { 2x | x ∈ Z }
  * Different Set
    - A ∪ B                 UNION                       A ∪ B = { x | (x∈A) v (x∈B) }  
    - A ∩ B                 INTERSECTION                A ∩ B = { x | (x∈A) ^ (x∈B) }
    - A - B or A \ B        SET DIFFERENCE              A - B or A \ B = { x | (x∈A) ^ (x∉B) }
    - A∆B                   SYMMETRIC DIFFERENCE        A∆B = { x | ((x∈A) ^ (x∉B)) v ((x∈B) ^ (x∉A)) }
  * Subsets
    - S ⊆ T = All elements of S is also an element of T.
    - A = { x, y }
  * Power Set
    - p(S) = { T | T ∈ S }
    - p(A) = { {x}, {y}, {x,y}, Ø }
    - B = { x, y, z }
      - p(B) = { {x}, {y}, {z}, {x,y}, {x,z}, {y,z}, {x,y,z}, Ø }
  * We've also discussed about Power Series
    - Example: Zeno's Paradox (can be solved using GEOMETRIC SERIES)
    - A1 / 1-R
  * Cardinality
    - Number of Element it contains
    - | S |
      - |{A, B, C, D, E}| = 5.
      - |{1, 2, 3, 3, 3}| = 3.

## Week 7
  * This week, we've discussed about Functions.
    - Assinging an element from set A to set B.
      - Set A (Domain)
      - Set B (co-Domain)
      - Actual occuring value from A to B (Range)
  * Types of Functions:
    - one - to - one function (injective)
      - Never assign the same value to two different domain elements.
        - f(x) = x + 1
        - ∀x1∀x2(f(x1) = f(x2) → (x1=x2)) ; x1, x2 ∈ A
    - onto function (surjective)
      - Function that has an equal range and co domain
        - x + 1 = onto
        - x^2 = not onto.
    - one - to - one correspondence (bijective)
      - Both Injective and Surjective
      - Venn Diagram: Intersection between two set is the bijective.
      
## Week 8
  * This week, we learned about Algorithms
      - Finite set of instructions for solving a problem.
      - Pseudocode (high-level description of algorithm)
          - Input
          - Body
          - Output
        - For a pseudocode to be correct, you need:
          - Definiteness                Definitely precise
          - Correctness                 Output value is correct
          - Finiteness                  Limited to the input
          - Generality
  * Also we tackled about Searching.
      - Linear Search
        - one by one search
          - input: { A1, A2, ..., An }
          - output: Aindex { found: {1, ..., n} ; else: -1
      - Binary Search
          - Divide the list into half
            - Upper half & Lower half
            - Until the last number/index.
          - in Binary search, sorting is required.
  * And lastly, we discussed about Sorting.
      - Bubble
      - Insertion
    - Pseudocode for sorting is a longer than the pseudocode for search.
    - 
## Week 9
