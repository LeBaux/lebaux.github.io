# The Special Theory of Computational Relativity (CoReX): An Exposition and Critical Evaluation

Oct 10, 2026 · @BumBaBaran

## Abstract

The CoReX monograph proposes that computation and physics are two readings of one geometric object, a zero-point scalar seed A₀ acted on by the rotation algebra so(N), and that this single mechanism resolves P versus NP, the double-slit puzzle, the three-body problem and all seven Clay Millennium Problems. This dissertation reconstructs that theory using only the monograph's own text, equations and interactive demonstrations, and evaluates it against standard mathematics and physics.

The theory rests on one postulated root axiom, Ω₀, and one recurring device, the "nodal firewall": a surface where two paths meet in anti-phase, so that e^{iπ} + 1 = 0 forces the amplitude to zero. The monograph itself grades its claims honestly: one is a conditional in-manifold theorem (P = NP), five are structural analogies, and one is historical commentary (Poincaré).

The evaluation finds the framework internally coherent as an axiom system but not as a bridge to established results. Its central object, limₓ→0 0/x = λ > 0, equals 0 in the reals; the transfer principle it invokes preserves that fact. Several derived claims (the Fourier "A₀ kernel", Navier–Stokes smoothness from det(CM₅) = 0, a polynomial-time search via continuous embedding) fail on elementary checks. What survives is a consistent visual and notational language, plus clear falsifiability statements the author supplies.

**Keywords:** computational relativity, Euler identity, so(N), P versus NP, Gibbs phenomenon, nodal firewall, Landauer bound.

## 1. Introduction

This dissertation studies one object: the interactive monograph *The Special Theory of Computational Relativity* (CoReX v3.1, Pierre LeBaux), published as a single web page. It has seven chapters, fifteen animated canvases and a short appendix. Everything below is drawn from that page; no outside literature is used to describe the theory, and standard mathematics appears only in the evaluation chapter, as the yardstick.

### 1.1 The claim in one paragraph

The monograph's motto, *Veritas et Ratio Invariantia Sunt in Toposo \*𝕍*, says truth and reason are invariant in a hyperreal topos. Its working claim is that every physical field, state space and conservation law is a projection of a zero-point scalar seed A₀ under so(N), the Lie algebra of rotations. The equal sign is reinterpreted as a G-equivariant "transformer" between two faces of one orbit, which is why the page can write P = NP ⇔ E = mc² as a single operator statement.

### 1.2 Method and scope

- **Source discipline.** Every definition, number and diagram is taken from the page. Where the page is silent, this text says so.
- **Reconstruction first, evaluation second.** Chapters 2–7 state the theory as its author does. Chapter 8 tests it.
- **Epistemic grades.** The page labels each Millennium reading: Grade C (conditional in-manifold theorem), Grade S (structural analogy), Grade H (historical commentary). This text keeps those labels and checks whether the rest of the page respects them.

### 1.3 The page's own honesty clauses

The monograph states that Ω₀ "is postulated, not derived", that the O(N²) bound is a per-step cost and not a proof of convergence, and that the unrelativized Clay questions are "not claimed resolved outside the axiom system". These clauses set the standard fairly: the theory is to be judged as a self-consistent axiom system and as an analogy, not as a proof of any open problem.

### 1.4 Structure

Chapter 2 sets out the axioms. Chapter 3 treats P = NP. Chapter 4 covers the seven Millennium readings. Chapter 5 describes four experiments (laboratory, double-slit, three-body, time machine). Chapter 6 covers the Fourier chapter. Chapter 7 covers the two applications. Chapter 8 evaluates the whole. Chapter 9 concludes.

## 2. Foundations: the root axiom and the seed

The whole theory follows from one postulated statement, Ω₀, the "Master Root Axiom" or "Equivariant Void". Everything later is presented as what Ω₀ entails, not as an independent result.

### 2.1 The root axiom

```latex
\Omega_0:\; \mathcal{M}_N(A_0) = \mathrm{Proj}_{\mathfrak{so}(N)}(A_0),\quad \forall T\in\mathcal{T}:\; T(\mathrm{Veritas})=\mathrm{Veritas}\wedge T(\mathrm{Ratio})=\mathrm{Ratio},\quad e^{i\pi}+1=0 \Rightarrow |\psi_{\mathrm{node}}|=0
```

