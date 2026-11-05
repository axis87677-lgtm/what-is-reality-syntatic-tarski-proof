# Syntactic Reality: The Gödelian Formal System of the Universe

Lean 4 is the object language. It is used only to lock the inferences. The English argument is the metalanguage. It takes facts, or what science treats as true, plus other empirical material, and draws logical deductions from them to establish the premises. Those English deductions are the content of the argument. Once the premises are stated, each one is declared as an axiom in Lean. The conclusion is then written as a theorem that simply collects the axioms. Lean checks, by formal syntactic rules alone, that the conclusion follows from those axioms with no missing steps.

This is Tarski's distinction. The metalanguage (English) supplies the content and performs the reasoning from the given facts and empirical material. The object language (Lean) does not interpret quantum mechanics or Gödel's theorems; it only verifies that the logical skeleton connecting the stated premises to the conclusion is valid. If the English premises hold, the conclusion cannot be denied without denying one of the premises. That is the inference lock.

## On the role of Lean 4 in this document

Lean 4 appears here only as an uninterpreted object language in Tarski's sense. It is a syntactic register: a place to write down each premise and the conclusion as tokens so the argument's shape is visible. It is not a Lean proof. No derivation is claimed in Lean, and none is needed, because the reasoning is done entirely in the metalanguage (English), which assigns meaning to the object-language tokens. English derives the premises from facts and empirical material and draws the conclusion. Lean records the result. Evaluating the Lean block as a formal proof, or expecting it to derive the conclusion, misreads its role. The proof is the English. The Lean is the notation.

---

## Premise 1

Naturally occurring quantum processes in quantum mechanics itself satisfy the four conditions for an effective method given in the Stanford Encyclopedia of Philosophy entry on the Church-Turing Thesis (section 1.2).

An effective method must meet four conditions:

1. **It is set out in a finite number of exact instructions, each expressed by a finite number of symbols.**

   The physical configurations of a quantum system (an electron's spin pointing up or down, a photon's polarization, an atom sitting at a low energy level or a high energy level, the vacuum) are discrete: each configuration is a separate finite configuration. A system with infinitely many levels is a series of separate finite configurations, not one infinite configuration. Each level is its own finite computation. The series is like 100 people — each person is one person; the series is 100 people, not one person. The predicate applies to each computation; the series is a collection of finite computations.

   The transitions between them are fixed by the physical laws. These configurations and transitions are the instructions. Zero is a finite number, so the vacuum or ground configuration is a finite instruction. Each iteration is one finite computation.

2. **It produces the result in a finite number of steps.**

   A naturally occurring quantum process (superposition of a finite number of physical configurations, unitary evolution of a finite system, creation or annihilation of a particle) takes a finite number of steps. Superposition of zero additional configurations is the zero case; zero is finite. Any finite occupation or finite evolution meets the condition. Unitary evolution of an infinite system is just the repeated application of a finite rule. The rule itself is finite. The computation is the repeated application of that finite rule, even if the number of applications is infinite. Infinite iteration of a finite rule is still an effective method; each step remains finite and mechanical.

   A distribution is a result. When a superposition acts, it produces a result in a state. When vacuum fluctuations act, they produce a result — a distribution. The condition says only that a result is produced; it does not require determinism. A distribution is what the process yields, and that is a result.

3. **It can, in principle, be carried out by a human with paper and pencil.**

   The physical configurations and the transitions between them can be idealized by mathematical symbols and calculated by hand, just as Turing did in his 1936 paper. Turing's tape machine was itself an idealization of physical markings:

   > "The machine is supplied with a 'tape' (the analogue of paper) running through it, and divided into sections (called 'squares') each capable of bearing a 'symbol'. At any moment there is just one square which is 'in the machine'."

   The criteria do not require the human to physically enact the process; they require that the method of obtaining the successive values can be carried out with paper and pencil.

4. **It requires no insight, intuition, or ingenuity.**

   Once the physical laws are given, the process proceeds mechanically. No further insight is required at each step.

These four conditions are met by the naturally occurring quantum processes in quantum mechanics.

### Clarifications on the physical reading of the conditions

