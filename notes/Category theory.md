[A Crash Course in Category Theory - Bartosz Milewski](https://www.youtube.com/watch?v=JH_Ou17_zyU)
### Intro

Programming can be divided in two paradigms : 
 - The **imperative programming**, which focuses on giving instructions to the machine similar to how the machine will actually process them. For example, we have **C** which is an abstraction layer over assembly, but that can be directly translated into byte-code (tokenizer-step compile). This paradigm is essentially *lowering humans to computers* by forcing us to think like computers, in a localized and linear way.
 - The **functional programming** which is similar to mathematical language. It employs a high level of abstraction, free from the constraints of the machine. 

Mathematics are supposed to represent the way *we* humans think. Mathematical teaching is bad, as it usually consists in some kind of *imperative paradigm*. Learning multiplication by hand is a good example (even better with matrix multiplication, what a pain). 

**Category theory** is maths freed from the stupid constraints of *imperative-ness*, its **fun**, it looks much nicer. It talks about *ideas* not numbers and bits.

Programming languages have different **semantics** (ways to convey meaning) :
 - **Operational semantics** (*if you do this then the next state would be this*) the program is seen as list of operations and conditions, very computer-like
 - **Notational semantics** (*this program has meaning because it can be translated into a language which we understand*) the program is basically a computer-y representation of maths. It can be seen as a mathematical *proposition* like a *proof* or a *theorem*.

Understanding **operational semantics** needs us to run the program in our heads, and act as a computer to figure out the logic. (*I'm very good at this*) 

# Functional programming

The computer evaluates the functions, but we don't care about it.

**Set theory** is like an assembly language of mathematics.

**Category theory** simplifies the *set theoric* views by reducing everything to two types of things:
 - **Objects** similar to types (*integer, list*)
 - **Morphisms** or **functions** like **arrows**, or relationships between **objects**.

**Set theory** defines properties of *sets* by talking about the elements of the sets, while **category theory** only describes them by their relationships with other *sets* or *objects*.  Its a change of perspective.

**Relationships** or **functions** are defines by *associativity*: $(f~ \circ ~g)~ \circ ~h = f~ \circ ~(g~ \circ ~h)$

Every object has an *identity function* that goes from itself back to itself: $\text{id}~ \circ ~f = f~ \circ ~\text{id} = f$

![[category theory.png]]

**Category theory** makes all complexity needed for programming from the simples principles above. It's like a new set of axioms applied to a reduced area.

A [[monoid]] is something that has an identity and stuff.

