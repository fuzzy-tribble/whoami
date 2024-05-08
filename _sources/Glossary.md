# Glossary

A glossary of common terms used throughout my writings.

*Note that my intention is not to give formal definitions (those are available in excess elsewhere) but rather an intuitive sense of the term in the context of my writings.*

```{glossary}
DIP
  The Diverse Intelligence Puzzle (DIP) what I call the puzzle of how we can identify, understand, interact with and engineer all possible constructs of intelligence or agents.
```

```{margin} Unconventional Computation vs Diverse Intelligence
It is noteworthy that {term}`unconventional computation` and diverse intelligence though related are distinct. They both challenge the narrowness of our perspectives in the spheres of computation but not all computational processes are intelligent. Intelligent processes are a subset of computational processes that have competency navigating a space.
```

```{glossary}
DIP Terminology
  In the context of the DIP, terms like **intelligence**, **computation** and **programming** are used in a general sense and tend to have an information theoretic flavor.
  
  **Intelligence** (or sometimes *agent* or *cognitive agent*) referrs to a *distinguishable system that has domain competentcy* (I like Mike Levin's succinct definition: "competency navigating a space").

  **Computation** referrs to a *physical process that is also an information process* (IP). It can be a reliable IP like the result of typing 2+2 on your calculator or a less reliable process like the transformation undergone when light reflects off a bubble. The more reliable processes tend to be more interesting from an engineering perspective but a computation in and of itself is simply about state transformation. (Note that a 'computer' (or *information processing system*, IPS) is the physical system that realizes a computation. In the context of my work a computer is not thought of as a standalone system but rather as a dynamical system coupled with its environment.)
  
  **Programming** in the most general sense is the *method by which a computer is configured* (ie. its about configuring an IPS/computer). This configuration can be done via textual interface and include the set of algorithms that are conditionally and iteratively controlled (ie Python code on your laptop) or it could be encoding an initial state that evolves toward an attractor or some other way. It can be manual with a separate execution step. It can be a continuous process like a conversation between two people (ie. two coupled dynamical IPSs configuring each others state spaces as they share and understand ideas).
```

```{margin}
A computation is a physical process that is an information process which means that it depends only on the form of its state and not the matter to fulfill its purpose.
```