**On symbols.** A symbol here is not a mark on paper; it is the physical configuration itself. An amplitude is one physical magnitude — one fact about the system — not a decimal expansion. Asking how many symbols a continuous amplitude contains is asking for the mathematical representation, not the physical fact. Physically, it is one configuration, one symbol.

**On step count.** Each state transition is 0 or 1 steps. A continuous evolution is stated explicitly to count as one step. The predicate says "finite number of steps," and 0 and 1 are finite. It does not require discrete ticks; it requires that the step count be finite.

**On the class claim.** The argument does not enumerate every quantum process. It covers the class by what a quantum process is: a state plus a dynamical rule. This is the same method Turing used: he did not enumerate every computation; he analyzed the structure of computation and generalized. The class claim is that any process that is a quantum process meets the conditions by its structure, not by individual inspection.

Section 1.2 states that the Church-Turing thesis licenses the following replacement: the informal claim "there is an effective method for obtaining the values of function (*f*)" may be replaced by the formal claim "(*f*) is a member of (*S*)" (the set of Turing-computable functions) once the method that obtains those values satisfies the four conditions.

Here the effective method is the naturally occurring quantum process itself. The function (*f*) whose values that method obtains is the mapping from one quantum configuration to the next under the physical transitions. Because the naturally occurring quantum processes are the methods that produce those successive values, the thesis licenses the claim that those functions (*f*) are members of (*S*).

Therefore the naturally occurring quantum processes that meet the conditions are the effective methods that compute the mathematical functions in (*S*). The foundational structure of quantum mechanics is mathematical.

These four conditions are met. Section 1.2 of the SEP entry notes that an effective method is thereby formalized as a mathematical object. Therefore the foundational structure of quantum mechanics is mathematical.

### Substrate dependence

Substrate dependence is true because:

If the difference were only a matter of efficiency, it should still be possible for classical computers to perform the same computations as quantum computers, given enough resources.

But we know that past roughly 300 qubits, a classical simulation would require more atoms and energy than exist in the observable universe. That is a hard resource limit, not a practical inconvenience. Engineering a machine on that scale would also be impossible: the mass and gravity of such a structure would collapse it, and even if one appealed to the unobservable universe, the scale required would still exhaust available resources long before the computation finished.

Therefore different substrates yield different computational capabilities. Quantum mechanics is computational because its substrate produces results that are physically unreachable by any classical substrate under the resource limits of the universe.

### Closed quantum system

The universe is ultimately a closed quantum system for the following reason:

Because quantum mechanics is mathematical, any quantum system is a mathematical system. When two mathematical systems are combined so that they interact, the result is a single combined mathematical system rather than two separate ones. Therefore any collection of quantum systems forms one mathematical system. The universe, as the totality of such systems, is therefore a single closed quantum system.

### Mathematical operations instantiated in reality

The mathematical operations used in quantum computing are instantiated in reality naturally.

Unitary evolution occurs in any closed or isolated quantum system. Because the universe is such a system, it carries out unitary evolution. I will not list every mathematical operation, but I will show that the operations sufficient for Peano arithmetic strength are present.

**The first part of Premise 1 already established that QM is mathematical: the transition functions are Turing-computable, hence mathematical. What follows shows *what* those mathematical functions are — the specific arithmetic operations they instantiate. The Peano mapping is not a re-argument for QM being mathematical; it is an identification of which mathematical functions the dynamics *is*.**

The mapping is:

| Quantum operation | Arithmetic operation |
| --- | --- |
| Creation operator | Successor |
| Annihilation operator | Predecessor |
| Superposition | Addition |
| Tensor products | Multiplication |
| Vacuum state | Zero |
| Unitary evolution | Induction / iteration |

**The mapping is not an interpretation placed on the physics; it is the physics.** This is shown by quantum computation. In a quantum computer, nobody installs an addition operation into the machine. The machine is built; superposition occurs; unitary evolution acts. The addition that the computer performs *is* that natural action of superposition under unitary evolution. The human selects the configuration and reads the result; the arithmetic itself is the mechanical evolution. The mapping from superposition to addition is therefore not an overlay a human projects onto the dynamics — it is the dynamics. It is what the process natively does.

