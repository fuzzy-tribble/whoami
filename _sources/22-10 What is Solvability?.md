# Notions of Solvability
<span style="float:right; font-size:0.9em;">October 2022</span>

<span style="font-size:0.9em; font-style:italic;">
#computability #Gödel #Turing
</span>
</br></br>

>This post contains wandering thoughts on the nature of problems, solvability and computability. In computer science and mathematics text we ofen see problems discussed in terms of solvability, decidability, and computability. Computational complexity theory is beautiful but I think horribly narrow-minded with regard to how it captures effort to solve problems. 

In standard computability theory, Gödel’s incompleteness theorems and Turing’s Halting Problem form the backbone of how we think about solvability. They define the boundaries of what can be known or computed within a given formal system.

Gödel showed that in any consistent axiomatic system powerful enough to express arithmetic, there will be true statements that cannot be proven within that system—and that such a system cannot demonstrate its own consistency from the inside. Turing showed that no general procedure exists to decide whether an arbitrary program halts on a given input. These results ground our understanding of what it means for a problem to be solvable or decidable.

But crucially, Gödel wasn’t claiming that solvability is absolute. On the contrary, his work reveals that solvability is relative to a given formal system. That’s not a departure from my view—it’s the basis for it.

My perspective picks up from there: different rule structures—different axiomatic systems—offer different notions of what’s solvable. In computational systems especially, we have to think in terms of coupled systems: the observer and the observed, the solver and the system being solved. Solvability isn’t some independent property of a problem “out there.” It emerges from the interaction between a problem and the structure we use to frame it.

To me, a problem is unsolvable in a given rule structure not because it is inherently unsolvable, but because we haven’t found—or don’t know—what rule structure could solve it. This shifts the question:

- If a problem is unsolvable in one system, is it solvable in another?
- Are there problems that remain unsolvable across all systems?
- And how do we even begin to formalize such questions?

This leads me to think more about the dynamics between axiomatic systems—their capacities, transformations, and translations. What does it mean to shift between them? Can we develop metatheories that help us navigate or relate these spaces of rules?

In that sense, solvability isn’t just a question about logic or computation—it’s a question about structure, language, and how we move between them.

It seems like we don't have a framework for moving between rule systems that is telling. Category Theory I hoped would offer some tools and insights but my (non-expert) intuition is that defining objects by their relationship to others doesn't capture enough richness to offer practical utility across the sciences.