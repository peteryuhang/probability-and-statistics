## Experiment and Event

- An experiment is any process, real or hypothetical, in which the possible outcomes can be identified ahead of time
- An event is a well-defined set of possible outcomes of the experiment

## Set Theory

- This section develops the formal mathematical model for events, namely, the theory of sets

### Sample Space

- The collection of all possible outcomes of an experiment is called the sample space of the experiment
- The sample space of an experiment can be thought of as a **set**, or collection, of different possible outcomes; and each outcome can be thought of as a **point**, or an **element**, in the sample space. Similarly, events can be thought of as **subsets** of the sample space

### Relations of Set Theory

- In order to be able to do all of the probability calculations that we might find interesting, there are three simple conditions that must be met by the collection of sets that we call events
  1. The sample space `S` must be an event
  2. If `A` is an event, then `Ac` is also an event
  3. If A1, A2, . . . is a countable collection of events, then `A1 ∪ A2 ∪ ...` is also an event

- Definitions:
  1. For events, to say that `A ⊂ B` means that if `A` occurs then so does `B`
  2. **Empty Set**: The subset of `S` that contains no elements is called the empty set, or null set, and it is denoted by the symbol `∅`. In terms of events, *the empty set is any event that cannot occur*
  3. **Countable/Uncountable**. An infinite set `A` is countable if there is a one-to-one correspondence between the elements of `A` and the set of natural numbers `{1, 2, 3, . . .}`. A set is uncountable if it is neither finite nor countable. If we say that a set has at most *countably many elements*, we mean that the set is either finite or countable

- Theorems:
  1. Let `A`, `B`, and `C` be events. Then `A ⊂ S`. If `A ⊂ B` and `B ⊂ A`, then `A = B`. If `A ⊂ B` and `B ⊂ C`, then `A ⊂ C`
  2. Let `A` be an event. Then `∅ ⊂ A`

### Operations of Set Theory

- Definitions:
  1. **Complement**: The complement of a set `A` is defined to be the set that contains all elements of the sample space `S` that do not belong to `A`. The notation for the complement of `A` is `Ac`. In terms of events, the event `Ac` is the event that `A` does not occur
  2. **Union of Two Sets**: If `A` and `B` are any two sets,the union of `A` and `B` is defined to be the set containing all outcomes that belong to `A` alone, to `B` alone, or to both `A` and `B`.The notation for the union of `A` and `B` is `A ∪ B`
  3. **Union of Many Sets**: The union of `n` sets `A1,...,An` is defined to be the set that contains all outcomes that belong to at least one of these `n` sets

- Theorems:
  1. Let `A` be an event. Then: `(Ac)c =A`, `∅c = S`, `Sc = ∅`. The empty event `∅` is an event
  2. For all sets `A` and `B`, `A ∪ B = B ∪ A`, `A ∪ A = A`, `A ∪ Ac = S`, `A ∪ ∅ = A`, `A ∪ S = S`. Furthermore, if `A ⊂ B`, then `A ∪ B = B`