```{glossary}
Unconventional Comp
  In these writings "conventional computation" refers to computational processes like those on your laptop. They are typically characterized by: *binary digital electronics, sequential logic, discrete data representation, discrete memory _units (_addressable_ via natural_ numbers), programs stored in memory, conditional and iterative control/programming methods, etc*. On the other hand "unconventional computation" refers to everything that is not that like embodied computation, field computation, etc. These systems are typically characterized by: *asynchronous operations, not separating memory and processing, often non-deterministic, etc.*

[Information Media](https://www.constructortheory.org/wp-content/uploads/2016/03/ct-info.pdf)
  A physical system capable of carrying information. Any physical medium/system whose state/configuration has the following properties: 1) can be copied, and 2) can be something else (ie. can be fliped). This forms the basis of a universal set in information theory. The fact that the receiver of said information can distinguish between at least two states in a medium and that the state could be at least one other thing makes it possible for that system to carry information and thus be an information medium.

Knowledge
  A particular kind of information media which can perpetuate itself.

Information Process
  A process that can be *realized in any physical system* that supports the distinctions and transformations in the computation/process

Undefined understood
  These are things that we all tend to agree on but that have no well formed definition for. They have to do with concept alignment in the absence of a strong linguistic encoding (non-analogical). In social psychology, they have been studied under consensus reality or shared reality research.

Space & Structure
  That is--the mathematical kind. Imagine you have a bag of various balls—like soccer balls, basketballs, and ping-pong balls—and you want to talk about how to measure their size, how to add two balls together to get a new kind of ball, and how to make a ball bigger or smaller (scaling). In math, a "space" is like a bag—it's a collection of things you're interested in. The objects and the types of things you how you want to combine the things in the bag and the rules for how they transform (ie. combine) create the structure of the space.

Metric Space
  A metric space is a set of objects where it makes sense to talk about disance (a 'metric') between them. The metric has to follow these rules:
    - Non-negativity: The distance between two points is always non-negative, and the distance is zero if and only if the two points are the same.
    - Symmetry: The distance from point A to point B is the same as the distance from point B to point A.
    - Triangle Inequality: The distance from point A to point C is less than or equal to the sum of the distances from point A to point B and from point B to point C.
  These properties ensure that the concept of distance within the space behaves in a way that is consistent with how we intuitively understand distance in the physical world.

Homeomorphism
  Imagine you have two lumps of clay: one shaped like a cat and another like a dog. A homeomorphism is like being able to squish and stretch the clay from the cat shape into the dog shape without any tearing or gluing. If you can do this, then in the world of topology, the cat and the dog are considered the same, or "homeomorphic." The idea is that their basic "clay-ness" and the way they are connected are the same, even if they look different on the outside.

Banach Spaces
  Banach spaces are spaces of objects like functions or sequences (or other mathematical objects) that give us notions of adding, scaling and measuring the size of the objects. In the bag as a space analogy, a Banach space is a special bag where every time you start with a ball and keep making it smaller and smaller (like a sequence of functions getting closer and closer to each other), there is a smallest ball in the bag that you're getting closer to (ie. its 'complete' meaning that every convergent sequence of functions has a limit thats also in the space). 'Completeness' is handy because it lets us do calculus.

Markov Process
   In a Markov process, the only thing you need to know to figure out what might happen next is where you are right now, not the whole history of how you got there. I think about the "memory" of a Markov process as short.

Isomorphism
  The same in terms of their relationships
  An AI bot that has the same relationships as me is isomorphic to me
  The major concept that replaces equality in the context of categories. In category theory, it's more relevant to ask about the existence of an isomorphism between two objects rather than their equality. However, knowing that an isomorphism exists is not always enough; sometimes, it's important to identify a specific isomorphism with particular properties.

Fields
   A field is a set that allows for both addition and multiplication, and it has to follow specific rules that make it a robust structure for algebraic operations.

Field Computation
  Field computation in unconventional computing refers to computing methods that use continuous fields, like electrical or magnetic fields, to perform calculations. Instead of relying on digital bits, these methods use spatial and temporal variations in fields to encode and process information.

  In an optical computer, a simple computation like addition can be done as follows:

      Encoding: Input numbers are converted into light signals, often using the intensity or phase of the light to represent the value.

      Routing: Light beams are directed using mirrors, lenses, or fiber optics to the location where the computation will occur.

      Computation: The light beams interact in a nonlinear optical material. For addition, you could use a beam splitter that combines two input beams into a single output beam with an intensity equal to the sum of the inputs.

      Decoding: The output light signal is then converted back to a digital or analog form, representing the sum of the input numbers.

      Readout: The result is read from the output signal, completing the computation.

  This is a simplified example, but it captures the essence of how optical computing can perform calculations.

  When using polarization for optical computing, each light beam can have its polarization state set to represent a specific value or condition. Here's a basic example using polarization to implement a logical NOT gate:

      Encoding: Input is represented by a polarized light beam. Vertical polarization might represent a logical "1" and horizontal polarization a "0."

      Routing: The polarized light beam is sent to a polarization rotator, which is the computational element.

      Computation: The polarization rotator flips the polarization by 90 degrees. If the input was vertically polarized ("1"), it becomes horizontally polarized ("0"), and vice versa.

      Decoding: The output light beam's polarization is read and converted back to its logical representation.

      Readout: The result, a flipped logical value, is obtained from the polarization state of the output light.

  This example demonstrates that by using polarization, you can perform logical operations in a way similar to electronic logic gates but with light instead of electrical signals.

The Yoneda Lemma
  The categorical maxim that an object is completely determined by its relationships to other objects.

Limits
  Taking sub-things: A single element, an intersection, a preimage, a product. These are all formed by picking out a sub-collection of elements from given sets, contingent on some condition. (or maps whose domain is the limit)

Colimits
  Gluing things together: A set with no elements, disjoint unions, not-necessarily-disjoint unions, and quotients are all formed by assembling or 'gluing' things together. (or maps whose codomain is the colimit)

Monad
  A structure that represents computations defined as sequences of steps.

```
