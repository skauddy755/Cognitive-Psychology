[[weekly_readings]] #week-1 #ch-1 

# Contents

1. The reaction against behaviorism in psychology (Section 1.1)
2. The idea of algorithmic computation in mathematical logic (Section 1.2)
3. The emergence of linguistics as the formal analysis of language (Section 1.3)
4. The emergence of information-processing models in psychology (Section 1.4)

# (1) - The reaction against behaviorism in psychology

Behaviorists think that,
- psychologists should avoid speculating about unobservable mental states,
- and instead focus on nonpsychological mechanisms linking particular stimuli with particular responses. (S-R associations)
- These mechanisms are the product of conditioning.
- eg- Pavlov's dog being conditioned to salivate at the sound of bell.

Some of the ideas that proved important for the later development of cognitive science by looking at 3 landmark papers:
- Learning without reinforcement:
  **'Insight' in Rats (1930)** - by Tolman and Honzik
- Cognitive Maps in Rats?
  **Studies in Spatial Learning (1946)** - by Tolman, Ritchie, Kalish
- Plans and Complex bahaviors:
  **The problem of serial order in behavior (1951)** - by Karl Lashley

## 'Insight' in Rats (1930)

Two standard behaviorist assumptions about learning.
- All learning is the result of conditioning.
- Conditioning depends upon processes of association and reinforcement.

We can understand these two assumptions by thinking about a rat in a Skinner box.

>In classical conditioning what is strengthened is the association between a conditioned stimulus (such as the typically neutral sound of a bell ringing) and an unconditioned stimulus (such as the presentation of food). The unconditioned stimulus is not neutral for the organism and typically provokes a behavioral response, such as salivation

Tolman and Honzik were interested in how rats learned to navigate mazes. They ran three groups of rats through a maze.
- g1: received a reward each time they successfully ran the maze.
- g2: never received a reward.
- g3: was unrewarded for the first ten days and then began to be rewarded.

**OBSERVATIONS:**
- g1 learned first
- g2 never learned
- g3 when started receiving rewards, they learned far more quickly than g1

**CONCLUSIONS:**
Behaviorism can explain g1 and g2:
since g1 received reward their SR-mapping became strong, and g2 were acting randomly
But they failed to explain g3:
had they been correct, then after g3 started getting reward they should have taken the same amount of time to learn as g1 (and not faster). This means they must have been learning all this while (and it was happening even without any reward).

> Tolman and Honzik argued that the rats must have been learning about the layout of the maze during the period when they were not being rewarded.
> This type of latent learning seemed to show that reinforcement was not necessary for learning, and that the rats must have been picking up and storing information about the layout of the maze when they were wandering around it, even though there was no reward and hence no reinforcement.

***QUESTIONS: But are the rats simply remembering the sequence of moves?***

Tolman and his students and collaborators designed many experiments during the 1930s and 1940s to try to decide between **place learning** and **response learning** accounts of how rats learn to run a maze. Some of these experiments were reported in a famous article in 1946.

## Studies in Spatial Learning (1946)

One experiment used a cross-maze with four end points (North, South, East, West)
Rats were started at North and South on alternate trials.
g1: rewarded by the food at the same end point (say East) - **place learning**
g2: rewarded by the food at the same turning (East for North headed rats and West for South headed rats) - **response learning**

**OBSERVATION:**
g1 learned to run the maze much more quickly than g2.
This implied, place learning > response learning.

**CONCLUSION:**
Nature of animal learning in general:
It was easier for animals to code spatial information in terms of places rather than in terms of particular sequences of movements.

**RESULT**
- Tolman took his place-learning experiments as evidence that,
  Animals form *high-level representations of how their environment is laid out*
  – what he called **cognitive maps**.
- Tolman’s cognitive maps were one of the first proposals for explaining behavior in terms of **representations (stored information about the environment)**

## The Problem of Serial Order in Behavior (1951)

**COMPLEX BEHAVIORS:**
- Behaviorisms: They have to view them as linked sequences of responses
- **The standard behaviorist** view is that rats learn to chain together a series of movements that leads to the reward.
- **Tolman** showed that this is not the right way to think about what happens when rats learn to run mazes.
- **Lashley** made the far more general point that this seems to be completely the wrong way to think about many complex behaviors.