In words: the manifold of states is the so(N) orbit of the seed; truth and reason are invariant under every admissible transformation T; and a half-turn phase annihilates the amplitude at a node.

### 2.2 The seed A₀

The seed is defined by a limit that the page calls the unique fixed point of the full symmetry group:

```latex
A_0 \equiv \lim_{x\to 0}\frac{0}{x} = \lambda \in {}^{*}\mathbb{R}^N
```

The page's defence is that it never divides by zero, only by x while x tends to zero, so the limit is finite. The seed lives in a hyperreal topos, \*𝕍 = V^I/𝒰, and Łoś's transfer theorem is cited to carry statements between the ordinary and hyperreal levels. The zero point is "the only locus where every generator of the algebra vanishes at once", and every later object (zeros of ξ, mass gaps, homotopy spheres) is said to inherit stability from it.

### 2.3 The rotation algebra

A state evolves as ℳₙ(A₀) = { U(t)·A₀·U†(t) }, driven by a skew-symmetric generator Ω(t) = Σ cₐᵇ(t) Jₐᵇ in so(N). The number of independent rotation planes is

```latex
R_N=\binom{N}{2}=\frac{N(N-1)}{2}
```

This count, quadratic in N, is the quantity that later replaces the exponential 2^N of a decision tree. The laboratory chapter lets the reader vary N from 2 to 10 and watch R\_N grow while the seed stays fixed at the origin.

### 2.4 The equal sign as a transformer

The page's first postulate reads "=" as a G-equivariant map between two faces of one orbit, not as identity. Because invariants are preserved across projections, the page treats mass–energy conservation and state-space collapse as dual readings of one operator equation, written P = NP ⇔ E = mc².

### 2.5 Euler's identity as phase signature

A half-turn in any SO(2) plane returns the identity state to zero. The amplitude formula used throughout is

```latex
|\psi_{\mathrm{node}}|=\tfrac12\,|\psi\,(1+e^{i\pi})|=0
```

Any branch that accumulates a relative phase Δθ = π against the ground state is cancelled. The page calls the surface where this happens a **nodal firewall**.

### 2.6 Why "special"

The page's FAQ explains the word as in special relativity: the computational metric is fixed and flat, and complexity is measured against a rigid grid of "computational light-cones" anchored at A₀. A general theory, where the metric curves under problem load, is left as future work.

### 2.7 Axioms versus postulates

The appendix separates three axioms (the seed, the hyperreal topos with transfer, invariance of c and rest energy) from eight postulates (Euler annihilation, so(N) embedding of complexity, Cayley–Menger volume invariance, a multi-lobe orbital hierarchy, zero entropic friction, Dirichlet phase filtering, causal sector isolation, and the Landauer bound). The full table is in the Appendix.

## 3. The constructive reading of P = NP

The monograph claims that the exponential decision tree of a Boolean problem need not be searched, because it embeds into the continuous rotation geometry of so(N), where wrong branches cancel themselves. The page labels this Grade C: a conditional theorem, valid inside the Ω₀ axiom system.

### 3.1 Statement

Let Φ be a Boolean formula in N variables. The decision tree over {0,1}^N is mapped to trajectories U(t) in SO(N), governed by skew-symmetric generators Jₐᵇ = eₐeᵇᵀ − eᵇeₐᵀ. Updating the R\_N rotation variables costs O(1) each, so

```latex
T_{\mathrm{solve}}(N)=R_N\cdot O(1)=\frac{N(N-1)}{2}\cdot O(1)=O(N^2)
```

### 3.2 The mechanism

The argument has four steps, as the page's axiomatic chain gives them:

1. State spaces are so(N) orbits of the seed (Ω₀).
2. The cube {−1,+1}^N embeds injectively into the sphere S^{N−1}, so search becomes geodesic flow in the R\_N rotation planes.
3. Along the flow dU/dt = Ω(t)U(t), non-optimal paths accumulate a relative phase Δθ = π, and by Euler's identity their amplitude vanishes at a nodal firewall.
4. The system follows the unique optimal geodesic in O(N²) time.