Given P1, reality is the closed system, so unitary evolution and superposition occur natively in reality. Therefore superposition is the addition function inherently in reality, on the same grounds it is the addition function in a quantum computer: because the mechanical evolution is the operation, not a model of it.

These processes occur in the universe because it is an isolated quantum system. Their mechanical behaviour is the same as the corresponding operations in quantum computing, and they occur naturally in reality. They are effective procedures. Therefore these effective methods of quantum mechanics are the mathematics, and they are instantiated in reality because they occur naturally.

Because the four conditions are satisfied by the dynamics of quantum systems, the result holds for the class; no separate enumeration of individual processes is required.

---

## Premise 2

QTM instantiates the primitives of QM and maps them. Because of P1, QM is math, so QTM instantiates that math. Therefore reality itself is a formal system. To deny this you would have to deny P1 or deny that QTM is a formal system.

### The Pure Physical Realization of (A, I, R)

By stripping away any lingering classical "tape/symbol" idealization:

- **Alphabet (A):** The actual, physical basis states of the quantum system (e.g., spin states, polarization states, discrete energy levels). No abstract symbols required — the physical matter/energy configurations are the alphabet, just as the tapes used in QTM are idealising the physical of that quantum object.
- **Initial Strings (I):** The concrete initial state vector of the closed quantum system (the universe).
- **Production Rules (R):** The physical Hamiltonian and resulting unitary evolution operator (`U(t) = e^{-iHt/ℏ}`), which physically drives the state transitions mechanically, natively, and without human intervention.

**Clarification on the alphabet.** The alphabet is the set of physical basis states of the system — spin up/down, polarization states, discrete energy levels. These are physical configurations, not abstract marks. No separate symbol layer is introduced: the physical configuration is the symbol. The initial string is the concrete initial state. The production rules are the Hamiltonian and the unitary evolution operator, which drive transitions mechanically. This is the same reading used in P1: state = symbol, transition = rule.

**Derivability in a Post system is reachability by rewriting.** A state transition is therefore a derivation. The theorems are the reachable states. No separate "proof layer" is needed above the physics: the rewriting *is* the derivation, and no truth-valuation or human interpretation is involved. A string is derivable if the rules can reach it from the initial strings. That is exactly what a quantum transition is: reachability of one physical configuration from another under the dynamical rule.

These primitives occur naturally in the closed quantum system. Because they match Post's definition of a formal system and, by P1, the underlying QM is mathematical (instantiates what it is the effective method of), reality is a formal system.

---

## Premise 3

The universe meets the requirements of Gödel's incompleteness theorems and is therefore a Gödelian system. Both the first and second incompleteness theorems apply to it.

From Premises 1 and 2 the closed quantum system is a formal system that instantiates the mathematical operations sufficient for Peano-arithmetic strength: creation operators function as successor, annihilation operators as predecessor, superposition as addition, tensor products as multiplication, the vacuum state as zero, and unitary evolution as induction/iteration. These are the operations themselves, not the axioms of Peano arithmetic. Peano-arithmetic strength is strictly stronger than both Robinson's Q and Primitive Recursive Arithmetic. Robinson's Q is already sufficient for the first incompleteness theorem, and Primitive Recursive Arithmetic is already sufficient for the second incompleteness theorem, so the strength supplied by these operations is more than enough for both.

Because the system has at least this strength it can represent a provability predicate. The same strength also lets the system prove the Hilbert–Bernays–Löb conditions on that predicate:

- **D1:** If the system proves *A*, then it proves `Prov(⌜A⌝)`.
- **D2:** It proves `Prov(⌜A⌝) → Prov(⌜Prov(⌜A⌝)⌝)`.
- **D3:** It proves `Prov(⌜A → B⌝) → (Prov(⌜A⌝) → Prov(⌜B⌝))`.

Its axioms are recursively enumerable: the physical laws together with an initial state form a recursively enumerable set.