> - According to Lashley, we should think about many of these complex behaviors as products of **prior planning and organization**.
> - The **behaviors are organized hierarchically** (rather than linearly)

Lashley’s essay contains the seeds of two ideas:
1. **hypothesis of subconscious information processing**
   Even though we are often conscious of our high-level plans and goals (of what goes on at the top of the hierarchy), we tend not to be aware of the information processing that translates those plans and goals into actions.
   - Example: consiously have intention to pick a glass, but calculations of the exact trajactory of hand is done far below the threshold of consious awareness.
   
2. **hypothesis of task analysis**
   understand a complex task (and the cognitive system performing it) by breaking it down into a hierarchy of more basic subtasks (and associated subsystems)
   - Example: Task to exploit previously acquired information can be broken down as-
     subtask: storing info - (sub-sub-task: long term, short-term)
     subtask: retrieving info

# (2) - The idea of algorithmic computation in mathematical logic

- In 1936–7 **Alan Turing** published an article in the *Proceedings of the London Mathematical Society* that introduced some of the **basic ideas in the theory of computation**.
- **Computation** is what computers do and, according to many cognitive scientists, it is what minds do.
- What Turing gave us was a **theoretical model** that many have thought to capture the essence of computation.

## Algorithms and Turing Machines

***"On Computable Numbers, with an Application to the Decision Problem" (1936-7)***

- Many computer programs are not defined for every possible input.
- They will give a solution for some inputs, the ones for which they are defined.
- But for other inputs, the ones for which they are not defined, they will just endlessly loop, looking for a solution that isn’t there.

*It is important to tell, whether the program is simply taking a long time to get to a solution, or is it stuck in an endless loop.*

**Solution to the HALTING PROBLEM:**
Given, a computer program and a given input(s).
Can we tell, whether the program is defined for this input or not.
The solution has to work both ways: "Yes" if defined and "No" if not defined.

- Turing was looking for a ***purely mechanical solution*** to the Halting Problem.
- For this, he needed to make the solution more precise - an **Algorithm**

**TURING MACHINE:**
- Any individual Turing machine has a **machine table (set of instructions)**.
- The machine can be in any finite number of different states.
- The machine table will determine, what the machine will do:
	1. when it encounters a given **symbol**
	2. in a particular **cell**
	3. depending upon its **internal state**
- There is no ambiguity and no room for the machine to exercise “intuition” or “judgment.”

**OUTCOMES:**
- Turing's paper contained a subtle proof that **Halting Problem cannot be solved**.
- **Church-Turing thesis:** Anything that can be done in mathematics by an algorithm, can be done by Turing machine.

**CONTRIBUTION to Cognitive Science:**
- A model of computation that looked as if it might be a clue to how **information could be processed by the mind**.
- As theorists moved closer to the idea that **cognition involves processing information** it was an easy step to think about **information processing as an algorithmic process** along the lines analyzed by Turing.


# (3) - Linguistics and the Formal Analysis of Language

Language usage:
1. **hierarchically organized complex behavior** - Karl Lashley
2. **can be analyzed in algorithmic terms** - due to the emergence of tansformational linguistics and the formal analysis of syntax.

## Syntactic Strutures (1957) - by Noam Chomsky

**"why" (rather than "how") languages work the way they do**

Structure of any language:
1. **Deep Structure** (phase structure grammer) - formed by basic parts of speech: nouns, verbs, adjectives. Similar in all languages
2. **Surface Structure** - The actual organization of words in a sentence.

- Analyzing sentences in terms of their phrase structure is a powerful explanatory tool.
- There are pairs of sentences that have very **different phrase structures, but are clearly very similar in meaning**.
	- eg- “John has hit the ball” and “The ball has been hit by John.”
	- In most contexts these sentences are equivalent and interchangeable, despite having very different phrase structures
- The transformational principles of **transformational grammar** are examples of **algorithms**.
- They specify a set of procedures that operate upon a string of symbols to convert it into a different string of symbols.


**CONTRIBUTION to Cognitive Science**
Provided a very clear example of **how to analyze (in algorithmic terms)**, the bodies of information that might underlie certain very **basic cognitive abilities** (such as the ability to speak and understand a language)