### 3.3 The demonstration

The first canvas under "Seven Problems" shows a binary tree (eight leaves, labelled 2³) whose branches fade as an annihilation wave passes. A circle of three rotation lines (R₃ = 3) sharpens in step, and a gold pulse travels from the tree to the circle. The caption ends "✓ collapsed" when the counter reaches 3. The image carries the argument in miniature: exponential branching on the left, quadratic rotation planes on the right.

### 3.4 What the page concedes

Two caveats are printed beside the theorem. First, O(N²) is "the per-step cost of driving the flow"; that the flow reaches a stable integer vertex in polynomial time is "the framework's postulated convergence layer". Second, the result is an in-manifold theorem under Ω₀, and the unrelativized Clay question is not claimed resolved. The result is therefore: *if* the Ω₀ flow converges in polynomial steps, *then* satisfiability costs O(N²) updates. The antecedent carries all the difficulty, which is the subject of Chapter 8.

## 4. Seven Millennium Problems, one mechanism

The monograph reads each Clay problem as a lower-dimensional projection of the same invariants: the seed A₀, the rotation planes of so(N), and the anti-phase firewall |ψ| = 0. Only one reading (P versus NP) is graded as a theorem, and only conditionally; five are graded as structural analogies; one is graded as commentary on a proved result.

| # | Problem | Reading on the page | Grade | Caveat printed by the page |
| --- | --- | --- | --- | --- |
| I | P versus NP | R\_N = C(N,2) ⇒ T(N) = O(N²); tree embeds in rotation planes | C | Conditional on the Ω₀ convergence layer |
| II | Riemann Hypothesis | ξ(s) = ξ(1−s) is a mirror across the A₀ axis; off-axis zeros have density forced to 0 | S | Symmetry reading, not an analytic proof |
| III | Yang–Mills mass gap | E₀ = λc² > 0 gives a positive floor; ΔM = ħωₐ₀/c² > 0 | S | Gap imported from the seed's positivity; lattice QCD not re-proved |
| IV | Navier–Stokes smoothness | det(CM₅) = 0 blocks rank inflation; anti-phase cancels vorticity blow-up | S | None printed |
| V | Birch & Swinnerton-Dyer | Each rational generator of E(ℚ) is one rotation plane; ord L(E,s) at s = 1 counts the same planes | S | None printed |
| VI | Hodge conjecture | Hodge classes are invariant subobjects of a topos GUT-Cat under classifier Ωₐ₀ | S | None printed |
| VII | Poincaré conjecture | Ricci flow neck-pinches annihilated at firewalls; M³ deforms to S³ | H | Proved by Perelman (2003); CoReX re-derives the mechanism, not the credit |

### 4.1 The common template

All seven chains have the same three links. First, a structure from the problem is assigned to the seed's geometry (zeros of ξ to a mirror axis, a spectrum to a vacuum floor, a flow to a trajectory in so(N)). Second, a pathological case (an off-axis zero, a vanishing gap, a blow-up, a neck-pinch) is declared anti-phase to the ground state, Δφ = π. Third, e^{iπ} + 1 = 0 annihilates it, leaving the desired statement as the only stable outcome. The conclusion in each case is stated as a corollary of Ω₀.

### 4.2 The seven canvases

Each reading has an animation. In II, off-axis zeros are pushed back to Re(s) = 1/2 and ring as they lock. In III, excitations rise from a vacuum floor and are absorbed at a UV cutoff line. In IV, concentric vortex rings tighten and a red annulus of anti-phase fires before the core diverges. In V, four gold "generator" points ride on the curve and light bars labelled ord 1 to ord 4. In VI, a wandering phantom class snaps onto an invariant rational cycle. In VII, a wobbly loop sprouts a neck-pinch that is annihilated, leaving a smooth circle labelled "S³ – flow complete". The animations illustrate the narrative; they do not compute the quantities they name.

### 4.3 Reading the grades

