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
