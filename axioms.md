# Axioms

Axioms are fundamental truths or principles that serve as the foundation for a
system of thought, logic, or mathematics. They are accepted without proof and
are used to derive further truths within a given framework.

## Characteristics of Axioms

1. **Self-Evident**: Axioms are often considered self-evident truths that do not require proof.
2. **Foundation**: They serve as the foundational building blocks for theories and systems.
3. **Universality**: Axioms are generally accepted within a specific context or field.
4. **Independence**: Axioms should be independent of one another, meaning that no axiom can be derived from the others.
5. **Consistency**: A set of axioms should not lead to contradictions within the system.

## Examples of Axioms

- **Mathematics**: In Euclidean geometry, one of the axioms is that through any two points, there is exactly one straight line.
- **Logic**: The law of non-contradiction states that a statement cannot be both true and false at the same time.
- **Set Theory**: The axiom of choice states that given a collection of non-empty sets, it is possible to select one element from each set

## Axioms in Logic

### Law of Non-Contradiction

Thought: Can a statement be both true and false at the same time? Like saying "It is raining" and "It is not raining" simultaneously?

A statement cannot be both true and false at the same time.

1. "It is raining" cannot be both true and false simultaneously.
2. If "It is raining" is true, then "It is not raining" must be false.

Examples:

- If a number x is greater than 5, it cannot simultaneously be less than or equal to 5.
- If a light is on, it cannot simultaneously be off.
- If a number is even, it cannot simultaneously be odd.

Exercise:

- Identify a situation where the law of non-contradiction applies.
- Can you provide an example of the law of non-contradiction in everyday life?
- Can you think of a real-life example where something cannot be both true and false at the same time?

### Law of Excluded Middle

A statement is either true or false; there is no middle ground.

Examples:

- "It is raining" is either true or false; there is no third option.
- A light switch is either on or off; there is no in-between state.
- A door is either open or closed; it cannot be partially open.

Question: Can you provide an example of the law of excluded middle in decision making?

### Modus Ponens

If it it raining (A) the is the ground is wet (B) ?
If it is dark outside (A) then is the sun is not visible (B) ?

#### Modus Ponens: Definition

If A holds true, and A implies B, then B must also hold true.

Example:

1. If it is raining (A), then the ground is wet (B).
2. It is raining (A).
3. Therefore, the ground is wet (B).

Examples:

- If a number is prime (A), then it has exactly two distinct positive divisors (B). The number 7 is prime (A), so it has exactly two distinct positive divisors (B).
- If a number is odd (A), then the square of that number is odd (B). The number 5 is odd (A), so the square of 5 (25) is odd (B).
  - Why ? How are we sure about that ? We need to prove it ? We will prove it later.
- If a kid doesn't do their homework (A), then they will not go outside to play (B). 

Exercise: Can you create your own example of Modus Ponens?

#### Mathematical Notation

1. A → B (If A then B)
2. A (A is true)
3. Therefore, B (B is true)

#### Truth Table for Modus Ponens

| A (It is raining) | B (Ground is wet) | A → B (If A then B)  | Conclusion (B) |
|-------------------|-------------------|----------------------|----------------|
| True              | True              | True  (possible)     | True           |
| True              | False             | False (impossible)   | False          |
| False             | True              | True  (possible)     | True           |
| False             | False             | True  (possible)     | False          |

### Modus Tollens

If A implies B, and B is false, then A must also be false.

Example:

1. If it is raining (A), then the ground is wet (B).
2. The ground is not wet (¬B).
3. Therefore, it is not raining (¬A).

Examples:

- If a number is even (A), then it is divisible by 2 (B). The number 7 is not divisible by 2 (¬B), so it is not even (¬A).
- If a shape is a square (A), then it has four sides (B). A triangle does not have four sides (¬B), so it is not a square (¬A).

Exercise: Can you create your own example of Modus Tollens?

#### Modus Tollens: Mathematical Notation

1. A → B (If A then B)
2. ¬B (B is false)
3. Therefore, ¬A (A is false)

#### Modus Tollens: Discussion Questions

- Create a truth table for Modus Tollens ?
- Can you think of a real-life example where Modus Tollens applies?
- Prove that if a number is not divisible by 2, then it is not even using Modus Tollens.
- Prove that if a shape does not have four sides, then it is not a square using Modus Tollens.

## Direct Proof

If A implies B, and B implies C, then A implies C.

Example:

1. If it is raining (A), then the ground is wet (B).
2. If the ground is wet (B), then the grass is slippery (C).
3. Therefore, if it is raining (A), then the grass is slippery

### Direct Proof: Discussion Questions

- Can you provide an example of a direct proof in everyday life?
- How does direct proof help in establishing logical relationships?
- Create your own example of a direct proof.

## Exercises

1. If $X^2$ is even, prove that $X$ is even using Modus Tollens.
2. If a number is divisible by 4, prove that it is even using Modus Ponens.
3. Prove that if a number is odd, then its square is odd using direct proof.
4. Create a truth table for the law of excluded middle.
5. Identify a situation in real life where the law of non-contradiction applies.

## Further Reading

- "Introduction to Logic" by Irving M. Cop
- "Axioms and Hulls" by Paul R. Halmos