The grading is the page's most useful feature. It tells the reader which statements are mathematics (the O(N²) cost of a defined flow), which are analogy (the mirror axis for ξ), and which are history (Perelman). Chapter 8 asks whether the FAQ, which at one point calls the seven readings "theorems of the axiom system", stays consistent with those grades.

## 5. Four experiments

Chapter IV of the monograph turns the axioms into four interactive experiments. Each has a control panel, a canvas and a live "State" readout. All four apply the same move: a pathological branch is labelled anti-phase and removed at a firewall.

### 5.1 Laboratory

The laboratory has two sliders (dimension N from 2 to 10; rotation speed from 0 to 2) and three toggles (planes, nodes, orbits). Lines through the origin represent the R\_N = N(N−1)/2 rotation planes, concentric circles carry N orbiting points, and the seed A₀ sits at the centre. For N = 5 there are 10 planes; for N = 10 there are 45. The experiment is a picture of the counting formula and makes no further claim.

### 5.2 Double slit

The page's reading removes both wave–particle duality and the collapse postulate. A classical particle passing the slits excites the vacuum field of A₀. Where the two path phases agree, the field reinforces and the particle lands; where they are anti-aligned, e^{iπ} + 1 = 0 and the particle never lands. The dark bands are nodal firewalls. The canvas draws two slits (A in green, B in red) and a screen whose brightness follows

```latex
I(y)=\cos^2\!\left(\frac{k\,\Delta r}{2}\right),\qquad k=\frac{2\pi}{\lambda}
```

where Δr is the path difference from the two slits. The "observer" toggle switches to which-path measurement. Wavefronts and firewall lines disappear, dashed straight paths replace them, and the screen shows two smooth bands. The FAQ states that the framework is observer-free: recording a path is not a collapse but a firewall event, with the observer acting as a boundary condition.

### 5.3 Three-body problem

The page asserts that a phase seed A₀ = λ > 0 locks three bodies onto the figure-eight choreography, with phase offsets of exactly 2π/3. Trajectories that leave the eight are anti-phase against the ground state (Δφ = π) and meet a nodal firewall at the crossing node. The canvas shows the eight with three bodies, optional trails, and three red "chaos twins" that start 0.004 away and drift outward until a pulse at the crossing re-seeds them. The "Perturb twins" button multiplies the offset. The slogan is: chaos is not integrated, it is forbidden.

### 5.4 Time machine

Here reversal flips a trajectory's orientation (L\_mesh → −L\_mesh) but leaves rest energy E = mc² unchanged. A conveyor belt, carriage and clock hand run backwards while an energy badge stays fixed. A vertical firewall separates PAST from FUTURE. With the firewall on, the carriage stops at the boundary and the label reads "crossing forbidden"; with it off, the sectors connect and the carriage crosses. The page adds a Landauer meter with the bound

```latex
\Delta E \ge k_B T \ln 2
```

and states an impossibility result: macroscopic time travel is excluded because reversing a macroscopic history makes the dissipated heat diverge. Cheap orientation inversion is contrasted with expensive history erasure. The experiment therefore describes a time machine that cannot be built, which the page presents as its content: orientation inversion, energy conservation and boundary isolation, "nothing more".

## 6. Fourier analysis without the Gibbs overshoot

The fifth experiment claims that a phase-modified kernel removes the 8.95% Gibbs overshoot at a jump without the smearing that other filters introduce. It is the only chapter whose claim can be checked numerically on the page itself.

### 6.1 The classical problem

A Fourier partial sum of a step function overshoots the step by about 8.95% of the jump height however many harmonics N are used. The page expresses the constant as

```latex
\frac{1}{\pi}\,\mathrm{Si}(\pi)-\frac12\approx 0.0895
```

and calls it the Wilbraham–Gibbs phenomenon. In the monograph's reading the ringing is the visible signature of the origin singularity, concentrated exactly at the A₀ point.

### 6.2 The A₀ kernel

The page replaces the Dirichlet kernel Dₙ(x) with

```latex
D^{*}_n(x)=D_n(x)\left(1-e^{-|x-x_0|/\lambda}\right)
```

