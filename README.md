# PossibleWorlds
A Mathematical Framework for LLM Models based on the Possible Worlds Philosophies of David Lewis

**Equation 1**
W: The set of all possible worlds.
p: A proposition.
P(w): The truth value of proposition p in world w.
We can then define the following modal operators:

□p: p is true in all possible worlds.
◇p: p is true in at least one possible world.
We can then express Lewis's possible world semantics for counterfactuals as follows:

p ▷ q ≡ ∀w ∈ W[(P(w) ∧ ¬p(w)) → P(q(w))]
This equation states that the counterfactual "If p, then q" is true if and only if q is true in all possible worlds where p is true and false.

**Equation 2**
W: The set of all possible worlds.
R: A relation between possible worlds.
p: A proposition.
P(w): The truth value of proposition p in world w.
We can then define the following modal operators:

□p: p is true in all possible worlds accessible from the actual world.
◇p: p is true in at least one possible world accessible from the actual world.
We can then express Lewis's possible world semantics for counterfactuals as follows:

p ▷ q ≡ ∀w ∈ W[R(w, w') → (P(w) ∧ ¬p(w')) → P(q(w'))]
This equation states that the counterfactual "If p, then q" is true if and only if q is true in all possible worlds accessible from the actual world where p is true and false.

Which equation is more appropriate depends on the specific application. The first equation is more general, but it can be difficult to apply in practice. The second equation is more specific, but it is easier to apply in practice.