It is consistent. Reality is a mathematical system that uses standard classical mathematics, and therefore it obeys classical logic. In classical logic the principle of explosion holds: if a system proves both a sentence *A* and its negation *¬A*, then it proves every sentence *B*. The short derivation is: from *A* you may prove *A ∨ B*; from *A ∨ B* and *¬A* you may prove *B*. One contradiction therefore makes the system prove everything. Because the system obeys classical logic, this reductio is sound. Standard mathematics does not prove every sentence and does not prove both a theorem and its negation. Therefore no contradiction is present. A sentence and its negation cannot both be true inside the system.

Gödel numbering is already available inside any arithmetic of this strength; Gödel showed that the numbering can be carried out within the arithmetic itself, so no separate construction is required. Gödel also proved that any formal system that is consistent, has recursively enumerable axioms, and contains at least the strength of Robinson's Q is incomplete in the first sense, and that any such system containing at least the strength of Primitive Recursive Arithmetic (and satisfying the conditions above) is incomplete in the second sense.

The universe satisfies every one of those conditions. Reality in fact has more than Peano-arithmetic strength, but only the minimum is required here. It is enough to show that the system reaches the strength of Peano arithmetic through the mathematical operations listed above, because that already places it above the threshold for both G1 (via Robinson's Q) and G2 (via Primitive Recursive Arithmetic and the conditions). Therefore the universe is G1 and G2 incomplete.

---

## Premise 4

The universe is self-referential recursion. Because the system is Gödelian (Premise 3), the diagonal lemma is mathematically part of it. The diagonal lemma produces a sentence that refers to itself by substituting a term for a free variable inside a formula. That substitution function is primitive recursion: it is defined by a finite recursion on the structure of the formula. Primitive recursion is therefore a structural part of the diagonal lemma, and the diagonal lemma is a structural part of any Gödelian system. Reality therefore contains this self-referential recursion by the mathematical structure of Gödel's own results. Denying it would require denying the diagonal lemma or the fact that substitution function is primitive recursion. Reality is self-referential recursion.

The structure of primitive recursion

Recursion theory defines primitive recursion by the scheme

Two clauses define h, and both are required:

1. The base clause, h(x, 0) = f(x), supplies the value at 0. It makes no reference to h. It is given, not generated by the recursion.
2. The recursive clause, h(x, y+1) = g(x, y, h(x, y)), generates later values from earlier ones by applying g to the previous value.

The base clause is both the start and the terminal condition

The recursion descends: y, y−1, …, 0. The base clause is where that descent halts and where the value is fixed. Without a base clause the recursion has no terminal value and defines nothing — it does not halt, so it does not define a function. The base clause is therefore not merely the starting value; it is the halting clause of the recursion. It supplies the value at 0 (the start) and it is the clause at which the descent ends (the termination). Termination is internal to the scheme: primitive recursion is defined so that the syntactic descent on the argument reaches 0, and the base clause fires. That is why primitive recursion always terminates — the base clause is the terminating clause, not an external addition.

The base clause is externally supplied relative to h and g

The recursive clause cannot produce its own starting value. g takes h as an argument; h at 0 cannot be defined by g, because g needs h to already have a value there. f is a parameter the recursion requires but does not generate. The base clause must therefore be supplied from outside the recursion it grounds. This is a structural feature of the scheme itself, not an interpretive overlay: the definition of primitive recursion makes f a supplied parameter.

Applying this to reality

Because the universe's formal system contains primitive recursion — via the operations already shown (creation as successor, etc.) and via the substitution function inside the diagonal lemma — the structure that recursion theory assigns to primitive recursion applies to it. The substitution function is primitive recursive precisely because it recurses on the structure of the formula: a well-founded syntactic descent that reaches the atomic case, where the base clause fires. So reality is the recursion h; its generation is the recursive clause g; and its base clause f is externally supplied relative to h and g. The base clause is the start and the terminal condition of reality's recursion.

Therefore, by the structure of primitive recursion, reality requires an externally supplied base case, which is responsible for starting and ending reality.

---

Final conclusion

The conclusion is that reality is a mathematical, computational, recursive, self-referential formal system that requires an external base case, which is responsible for starting and ending.