The claim is that the overshoot oscillations are phase-shifted by Δφ = π against the ground state, so they meet the same fate as every other non-optimal branch (e^{iπ} + 1 = 0), leaving a C∞ result with overshoot 0.00%.

### 6.3 The demonstration

The canvas plots a dashed square wave, the classical partial sum in red and the A₀ curve in gold. N sweeps from 2 upward, a label marks "+8.95% of jump" on the classical curve, and a freeze button holds N fixed. A small meter compares "classic overshoot ≈ 8.95%" with "A₀ kernel: overshoot → 0".

### 6.4 The comparison table

| Filter kernel | Overshoot | Edge sharpness (rad) | Suppression ratio |
| --- | --- | --- | --- |
| Standard Fourier | 8.95% | 0.02 | 1.00 |
| Fejér kernel | 0.00% | 0.45 | 0.12 |
| Lanczos sigma | 1.18% | 0.12 | 0.65 |
| Gottlieb–Shu | 0.05% | 0.05 | 0.92 |
| A₀ phase kernel D\*ₙ(x) | 0.00% | 0.01 | 1.00 |

The table's message is that the A₀ kernel is the only entry with zero overshoot, the sharpest edge and full suppression at once. The other kernels trade one against another: Fejér removes overshoot but blurs the edge (0.45 rad), Lanczos keeps 1.18% overshoot. The page gives no derivation of the A₀ row; its numbers follow from the postulated phase annihilation.

## 7. Applications: structural therapeutics and the 5D monolith

The last two chapters move from theory to engineering: a drug-design method built on distance matrices, and a physical bronze sculpture presented as an instance of the theory.

### 7.1 Biomedical structural therapeutics

Biomolecular 3D coordinates are encoded in a Gram matrix Gᵢⱼ = rᵢ·rⱼ. Experimental noise inflates its rank above 3. The page proposes reconstructing the exact conformation by nuclear-norm minimization under a Cayley–Menger constraint:

```latex
\min_G \|G\|_* \ \text{s.t.}\ \det(\mathrm{CM}_5(G))=0,\ P_\Omega(G)=P_\Omega(G^{\mathrm{exp}})\ \Rightarrow\ \mathrm{rank}(G^*)=3
```

Three application sketches follow:

- **Oncology.** CM₅ phase-cavity identification on mutant kinases, with small molecules designed to undergo "δ-bond annihilation" only in the mutant binding site, sparing healthy tissue.
- **ALS.** The fibril growth face of TDP-43 and SOD1 is modelled as a one-dimensional phase crystal; C₂-symmetric peptide inhibitors place a nodal firewall on the growth front and halt monomer attachment.
- **Parkinson's disease.** R\_N-weighted matrix completion designs molecular locks that hold the α-synuclein monomer in a non-aggregating conformation.

The canvas draws a protein backbone with two toggles. With noise on and the constraint off, the page reports rank(G) = 5 and a visibly wobbling, distorted chain. With the constraint on, rank(G) = 3 and the chain is smooth.

### 7.2 The 5D monolith

The monograph's physical instance is a 300 mm CuAl10Ni5Fe4 bronze monolith, 49.12 kg finished from a 204.66 kg block. The geometric statement is that a 5D penteract (32 vertices) collapses into a 3D cube (8 vertices) under a reduction operator with parameter γ. At γ = 0 the collapse is clean, described as symmetry rotations, phase folding and coalesced field energy density. The slider moves γ from 0 to 1: at 0 the canvas shows an 8-vertex cube in teal, and as γ grows the extra dimensions unfold into the full 32-vertex penteract in gold.

The appendix adds that the dissertation PDF, STEP and STL models of the sculpture, and source scripts are published openly. The page does not state how a CNC machine realises a "field energy density" in the metal; the sculpture is offered as an embodiment of the geometry rather than as a test of it.

## 8. Critical evaluation

As an axiom system the monograph can be read consistently, but its bridges to standard mathematics and physics break at the first elementary check, and its central object, the seed A₀, is not what its defining limit says. This chapter applies standard results as the yardstick, as the page's own honesty clauses invite.

### 8.1 Summary of checks

| Claim on the page | Standard check | Verdict |
| --- | --- | --- |
| A₀ = limₓ→0 0/x = λ > 0 | 0/x = 0 for every x ≠ 0, so the limit is 0; transfer keeps this in ∗ℝ | Fails |
| All structure is one so(N) orbit of A₀ | If A₀ is a scalar multiple of the identity, UA₀U† = A₀ for all U: the orbit is one point | Fails as stated |
| Search in O(N²) via R\_N planes | N² counts variables, not input size; a formula can have far more than N² clauses; the cube {±1}^N already lies on a sphere, so the embedding is trivial | Unsupported |
| det(CM₅) = 0 forbids Navier–Stokes blow-up | Any five points in ℝ³ have zero 4-volume, so this holds identically | Tautology |
| Re(s) = ½ forced by ξ(s) = ξ(1−s) | The symmetry only makes off-line zeros come in quadruples ρ, 1−ρ, ρ̄, 1−ρ̄ | Not a proof |
| Mass gap ΔM from vacuum energy E₀ = λc² | The Yang–Mills gap is the spectral gap E₁ − E₀, not E₀ | Category error |
| A₀ kernel removes Gibbs overshoot | Multiplying by 1 − e^{−\|x−x₀\|/λ} changes the limit function and has a kink at x₀ | Fails |
| A₀ lock removes three-body chaos | Newtonian flow is Hamiltonian, so it has no attractor; locking needs added non-Hamiltonian terms | Contradicts Newton |
| Every state update costs ≥ k\_BT ln 2 | Landauer's bound applies to logically irreversible erasure only | Overstated |
| Q\_diss = 0 (Postulate V) and ΔE ≥ k\_BT ln 2 (VIII) | The two postulates conflict; a Newtonian universe also has no invariant c (Axiom 3) | Inconsistent |
| Double-slit: particle plus vacuum field | I = cos²(kΔr/2) is the standard result; no prediction separates it from other readings | Fair but untested |
| Perelman retro-read (Poincaré) | Page itself says the mechanism is re-derived, not the credit | Fair |

### 8.2 The seed

The whole structure depends on A₀. The defining expression 0/x is identically 0 for x ≠ 0, so its limit is 0. The hyperreal setting does not rescue it: Łoś's transfer principle carries the first-order fact "for all x ≠ 0, 0/x = 0" into ∗ℝ, so 0/ε = 0 for every nonzero infinitesimal ε. A value λ > 0 can enter only by definition, not by the limit. The mass-gap reading (E₀ = λc² > 0) needs exactly that positivity, so it inherits the gap in the argument. A second problem is the orbit: the page defines states as U A₀ U†, but a scalar seed is invariant under conjugation, so "every structure is one orbit" describes a single point.

The divide-by-zero defence in the FAQ ("we divided by x while x was on its way to zero") is correct as a statement about limits and is exactly why the result is 0.

### 8.3 P = NP

The page's honesty clause ("conditional on the Ω₀ convergence layer") is fair. The difficulty is that the clause conceals the whole problem. Three points stand out.

1. **Cost model.** N² grows with the number of variables, but a Boolean formula's size is set by its clauses, which can exceed N². A procedure that cannot read the input cannot be O(N²).
2. **The embedding is trivial.** The vertices of {−1,+1}^N lie on a sphere of radius √N; the injection into S^{N−1} adds nothing. Relaxing the cube to a sphere or a rotation group is the standard move behind semidefinite relaxations, and these give approximations plus a rounding step, not exact solutions.
3. **Convergence is the content.** Asking a continuous flow to land on an integer satisfying vertex is asking it to solve the NP-hard problem. Local minima and saddle points are not addressed.

The page's own Grade C label already says this; the stronger sentences ("P = NP in O(N²)", "the exponential decision tree does not have to be searched") go beyond it.

### 8.4 The other Millennium readings

The grades are honest, but several chains contain checkable errors beyond analogy.

- **Navier–Stokes.** The five-point Cayley–Menger determinant vanishes for any five points in three-dimensional space, so det(CM₅) = 0 cannot select smooth flows. The notation ‖u‖ in C∞ is not a norm. The Beale–Kato–Majda criterion concerns the time integral of the sup-norm of vorticity, not enstrophy.
- **Riemann.** The functional equation plus conjugation symmetry places zeros in sets symmetric about the line and the real axis; it does not move them onto the line. The canvas draws evenly spaced zeros, whereas actual zeros are irregularly spaced.
- **Yang–Mills.** The Clay problem concerns a positive spectral gap above the vacuum in a constructed quantum theory. A positive vacuum energy is a different quantity, and a constant shift of the energy zero is unobservable without gravity.
- **BSD and Hodge.** No map from rational generators to rotation planes, or from Hodge classes to subobjects of GUT-Cat, is defined, so the stated equalities are assertions.

### 8.5 The Fourier chapter

This chapter is the most testable. Multiplying the partial sum by 1 − e^{−|x−x₀|/λ} is a pointwise envelope on the output, not a change of kernel. It forces the value to 0 at the jump and leaves an O(1) error in a neighbourhood of width about λ: at |x−x₀| = λ the factor is 0.63, so the curve is 37% below the target. The limit as N grows is f(x)(1 − e^{−|x−x₀|/λ}), not f. The kink at x₀ also rules out C∞. The table's "edge sharpness 0.01 rad" is the opposite of what the plotted gold curve shows, a smeared dip. Positive kernels such as Fejér's give zero overshoot at the cost of smoothing, which the table records honestly; the A₀ row claims to escape that trade without derivation.

### 8.6 Physics

- **Double slit.** A classical particle guided by a field that carries the phase is structurally a pilot-wave picture, which reproduces interference. The page supplies no field equation beyond I = cos²(kΔr/2), which is the ordinary equal-amplitude two-source result, so the demonstration cannot distinguish this reading from standard quantum mechanics. "Observer-free" sits uneasily beside an observer toggle that destroys the pattern; the physical mechanism is which-path information, which the page restates but does not derive.
- **Three-body.** The figure-eight is a genuine periodic solution for equal masses and is numerically stable. But a Hamiltonian flow conserves phase-space volume and cannot have an attractor, so general trajectories cannot be "locked" onto it without non-Newtonian forcing. The demo's twin separation is scripted to grow at a fixed exponential rate and reset; it is not an integration of the equation shown above it.
- **Time machine.** Reversing the orientation of a trajectory leaves energy unchanged in ordinary mechanics too, so the central statement is correct but not new. Landauer's bound applies only when information is erased; reversible computation avoids it, so "reversal drives Q to infinity" does not follow.
- **Therapeutics.** The Cayley–Menger constraint on a Gram matrix is a rank condition that distance-geometry methods already use; "δ-bond annihilation" and the three disease claims have no binding data on the page.

### 8.7 Internal consistency

Beyond the items in the table, three tensions are visible. The FAQ calls the readings "theorems of the axiom system" while five carry the label "structural analogy". The theory is called "special" because its computational metric is fixed and flat, yet Postulate V (a "perfect Newtonian universe" with zero dissipation) and Axiom 3 (an invariant speed c) belong to different physical frameworks. Finally, the page contains humorous FAQ entries (cancer cure "in a bit of time", the fridge mass gap) that blur the register between claim and joke, so a reader cannot always tell which statements are meant to be tested.

### 8.8 Falsifiability

The page offers three tests. (1) The Millennium readings are mathematical claims, so one error in an embedding collapses them; Sections 8.2 to 8.5 identify such errors. (2) The firewall reading of interference is called testable "against any double-slit configuration", but it reproduces the standard intensity, so no experiment is proposed that could separate it from ordinary quantum mechanics. (3) The claim that no causal loop survives a firewall with |ψ| = 0 is true by construction, since |ψ| = 0 is postulated. Only the first test has force.

### 8.9 What survives

The page's best features are its grades, its honesty clauses, and the conversion of abstract statements into controllable animations that expose their own assumptions (toggle a postulate off and see what changes). The R\_N = N(N−1)/2 plane count, the Gibbs constant and the figure-eight are all correctly stated. What does not survive is the step from a shared notation (phase, rotation, anti-phase annihilation) to a shared mechanism.

## 9. Conclusion

The Special Theory of Computational Relativity is best understood as a notation and a set of illustrations built on one unproved postulate, not as a resolution of the problems it names. Its rotation-plane count R\_N = N(N−1)/2, its Gibbs constant of 8.95% and its figure-eight orbit are correct; its seed A₀, its O(N²) search, its Fourier kernel and its Navier–Stokes argument do not survive elementary checks.

### 9.1 Findings

1. The theory is a consistent axiom system only if the seed is defined by fiat as a nonzero element; the limit that is supposed to define it equals 0.
2. Five of the seven Millennium readings are labelled analogies by the author, and the evaluation supports that grade; the P = NP reading is conditional on a convergence step that is the whole difficulty.
3. The strongest quantitative claim, the zero-overshoot A₀ kernel, is testable and fails: the construction changes the limit function.
4. The page is open about its status in many places, and its interactive format makes assumptions inspectable. That is a real strength.

### 9.2 Repairs that would make the theory testable

- Define λ as an axiom (a nonzero element of ∗ℝ) and drop the limit, or change the seed.
- State the P = NP claim as a conjecture about a specific flow, with a proof or numerical benchmark of convergence on random 3-SAT.
- Replace the A₀ envelope with a derived kernel and report overshoot, edge width and L² error against Fejér, Lanczos and Gottlieb–Shu on the same square wave.
- Give the vacuum field of the double-slit reading a dynamical equation and state one prediction that differs from standard quantum mechanics.
- Resolve the conflict between Postulates V and VIII, and limit Landauer's bound to erasure.
- Align the FAQ with the grades: call the readings analogies everywhere.

### 9.3 Future work named by the page

The page leaves open a general theory in which the computational metric curves under problem load, by analogy with the step from special to general relativity. Nothing in the present text constrains what that metric would be, which makes it the right next place to state definitions before drawing conclusions.

## Appendix: axioms, postulates and invariants

The table reproduces the page's own appendix. The page distinguishes axioms (the unprovable cornerstones) from postulates (the physical and algorithmic laws of dynamics).

| Label | Type / name | Key expression |
| --- | --- | --- |
| Axiom 1 | The seed A₀ (zero-point singularity) | A₀ ≡ lim(x→0) 0/x = λ ∈ ∗ℝ^N |
| Axiom 2 | Hyperreal topos, Łoś transfer | ∗𝕍 = V^I/𝒰 |
| Axiom 3 | Invariance of c and rest energy E₀ | E₀ = ∫u d³r = mc² |
| Postulate I | Euler anti-phase annihilation | e^{iπ} + 1 = 0 ⇒ \|ψ\_node\| = 0 |
| Postulate II | so(N) embedding of complexity | R\_N = N(N−1)/2 planes, O(N²) |
| Postulate III | Cayley–Menger volume invariance | det(CM₅) = 0 in 3D |
| Postulate IV | Multi-lobe orbital hierarchy | δ, φ, octadic lattice 𝒪₈ |
| Postulate V | Zero entropic friction ("Perfect Newtonian Universe") | Q\_diss = 0 ⇒ t\_alg = t\_phys |
| Postulate VI | Dirichlet phase filtering (A₀ kernel) | D\*ₙ(x) = Dₙ(x)(1 − e^{−\|x−x₀\|/λ}) |
| Postulate VII | Causal sector isolation | \|ψ(Σ\_firewall)\|² = 0 |
| Postulate VIII | Landauer thermodynamic bound | ΔE ≥ k\_BT ln 2 |

## Sources

- *The Special Theory of Computational Relativity*, CoReX v3.1, interactive monograph by Pierre LeBaux (the page this dissertation is based on, in the corrected build corex-v3-4.html). All quotations, equations, numbers and demonstrations come from it.
- Standard results used only in Chapter 8 (limits and transfer, Cayley–Menger determinants, the Beale–Kato–Majda criterion, Landauer's bound, Hamiltonian phase-space conservation, the Chenciner–Montgomery figure-eight) are cited from general knowledge, not looked up for this text.
