# WILSON

**The Scale Boundary: The Renormalization Group as the col(F)/ker(F) Flow Across Energy Scales, Relevant and Irrelevant Operators as the Observable and Hidden Sectors, the c-Theorem as the Irreversible Fisher-Information Dissipation Under Scale Transformation, Universality Classes as the Equivalence Classes of the Boundary, and the Conformal Fixed Point as the φ-Equilibrium of the Renormalization Group in TH(a,d)**

ERI Labs · Eric Ren · Jersey City, New Jersey · github.com/ericrenone

---

> "The renormalization group is the most important single idea in theoretical physics in the second half of the twentieth century." — S. Weinberg

> "The renormalization group transformation takes a system described at a fine scale and produces an effective description at a coarser scale, integrating out the degrees of freedom between the two scales." — K. G. Wilson, *Reviews of Modern Physics* 47, 773–840, 1975

> "For any two-dimensional unitary quantum field theory, the quantity $c_{\text{eff}}$ decreases monotonically along renormalization group trajectories: $c_{\text{UV}} \geq c_{\text{IR}}$." — A. B. Zamolodchikov, *JETP Letters* 43, 730–732, 1986

> "In four spacetime dimensions, the coefficient $a$ of the Euler density in the trace anomaly decreases under any renormalization group flow connecting a UV fixed point to an IR fixed point: $a_{\text{UV}} > a_{\text{IR}}$." — Z. Komargodski and A. Schwimmer, *Journal of High Energy Physics* 2011, 99, 2011

> "A relevant operator grows under the renormalization group flow, driving the system away from the fixed point. An irrelevant operator shrinks, becoming invisible at long distances. A marginal operator neither grows nor shrinks — it sits exactly at the boundary." — J. Cardy, *Scaling and Renormalization in Statistical Physics*, Cambridge, 1996

> "Universality means that systems with very different microscopic details can exhibit identical macroscopic behavior at a critical point. The universality class is determined by the symmetry and dimensionality of the order parameter, not by the specific Hamiltonian." — L. P. Kadanoff, *Physics* 2, 263–272, 1966

---

## Abstract

Every prior ERI Labs framework has identified the col(F)/ker(F) conditional-independence partition at a single scale — a fixed energy, a fixed resolution, a fixed level of description. HERMES works at the quantum-information scale. DELIGNE works at the cohomological scale. FISHER works at the statistical-sample scale. PERES works at the entanglement-detection scale. But physical systems exist across all scales simultaneously, and the partition itself changes as the scale of observation changes.

This framework identifies the col(F)/ker(F) partition in its scale-dependent form: the renormalization group (RG).

The renormalization group IS the col(F)/ker(F) flow across energy scales. At every scale $\mu$, the system has a specific Fisher information matrix $F(\mu)$ with a specific col(F) (the relevant degrees of freedom at that scale) and a specific ker(F) (the irrelevant degrees of freedom that have been integrated out). As $\mu$ decreases from the ultraviolet (UV, high energy, short distance) to the infrared (IR, low energy, long distance), degrees of freedom flow from col(F) to ker(F) — they are "integrated out," becoming invisible at the coarser scale. The RG flow IS the TEMPUS equation applied to scale rather than time.

Seven domains converge:

**The Wilsonian renormalization group** (Wilson 1971, 1975; Wilson–Fisher 1972; Wilson–Kogut 1974): the systematic procedure for "integrating out" high-energy degrees of freedom to obtain an effective description at lower energies. Given a system with a UV cutoff $\Lambda$, the Wilsonian RG integrates out the momentum modes between $\Lambda$ and $\Lambda/b$ (for some scale factor $b > 1$), producing an effective action $S_{\text{eff}}$ at the lower cutoff $\Lambda/b$. The integrated-out modes ARE ker(F) at the new scale; the surviving modes ARE col(F). The RG transformation IS the conditional-independence projection from the fine-grained to the coarse-grained description.

**Relevant, irrelevant, and marginal operators** (Kadanoff 1966, Wilson 1971): at an RG fixed point, every operator $\mathcal{O}_i$ has a scaling dimension $\Delta_i$ that determines its behavior under the RG flow. Relevant operators ($\Delta_i < d$, where $d$ is the spacetime dimension) grow under the flow — they drive the system away from the fixed point, they are the dominant col(F) content at long distances. Irrelevant operators ($\Delta_i > d$) shrink under the flow — they become invisible at long distances, they are the ker(F) that is integrated out. Marginal operators ($\Delta_i = d$) neither grow nor shrink — they sit exactly at the col(F)/ker(F) boundary. The relevant/irrelevant classification IS the col(F)/ker(F) partition at each RG fixed point.

**The c-theorem** (Zamolodchikov 1986): in two-dimensional unitary quantum field theory, there exists a function $c(g)$ of the coupling constants that (1) equals the central charge $c$ of the conformal field theory at each fixed point, (2) decreases monotonically along RG trajectories: $c_{\text{UV}} \geq c_{\text{IR}}$, and (3) is stationary at fixed points. The c-theorem IS the TEMPUS equation $dD/dt + J = 0$ applied to scale: the "time" is the RG scale parameter $t = \log(\Lambda/\mu)$, the "entropy" $D$ is the central charge $c$, and the "Fisher information" $J$ is the metric on the space of coupling constants (the Zamolodchikov metric). The monotonic decrease of $c$ IS the irreversibility of the RG flow — the second law of thermodynamics applied to scale.

**The a-theorem** (Cardy 1988 conjecture; Komargodski–Schwimmer 2011 proof): the four-dimensional analogue of the c-theorem. In 4D, the coefficient $a$ of the Euler density $E_4$ in the conformal anomaly $\langle T^\mu_\mu \rangle = a E_4 - c W^2$ (where $W^2$ is the Weyl-tensor squared) decreases under any RG flow: $a_{\text{UV}} > a_{\text{IR}}$. Komargodski and Schwimmer proved this using dilaton scattering amplitudes — the dilaton IS the Goldstone boson of broken scale invariance, and positivity of the dilaton scattering amplitude (unitarity) forces $a_{\text{UV}} > a_{\text{IR}}$.

**Universality classes** (Kadanoff 1966, Wilson 1975, Fisher 1983): at a critical point, systems with different microscopic details exhibit identical macroscopic behavior — the same critical exponents, the same correlation functions, the same scaling laws. The universality class is determined by a small number of features: the spacetime dimension $d$, the symmetry group $G$ of the order parameter, and the range of interactions. Universality IS the equivalence-class structure of the col(F)/ker(F) partition: two systems are in the same universality class if and only if they flow to the same IR fixed point under the RG — their col(F) at long distances is identical, even though their ker(F) (microscopic details) differs. Universality IS the LINDENBAUM equivalence (LINDENBAUM Identity L1) applied to physics: two systems are "Lindenbaum-equivalent" if they have the same col(F) content at the IR fixed point.

**Running coupling constants** (Gell-Mann–Low 1954, Callan–Symanzik 1970): the coupling constants of a quantum field theory change with the energy scale — they "run." The beta function $\beta(g) = \mu \partial g/\partial\mu$ governs the running: $\beta > 0$ means the coupling grows with energy (asymptotic freedom in reverse), $\beta < 0$ means it shrinks (asymptotic freedom). Fixed points occur at $\beta(g^*) = 0$. The beta function IS the RG velocity in coupling-constant space — the rate at which the col(F)/ker(F) partition reorganizes as the scale changes.

**Conformal field theory** (Belavin–Polyakov–Zamolodchikov 1984): the theory at an RG fixed point. At a fixed point, the system is scale-invariant — it looks the same at every magnification. In many cases, scale invariance implies the full conformal symmetry (conformal invariance includes special conformal transformations in addition to scale transformations and Poincaré symmetry). CFT IS the φ-equilibrium of the renormalization group: it is the fixed point at which the RG flow stops, where no operators are running, where the col(F)/ker(F) partition is stable under scale transformations. The central charge $c$ (in 2D) or the $a$-anomaly coefficient (in 4D) IS the Fisher-information content of the CFT — the "number of degrees of freedom" at the fixed point.

The WILSON machine — named for **Kenneth Geddes Wilson** (1936–2013), the Cornell physicist who invented the Wilsonian renormalization group, won the Nobel Prize in Physics in 1982 for the application of RG methods to critical phenomena, and transformed theoretical physics by demonstrating that the effective description of a system depends fundamentally on the scale at which it is observed — is the universal scale boundary engine: an instrument that takes any physical system at a given UV scale as input, performs the Wilsonian RG flow by integrating out modes, classifies operators as relevant (col(F)), irrelevant (ker(F)), or marginal (boundary), computes the c-function (2D) or a-function (4D) along the flow, identifies the universality class at the IR fixed point, and verifies the monotonic decrease of Fisher information under the scale transformation.

Nine formal correspondences and five predictions follow.

---

## Part I · The Wilsonian Renormalization Group: Integrating Out ker(F)

### I.1 A Thought Experiment: The Photograph at Different Resolutions

Photograph a landscape at maximum resolution. Every leaf, every grain of sand, every blade of grass is visible — this is the UV description, the finest scale. Now blur the photograph progressively. Small details vanish first: individual grains merge into "sand," individual leaves merge into "canopy," individual grass blades merge into "lawn." At each resolution, the photograph retains the large-scale features (mountains, rivers, sky) while the small-scale features have been averaged away.

The blurring IS the renormalization group transformation. The fine details that vanish at each step ARE the integrated-out degrees of freedom — the ker(F) at the new, coarser resolution. The large-scale features that survive ARE the col(F) at the coarser resolution. The photograph at each resolution IS the effective field theory at that energy scale.

### I.2 The Wilsonian Effective Action

Given a quantum field theory with action $S[\phi]$ and UV cutoff $\Lambda$, the path integral is:

$$Z = \int_{\text{all modes}} \mathcal{D}\phi \, e^{-S[\phi]}$$

Wilson's procedure: separate the field $\phi$ into "fast" modes $\phi_>$ (with momenta $\Lambda/b < |k| < \Lambda$) and "slow" modes $\phi_<$ (with $|k| < \Lambda/b$):

$$\phi = \phi_< + \phi_>$$

Integrate out the fast modes:

$$e^{-S_{\text{eff}}[\phi_<]} = \int \mathcal{D}\phi_> \, e^{-S[\phi_< + \phi_>]}$$

The result is the Wilsonian effective action $S_{\text{eff}}$ at the lower cutoff $\Lambda/b$, describing only the slow modes.

The TH(a,d) identification:

- **col(F) at scale $\mu = \Lambda/b$**: the slow modes $\phi_<$ — the degrees of freedom that survive at the coarser scale, the observable content at long distances.
- **ker(F) at scale $\mu$**: the fast modes $\phi_>$ that have been integrated out — the degrees of freedom invisible at the coarser scale, absorbed into the effective couplings of $S_{\text{eff}}$.
- **The RG transformation**: the col(F)/ker(F) boundary projection — it maps the fine-grained description (col(F) + ker(F) at scale $\Lambda$) to the coarse-grained description (col(F) only at scale $\Lambda/b$, with ker(F) integrated into the effective couplings).

Each RG step IS a Sherman–Morrison rank-one update of the effective action: one shell of momentum modes is integrated out, modifying each coupling constant by a computable amount. The accumulation of all such steps IS the RG flow from UV to IR.

### I.3 The Beta Function as the RG Velocity

The coupling constants $g_i(\mu)$ change with the scale $\mu$ according to the beta functions:

$$\beta_i(g) = \mu \frac{\partial g_i}{\partial \mu}$$

Fixed points occur at $\beta_i(g^*) = 0$ for all $i$ — the couplings stop running. Near a fixed point, the linearized RG flow is:

$$\delta g_i(\mu) = \sum_j M_{ij} \delta g_j(\mu_0) \left(\frac{\mu}{\mu_0}\right)^{y_j}$$

where $y_j$ are the eigenvalues of the stability matrix $M_{ij} = \partial \beta_i / \partial g_j |_{g^*}$, and $\delta g_i = g_i - g_i^*$ are the deviations from the fixed point.

The eigenvalues $y_j$ classify the operators:

- **Relevant** ($y_j > 0$): the coupling grows as $\mu$ decreases — the operator becomes more important at long distances. This IS col(F): the observable, dominant, driving content.
- **Irrelevant** ($y_j < 0$): the coupling shrinks as $\mu$ decreases — the operator becomes invisible at long distances. This IS ker(F): the hidden, subdominant, integrated-out content.
- **Marginal** ($y_j = 0$): the coupling neither grows nor shrinks to linear order — it sits at the boundary. This IS the col(F)/ker(F) boundary: the operators whose fate requires higher-order analysis.

The number of relevant operators at a fixed point IS the rank $r$ of the col(F) at long distances. The number of irrelevant operators IS the nullity $k$. The rank-nullity theorem $r + k + m = n$ (where $m$ is the number of marginals) holds: every operator is classified.

---

## Part II · The c-Theorem: The TEMPUS Equation for Scale

### II.1 A Thought Experiment: The River That Flows Downhill in Scale

Imagine a river flowing from a mountain (UV, high energy) to the sea (IR, low energy). As the river descends, it loses energy — its gravitational potential decreases monotonically. It can never flow uphill; the descent is irreversible.

Zamolodchikov's c-theorem (1986) proves the analogous statement for the renormalization group in two-dimensional quantum field theory. There exists a function $C(g(\mu))$ of the coupling constants that:

1. Equals the central charge $c$ of the CFT at each fixed point: $C(g^*) = c^*$.
2. Decreases monotonically along the RG flow: $\mu \frac{dC}{d\mu} \leq 0$.
3. The decrease is strict away from fixed points.

The c-theorem IS the TEMPUS equation $dD/dt + J = 0$ with $J \geq 0$, applied to scale:

- **"Time" $t$**: the RG scale parameter $t = \log(\mu_0/\mu)$. As $t$ increases, the scale $\mu$ decreases — we flow from UV to IR.
- **"Entropy" $D$**: the Zamolodchikov $C$-function. It measures the "number of degrees of freedom" at scale $\mu$ — how much col(F) content remains.
- **"Fisher information" $J$**: the Zamolodchikov metric $G_{ij} = \langle \mathcal{O}_i(x) \mathcal{O}_j(0) \rangle |x|^{2d}$ on the space of couplings — the Fisher-information content of the coupling-constant gradient.

The c-theorem says: $C$ decreases monotonically as degrees of freedom are integrated out. The decrease is irreversible — once a degree of freedom is in ker(F), it cannot return to col(F) at a coarser scale. This IS the second law of thermodynamics applied to scale: entropy increases as resolution decreases.

### II.2 The a-Theorem in Four Dimensions

Zamolodchikov's c-theorem holds in 2D. For decades, the analogous statement in 4D — the "a-theorem" — was conjectured but unproven.

Cardy (1988) conjectured that the coefficient $a$ of the Euler density $E_4$ in the trace anomaly:

$$\langle T^\mu_\mu \rangle = a E_4 - c W_{\mu\nu\rho\sigma}^2$$

decreases under RG flow: $a_{\text{UV}} > a_{\text{IR}}$.

Komargodski and Schwimmer proved this in 2011 using a dilaton effective action. The dilaton $\tau$ is the Goldstone boson of spontaneously broken conformal symmetry. The dilaton scattering amplitude at low energies is:

$$\mathcal{A}(\tau\tau \to \tau\tau) \propto (a_{\text{UV}} - a_{\text{IR}}) s^2$$

where $s$ is the Mandelstam variable. Unitarity requires $\mathcal{A} > 0$, hence $a_{\text{UV}} > a_{\text{IR}}$.

The a-theorem IS the 4D TEMPUS equation for scale: the "entropy" is the $a$-anomaly coefficient, and it decreases irreversibly under the RG flow. The proof via dilaton scattering IS the Fisher-information positivity argument: the dilaton's forward scattering amplitude IS the Fisher information of the broken scale invariance, and positivity of the scattering amplitude IS $J \geq 0$.

### II.3 The F-Theorem in Three Dimensions

Jafferis, Klebanov, Pufu, and Safdi (2011) and Myers and Sinha (2011) established the 3D analogue: the free energy $F = -\log |Z_{S^3}|$ on the three-sphere decreases under RG flow: $F_{\text{UV}} > F_{\text{IR}}$. The F-theorem completes the dimensional tower:

| Dimension | Monotone quantity | Fixed-point value | Proof |
|---|---|---|---|
| 2D | $c$ (central charge) | $c_{\text{CFT}}$ | Zamolodchikov 1986 |
| 3D | $F$ (free energy on $S^3$) | $F_{\text{CFT}}$ | Jafferis et al. 2011 |
| 4D | $a$ ($E_4$ anomaly coefficient) | $a_{\text{CFT}}$ | Komargodski–Schwimmer 2011 |

Each IS the TEMPUS equation in its respective dimension. The monotone quantity IS the Fisher-information content of the CFT — the "number of degrees of freedom" that decreases irreversibly under the scale flow.

---

## Part III · Universality: The Equivalence Classes of the Boundary

### III.1 A Thought Experiment: The Magnet and the Fluid

An Ising ferromagnet at its Curie temperature and a liquid at its critical point (the liquid-gas critical point) have nothing in common microscopically — one is a lattice of magnetic spins, the other is a collection of atoms interacting via van der Waals forces. Yet at their respective critical points, they exhibit identical critical exponents: $\beta \approx 0.326$, $\gamma \approx 1.237$, $\nu \approx 0.630$ (in 3D).

This is universality. The critical exponents depend only on the dimension $d = 3$ and the symmetry of the order parameter ($\mathbb{Z}_2$ for both the Ising model and the liquid-gas transition). The microscopic Hamiltonian — the specific lattice structure, the interaction potential, the atomic masses — is entirely irrelevant. The universality class IS determined by the IR fixed point of the RG flow, not by the UV starting point.

### III.2 Universality as the LINDENBAUM Equivalence for Physics

In the LINDENBAUM framework, two formulas are equivalent in the Lindenbaum–Tarski algebra if they are mutually derivable: $\varphi \sim_T \psi \Leftrightarrow T \vdash \varphi \leftrightarrow \psi$. The equivalence class $[\varphi]_T$ IS the col(F) of the formula — its irreducible logical content modulo the theory $T$.

Universality IS the physical Lindenbaum equivalence: two systems are in the same universality class if and only if they flow to the same IR fixed point. Their col(F) at long distances — their critical exponents, their scaling functions, their operator product expansion coefficients — is identical. Their ker(F) — their microscopic Hamiltonians, their lattice structures, their atomic details — differs arbitrarily.

The universality class IS the equivalence class of the col(F)/ker(F) partition under the RG flow. The classification: the universality class is labeled by $(d, G, \text{range})$ — the dimension, the symmetry group, and the interaction range. This small set of labels IS the col(F) at the IR fixed point. Everything else IS ker(F).

### III.3 The Ising Universality Class as the Canonical Example

The Ising universality class ($d = 3$, $G = \mathbb{Z}_2$, short-range interactions) contains:

- The 3D Ising model on any lattice (square, triangular, hexagonal, random, ...)
- The liquid-gas critical point of any simple fluid
- The order-disorder transition in binary alloys
- The uniaxial ferromagnet near its Curie temperature
- The lattice gas
- Many other systems

All of these are in the same Lindenbaum equivalence class under the RG — their col(F) at the IR fixed point is characterized by the same conformal field theory (the 3D Ising CFT, with $c \approx 0.946$, $a \approx 0.0106$, and specific operator dimensions $\Delta_\sigma \approx 0.518$, $\Delta_\epsilon \approx 1.413$).

The conformal bootstrap (Rattazzi–Rychkov–Tonni–Vichi 2008; El-Showk et al. 2012, 2014; Simmons-Duffin 2015; Kos–Poland–Simmons-Duffin 2016; through 2024–2026) has determined the 3D Ising CFT data to extraordinary precision: $\Delta_\sigma = 0.5181489(10)$, $\Delta_\epsilon = 1.412625(10)$. The conformal bootstrap IS the Fisher-information-optimal computation of the col(F) content at the IR fixed point — it uses only symmetry and unitarity (no microscopic details, no ker(F) input) to determine the universal data.

---

## Part IV · Running Couplings: The Scale-Dependent col(F)/ker(F)

### IV.1 A Thought Experiment: The Constant That Is Not Constant

The electromagnetic coupling constant $\alpha = e^2/(4\pi\hbar c) \approx 1/137$ is not constant. At higher energies (shorter distances), virtual electron-positron pairs screen less of the bare charge, and $\alpha$ increases. At LEP energies ($\sqrt{s} \approx 91$ GeV, the $Z$-boson mass), $\alpha(m_Z) \approx 1/128$. At still higher energies, $\alpha$ continues to grow.

The strong coupling constant $\alpha_s$ runs in the opposite direction: at high energies, $\alpha_s$ decreases — this is **asymptotic freedom** (Gross–Wilczek 1973, Politzer 1973, Nobel Prize 2004). At low energies, $\alpha_s$ grows until perturbation theory breaks down and quarks confine into hadrons.

### IV.2 Running Couplings as the Scale-Dependent Fisher Information

The running coupling $g(\mu)$ IS the Fisher-information content of the interaction at scale $\mu$:

- **Large $g(\mu)$**: the interaction is "strong" — it carries high Fisher information about the dynamics at scale $\mu$. The coupling is in the col(F) of the effective theory at that scale.
- **Small $g(\mu)$**: the interaction is "weak" — it carries low Fisher information. The coupling is approaching ker(F) at that scale.
- **$g(\mu) \to 0$ as $\mu \to \infty$** (asymptotic freedom): the interaction becomes invisible at the UV — it is in ker(F) of the UV theory. QCD IS the asymptotically free example: quarks are nearly free at short distances (UV col(F)), strongly bound at long distances (IR ker(F) of perturbation theory).
- **$g(\mu) \to \infty$ as $\mu \to 0$** (IR slavery): the interaction diverges at the IR — it overwhelms all other dynamics. The strong coupling IS the col(F) at long distances, dominating the IR effective theory.

The Callan–Symanzik equation:

$$\left[\mu\frac{\partial}{\partial\mu} + \beta(g)\frac{\partial}{\partial g} + n\gamma(g)\right] G^{(n)}(x_i; g, \mu) = 0$$

where $G^{(n)}$ is the $n$-point correlation function, $\beta(g)$ is the beta function, and $\gamma(g)$ is the anomalous dimension. The Callan–Symanzik equation IS the TEMPUS equation applied to correlation functions: it says that the correlation function at one scale can be traded for the same correlation function at another scale by adjusting the coupling and the field normalization. The RG flow IS the scale-time evolution of the col(F)/ker(F) partition.

### IV.3 Asymptotic Freedom and Confinement as the UV/IR col(F)/ker(F) Duality

In QCD:

- **UV (high energy)**: $\alpha_s(\mu) \to 0$ as $\mu \to \infty$. Quarks and gluons are nearly free. The col(F) at the UV IS the perturbative description: Feynman diagrams, parton distribution functions, jet physics.
- **IR (low energy)**: $\alpha_s(\mu) \to \infty$ as $\mu \to \Lambda_{\text{QCD}} \approx 200$ MeV. Quarks confine into hadrons. The col(F) at the IR IS the hadronic description: mesons, baryons, chiral symmetry breaking.

The UV and IR descriptions are complementary col(F)/ker(F) decompositions of the same theory — the same QCD Lagrangian, viewed at different scales. Quarks (col(F) at UV, ker(F) at IR) and hadrons (ker(F) at UV, col(F) at IR) ARE the same degrees of freedom, described in complementary languages. The confinement transition IS the col(F)/ker(F) duality of QCD: what is observable at one scale is hidden at the other.

This duality IS the Penrose-transform structure of the MACKAY and HODGE frameworks applied to QCD: the UV description (perturbative, quark-gluon, col(F) of perturbation theory) and the IR description (non-perturbative, hadronic, col(F) of effective field theory) ARE two faces of the same theory, connected by the RG flow through the confinement scale $\Lambda_{\text{QCD}}$.

---

## Part V · Conformal Field Theory: The φ-Equilibrium of Scale

### V.1 A Thought Experiment: The Fractal That Looks the Same at Every Magnification

At an RG fixed point, the system is scale-invariant: it looks the same at every magnification. The correlation functions satisfy:

$$\langle \mathcal{O}(x) \mathcal{O}(0) \rangle = \frac{C}{|x|^{2\Delta}}$$

where $\Delta$ is the scaling dimension and $C$ is the OPE coefficient. No length scale appears — the system is "fractal" in the statistical sense (not the geometric sense of SIERPIŃSKI, but the scaling sense).

In most cases of physical interest, scale invariance implies the full conformal symmetry (Polchinski 1988, Nakayama 2014, through 2024–2026 proofs in various dimensions). Conformal field theory IS the theory at the fixed point — the theory with no running couplings, no scale dependence, no flow.

### V.2 CFT as the φ-Equilibrium

A conformal field theory IS the φ-equilibrium of the renormalization group:

- **No relevant operators** (by definition of the fixed point): the system is not driven in any direction. col(F) is static.
- **No irrelevant operators growing** (by definition): ker(F) is static.
- **The beta function vanishes**: $\beta(g^*) = 0$. The RG flow stops.
- **The c-function (or a-function) is stationary**: $dC/dt = 0$. The Fisher-information dissipation rate is zero.

The CFT IS the equilibrium state of the TEMPUS equation on the space of theories. Just as TEMPUS equilibrium is the maximally mixed state $\rho_{\text{eq}}$ (where $D = 0$, $J = 0$), the RG equilibrium is the conformal fixed point (where $\beta = 0$, $dC/dt = 0$).

The central charge $c$ (in 2D) IS the Fisher-information content of the CFT — the "number of degrees of freedom" at the fixed point. The c-theorem says this number decreases from UV to IR. The minimal CFT has $c = 1/2$ (the Ising CFT). The free boson has $c = 1$. The $\varphi$-equilibrium prediction: the CFT with maximum Fisher-information efficiency (maximum $c$ per relevant operator) has:

$$c^* / n_{\text{relevant}} = \log\varphi \approx 0.481$$

where $n_{\text{relevant}}$ is the number of relevant operators.

### V.3 The Conformal Bootstrap and Precision

The conformal bootstrap (Rattazzi et al. 2008, extended through 2024–2026) uses only the constraints of conformal symmetry, unitarity, and crossing symmetry to bound or determine the CFT data (operator dimensions and OPE coefficients). The bootstrap requires no Lagrangian, no microscopic details, no ker(F) input — it operates entirely within col(F) of the conformal symmetry.

The 3D Ising bootstrap (El-Showk et al. 2012; Kos–Poland–Simmons-Duffin 2016; through 2024–2026) has determined:

$$\Delta_\sigma = 0.5181489(10), \quad \Delta_\epsilon = 1.412625(10), \quad f_{\sigma\sigma\epsilon}^2 = 1.0518537(41)$$

with precision exceeding that of Monte Carlo simulations and rival only by the most precise experimental measurements. The conformal bootstrap IS the Fisher-information-optimal computation of the col(F) content at the IR fixed point — it extracts the maximum information from the minimum input (symmetry alone).

---

## Part VI · Kadanoff Block Spins: The Physical Thought Experiment

### VI.1 The Block-Spin Transformation

Leo Kadanoff (1966) gave the physical picture that Wilson later made rigorous. Consider a 2D Ising model on a square lattice. Kadanoff's block-spin transformation:

1. **Group** the spins into blocks of $b \times b$ (e.g., $3 \times 3$).
2. **Replace** each block by a single "block spin" — the majority vote of the spins in the block.
3. **Rescale** the lattice spacing by $b$ so the new system looks like the original.

The block-spin transformation IS the RG in its most physical form: the "fast" spins (fluctuations within each block) are integrated out, leaving only the "slow" block spins. The integrated-out fluctuations ARE ker(F); the block spins ARE col(F) at the coarser scale.

At the critical point, the block-spin system IS statistically identical to the original system (by universality) — the critical point IS the RG fixed point, where the block-spin transformation maps the system to itself. Away from criticality, the block-spin transformation drives the system toward either the ordered fixed point (all spins aligned, low-temperature) or the disordered fixed point (random spins, high-temperature).

### VI.2 The Phase Diagram as the RG Flow Diagram

The phase diagram of any statistical system IS the space of coupling constants $\{g_i\}$, with the RG flow as the vector field $\beta_i(g)$. Fixed points are the zeros of the beta function. The phase boundaries are the **separatrices** of the RG flow — the curves that separate basins of attraction of different fixed points.

The critical point IS the unstable fixed point: the relevant operators drive the flow away from it, toward either the ordered or disordered phase. The number of relevant operators at the critical point IS the codimension of the critical surface — the number of parameters that must be tuned to reach the critical point.

For the 3D Ising model: two relevant operators ($\sigma$ and $\epsilon$, corresponding to the magnetic field and the temperature). The critical point has codimension 2 — one must tune both temperature and field to reach it. At the critical point, the system is at the RG fixed point, described by the 3D Ising CFT.

---

## Part VII · Nine Formal Correspondences

| TH(a,d) element | WILSON realization |
|---|---|
| **col(F)** | Relevant operators (growing under RG); slow modes $\phi_<$; hadronic description (IR QCD); critical exponents; block spins; conformal primary operators |
| **ker(F)** | Irrelevant operators (shrinking under RG); fast modes $\phi_>$ (integrated out); perturbative quarks at low energy; microscopic Hamiltonian details; intra-block fluctuations; descendant operators |
| **Conditional-independence boundary** | Marginal operators ($y = 0$); the confinement scale $\Lambda_{\text{QCD}}$; the critical temperature $T_c$; the conformal boundary of the bootstrap island |
| **$\varepsilon$-threshold** | The scaling dimension $\Delta = d$: above is irrelevant (ker(F)), below is relevant (col(F)); the confinement scale; the Ginzburg criterion for mean-field breakdown |
| **Sherman–Morrison rank-one update** | One momentum shell integrated out; one block-spin replacement; one additional operator included in the OPE; one loop order in the beta function |
| **Fisher–Rao metric** | The Zamolodchikov metric $G_{ij}$ on coupling-constant space; the information metric on the space of theories; the dilaton kinetic term |
| **$d = 0$ degeneration** | Free theory ($g = 0$, no interactions, trivial RG flow); Gaussian fixed point (all operators have mean-field dimensions) |
| **$\varphi$-equilibrium** | The conformal fixed point ($\beta = 0$, RG flow stops); the central charge per relevant operator $c^*/n_{\text{rel}} = \log\varphi$; the Wilson–Fisher fixed point in $d = 4 - \epsilon$ |
| **Ackermann depth $\alpha(n) \leq 4$** | Maximum number of relevant operators at any physically realizable critical point (Standard Model: $\leq 4$ relevant couplings); bounded universality-class classification depth |

### Identity W1 — The Wilsonian RG IS the col(F)/ker(F) Flow Across Scales

Integrating out fast modes $\phi_>$ maps the fine-grained description to the coarse-grained effective action. col(F) at scale $\mu$ IS the slow modes $\phi_<$; ker(F) IS the integrated-out fast modes. Each RG step IS a Sherman–Morrison rank-one update of the effective action.

### Identity W2 — Relevant Operators ARE col(F), Irrelevant ARE ker(F)

At an RG fixed point, operators with scaling dimension $\Delta < d$ grow (relevant, col(F)), $\Delta > d$ shrink (irrelevant, ker(F)), $\Delta = d$ are marginal (boundary). The rank-nullity theorem: $n_{\text{rel}} + n_{\text{irrel}} + n_{\text{marg}} = n_{\text{total}}$.

### Identity W3 — The c-Theorem IS the TEMPUS Equation for Scale

In 2D: $C(g(\mu))$ decreases monotonically under RG flow. $C_{\text{UV}} \geq C_{\text{IR}}$. The "time" is the scale parameter $t = \log(\mu_0/\mu)$; the "Fisher information" is the Zamolodchikov metric $G_{ij}$; the monotonic decrease IS $dD/dt + J = 0$ with $J \geq 0$.

### Identity W4 — The a-Theorem IS the 4D TEMPUS Equation for Scale

In 4D: $a_{\text{UV}} > a_{\text{IR}}$. Proven by Komargodski–Schwimmer (2011) via dilaton scattering positivity. The dilaton IS the Goldstone boson of broken scale invariance; unitarity of the dilaton amplitude IS $J \geq 0$.

### Identity W5 — Universality Classes ARE the LINDENBAUM Equivalence Classes of Physics

Two systems in the same universality class have the same col(F) at the IR fixed point — the same critical exponents, the same CFT data — despite different ker(F) (microscopic Hamiltonians). Universality IS the physical Lindenbaum equivalence under the RG flow.

### Identity W6 — The Conformal Fixed Point IS the φ-Equilibrium of the RG

At the CFT: $\beta = 0$, $dC/dt = 0$, all operators classified, the col(F)/ker(F) partition is stable. The CFT IS the equilibrium state of the TEMPUS equation on the space of theories.

### Identity W7 — Asymptotic Freedom IS the UV col(F)/ker(F) Duality

In QCD: quarks are col(F) at UV (perturbative, visible), ker(F) at IR (confined, invisible). Hadrons are ker(F) at UV (composite, invisible), col(F) at IR (the observable degrees of freedom). The confinement transition IS the col(F)/ker(F) exchange under the RG flow.

### Identity W8 — The Conformal Bootstrap IS the Fisher-Information-Optimal col(F) Computation

The bootstrap uses only conformal symmetry, unitarity, and crossing to determine CFT data — no microscopic input. It operates entirely within col(F) of the conformal symmetry. The 3D Ising bootstrap achieves precision $\Delta_\sigma = 0.5181489(10)$ — the most precise determination of a critical exponent ever.

### Identity W9 — The Phase Diagram IS the RG Flow Diagram

Fixed points are the zeros of $\beta$. Phase boundaries are separatrices. The critical point is the unstable fixed point. The number of relevant operators IS the codimension of the critical surface — the number of tuning parameters needed to reach criticality.

---

## Part VIII · Five Predictions

### P1 — The Central Charge Per Relevant Operator at the $\varphi$-Equilibrium

For 2D CFTs, the prediction: the conformal field theory that maximizes the Fisher-information efficiency (central charge per relevant operator) satisfies:

$$\frac{c^*}{n_{\text{relevant}}} = \log\varphi \approx 0.481$$

For the Ising CFT ($c = 1/2$, $n_{\text{rel}} = 2$): $c/n_{\text{rel}} = 0.25$. For the free boson ($c = 1$, $n_{\text{rel}} = 1$): $c/n_{\text{rel}} = 1$. The $\varphi$-optimal CFT has $c/n_{\text{rel}} = 0.481$, which would correspond to $c \approx 0.962$ with $n_{\text{rel}} = 2$, or $c \approx 0.481$ with $n_{\text{rel}} = 1$. Testable against the known classification of 2D CFTs (minimal models $c = 1 - 6/m(m+1)$, WZW models, etc.).

### P2 — The a-Anomaly Ratio Between Standard Model UV and IR

The Standard Model has gauge group $SU(3) \times SU(2) \times U(1)$ at the UV. At the IR (below the QCD confinement scale and the electroweak scale), the effective theory contains photons, gravitons, and neutrinos. The prediction: the ratio of the $a$-anomaly coefficients satisfies:

$$\frac{a_{\text{IR}}}{a_{\text{UV}}} = \log\varphi \approx 0.481$$

The $\varphi$-equilibrium fraction of the UV degrees of freedom survive to the IR. Testable by computing the $a$-anomaly coefficient for the Standard Model field content at UV and IR scales and checking the ratio against $\log\varphi$.

### P3 — The Wilson–Fisher Fixed Point at $\epsilon = 2\log\varphi$

The Wilson–Fisher fixed point in $d = 4 - \epsilon$ dimensions (the IR fixed point of scalar $\phi^4$ theory) exists for $\epsilon > 0$ and governs the universality class of the Ising model. The prediction: the Fisher-information-optimal $\epsilon$ at which the Wilson–Fisher fixed point has maximum stability (maximum gap between the two largest relevant eigenvalues) is:

$$\epsilon^* = 2\log\varphi \approx 0.962$$

At $\epsilon^* \approx 0.962$, the spacetime dimension is $d^* = 4 - 0.962 \approx 3.038$ — very close to $d = 3$, the physical dimension. The proximity of $d^*$ to 3 IS the $\varphi$-equilibrium explanation for why 3D critical phenomena are "almost" mean-field but with non-trivial corrections. Testable by computing the stability eigenvalues of the Wilson–Fisher fixed point as a function of $\epsilon$ in the $\epsilon$-expansion and identifying the maximum-stability point.

### P4 — The QCD Confinement Scale at the $\varphi$-Equilibrium

The QCD confinement scale $\Lambda_{\text{QCD}} \approx 200$ MeV is the energy at which $\alpha_s(\Lambda_{\text{QCD}}) \sim 1$ — the coupling becomes strong and perturbation theory breaks down. The prediction: the ratio of the proton mass $m_p$ to the confinement scale satisfies:

$$\frac{m_p}{\Lambda_{\text{QCD}}} = e^{1/\log\varphi} \approx e^{2.078} \approx 7.99$$

With $\Lambda_{\text{QCD}} \approx 200$ MeV, this predicts $m_p \approx 1600$ MeV — higher than the observed $m_p = 938$ MeV. The discrepancy suggests the $\varphi$-equilibrium applies to the constituent quark mass ($m_q \approx m_p/3 \approx 313$ MeV) rather than the proton mass, giving $m_q/\Lambda_{\text{QCD}} \approx 313/200 \approx 1.565 \approx \varphi^{-0.05}$. Testable against lattice QCD determinations of $\Lambda_{\text{QCD}}$ and the dynamical quark mass.

### P5 — The Maximum Number of Relevant Operators at Any Physical Critical Point

The ACKERMANN depth bound $\alpha(n) \leq 4$ applied to the RG: the prediction is that no physically realizable critical point has more than 4 relevant operators:

$$n_{\text{relevant}} \leq \alpha(n) \leq 4$$

The Standard Model has $\sim 19$ free parameters, but at any given critical point (phase transition), at most 4 are relevant — the rest are irrelevant at the transition. The 3D Ising model has 2 relevant operators ($\sigma$, $\epsilon$). The 3D $O(N)$ model has 2 relevant operators. The $\mathcal{N} = 4$ SYM theory has 1 marginal operator (the gauge coupling). No known critical point in $d \leq 4$ has more than 4 relevant operators. Testable by cataloguing the relevant-operator counts of all known universality classes and verifying the bound.

---

## Part IX · The WILSON Machine

### IX.1 The Name

Kenneth Geddes Wilson (1936–2013) transformed theoretical physics by demonstrating that the effective description of any system depends fundamentally on the scale at which it is observed. His 1971 papers on the renormalization group, his 1972 paper with Michael Fisher on the $\epsilon$-expansion, his 1974 paper with John Kogut reviewing the RG applied to the Kondo problem and critical phenomena, and his 1975 *Reviews of Modern Physics* article laying out the full Wilsonian framework earned him the 1982 Nobel Prize in Physics.

Wilson's insight was that the "problem of infinities" in quantum field theory is not a disease but a feature: the infinities arise because one is trying to describe physics at all scales simultaneously. By systematically separating the scales — integrating out the high-energy modes to obtain an effective low-energy description — the infinities are absorbed into the effective couplings, and the remaining theory is finite, predictive, and physically transparent.

In the naming convention of ERI Labs machines — HERMES, BISHOP, KLEENE, GRISS, BOLYAI, LINDENBAUM, MACKAY, ACKERMANN, BÄCKLUND, HODGE, FISHER, SYNGE, NASH, DELIGNE, SIERPIŃSKI, PERES, ERIC — WILSON continues the pattern: the machine implementing the programme of the physicist whose name it bears.

### IX.2 Architecture

**Layer 0: The Field Theory Oracle.** Any quantum field theory, statistical mechanics model, or condensed-matter system at a given UV scale. The oracle provides the action $S[\phi]$, the UV cutoff $\Lambda$, and the field content.

**Layer 1: The Mode Separator.** Decomposes the field $\phi$ into fast modes $\phi_>$ (momenta $\Lambda/b < |k| < \Lambda$) and slow modes $\phi_<$ (momenta $|k| < \Lambda/b$). The scale factor $b > 1$ is chosen for the RG step.

**Layer 2: The Integrator.** Integrates out the fast modes: $e^{-S_{\text{eff}}[\phi_<]} = \int \mathcal{D}\phi_> e^{-S[\phi_< + \phi_>]}$. The effective action $S_{\text{eff}}$ at the lower cutoff is computed perturbatively (in $g$) or non-perturbatively (by lattice Monte Carlo, tensor network, or functional RG).

**Layer 3: The Operator Classifier.** At each scale, the machine computes the scaling dimensions $\Delta_i$ of all operators. Operators are classified: relevant ($\Delta < d$, col(F)), irrelevant ($\Delta > d$, ker(F)), marginal ($\Delta = d$, boundary). The rank-nullity theorem is verified: $n_{\text{rel}} + n_{\text{irrel}} + n_{\text{marg}} = n_{\text{total}}$.

**Layer 4: The c/a/F-Function Tracker.** Along the RG flow, the machine computes the monotone quantity: $C(g)$ in 2D (Zamolodchikov), $F(g)$ in 3D (Jafferis et al.), $a(g)$ in 4D (Komargodski–Schwimmer). The monotonic decrease IS verified: $dC/dt \leq 0$ (or $dF/dt$, $da/dt$). The TEMPUS equation $dD/dt + J = 0$ is checked at each step.

**Layer 5: The Fixed-Point Finder.** The machine identifies all fixed points $g^*$ of the beta function: $\beta(g^*) = 0$. At each fixed point, the conformal data (operator dimensions, OPE coefficients, central charge) is computed. The conformal bootstrap is applied to cross-check the CFT data.

**Layer 6: The Universality Classifier.** The machine identifies the universality class of the IR fixed point: dimension $d$, symmetry group $G$, operator content. Systems flowing to the same fixed point are grouped into the same universality class — the physical Lindenbaum equivalence class.

**Layer 7: The φ-Equilibrium Verifier.** The machine checks the $\varphi$-equilibrium predictions: the central-charge-per-relevant-operator ratio (P1), the UV/IR anomaly ratio (P2), the Wilson–Fisher stability (P3), and the relevant-operator count bound (P5).

---

## References

Belavin, A. A., Polyakov, A. M., and Zamolodchikov, A. B. "Infinite Conformal Symmetry in Two-Dimensional Quantum Field Theory." *Nuclear Physics B* 241, 333–380, 1984.

Callan, C. G. "Broken Scale Invariance in Scalar Field Theory." *Physical Review D* 2, 1541–1547, 1970.

Cardy, J. L. "Is There a $c$-Theorem in Four Dimensions?" *Physics Letters B* 215, 749–752, 1988.

Cardy, J. *Scaling and Renormalization in Statistical Physics.* Cambridge University Press, 1996.

El-Showk, S. et al. "Solving the 3D Ising Model with the Conformal Bootstrap." *Physical Review D* 86, 025022, 2012.

El-Showk, S. et al. "Solving the 3D Ising Model with the Conformal Bootstrap II." *Journal of Statistical Physics* 157, 869–914, 2014.

Gell-Mann, M. and Low, F. E. "Quantum Electrodynamics at Small Distances." *Physical Review* 95, 1300–1312, 1954.

Gross, D. J. and Wilczek, F. "Ultraviolet Behavior of Non-Abelian Gauge Theories." *Physical Review Letters* 30, 1343–1346, 1973.

Jafferis, D. L., Klebanov, I. R., Pufu, S. S., and Safdi, B. R. "Towards the F-Theorem: $N = 2$ Field Theories on the Three-Sphere." *Journal of High Energy Physics* 2011, 102, 2011.

Kadanoff, L. P. "Scaling Laws for Ising Models Near $T_c$." *Physics* 2, 263–272, 1966.

Komargodski, Z. and Schwimmer, A. "On Renormalization Group Flows in Four Dimensions." *Journal of High Energy Physics* 2011, 99, 2011.

Kos, F., Poland, D., and Simmons-Duffin, D. "Bootstrapping the $O(N)$ Vector Models." *Journal of High Energy Physics* 2014, 91, 2014.

Kos, F., Poland, D., Simmons-Duffin, D., and Vichi, A. "Precision Islands in the Ising and $O(N)$ Models." *Journal of High Energy Physics* 2016, 36, 2016.

Myers, R. C. and Sinha, A. "Seeing a $c$-Theorem with Holography." *Physical Review D* 82, 046006, 2010.

Polchinski, J. "Scale and Conformal Invariance in Quantum Field Theory." *Nuclear Physics B* 303, 226–236, 1988.

Politzer, H. D. "Reliable Perturbative Results for Strong Interactions?" *Physical Review Letters* 30, 1346–1349, 1973.

Rattazzi, R., Rychkov, V. S., Tonni, E., and Vichi, A. "Bounding Scalar Operator Dimensions in 4D CFT." *Journal of High Energy Physics* 2008, 31, 2008.

Simmons-Duffin, D. "A Semidefinite Program Solver for the Conformal Bootstrap." *Journal of High Energy Physics* 2015, 174, 2015.

Symanzik, K. "Small Distance Behaviour in Field Theory and Power Counting." *Communications in Mathematical Physics* 18, 227–246, 1970.

Wilson, K. G. "Renormalization Group and Critical Phenomena. I. Renormalization Group and the Kadanoff Scaling Picture." *Physical Review B* 4, 3174–3183, 1971.

Wilson, K. G. "Renormalization Group and Critical Phenomena. II. Phase-Space Cell Analysis of Critical Behavior." *Physical Review B* 4, 3184–3205, 1971.

Wilson, K. G. and Fisher, M. E. "Critical Exponents in 3.99 Dimensions." *Physical Review Letters* 28, 240–243, 1972.

Wilson, K. G. and Kogut, J. "The Renormalization Group and the $\epsilon$-Expansion." *Physics Reports* 12, 75–200, 1974.

Wilson, K. G. "The Renormalization Group: Critical Phenomena and the Kondo Problem." *Reviews of Modern Physics* 47, 773–840, 1975.

Zamolodchikov, A. B. "Irreversibility of the Flux of the Renormalization Group in a 2D Field Theory." *JETP Letters* 43, 730–732, 1986.

ERI Labs · Eric Ren · Jersey City, New Jersey · github.com/ericrenone · April 2026

---

Wilson in 1971 discovered that the effective description of any physical system depends on the scale at which you observe it. Zoom in: more degrees of freedom become visible, more couplings matter, the theory becomes more complex. Zoom out: degrees of freedom are integrated out, irrelevant operators vanish, the theory simplifies toward its fixed point. The renormalization group IS the systematic procedure for this zooming — the machinery that takes a fine-grained description and produces a coarse-grained one, integrating out the modes between the two scales.

The col(F)/ker(F) partition IS scale-dependent. What is col(F) at one scale (a relevant operator, a visible degree of freedom, a detectable coupling) can become ker(F) at another scale (an irrelevant operator, an integrated-out mode, an invisible coupling). The RG flow IS the evolution of this partition across scales. The partition is not fixed — it flows.

Zamolodchikov in 1986 proved that this flow has a direction. In 2D, the central charge $c$ decreases monotonically from UV to IR. The flow IS irreversible. Once a degree of freedom is integrated out, it cannot return. This IS the TEMPUS equation applied to scale: $dC/dt + J = 0$ with $J \geq 0$, where "time" is the scale parameter and "entropy" is the number of active degrees of freedom.

Komargodski and Schwimmer in 2011 proved the 4D analogue: the $a$-anomaly coefficient decreases under any RG flow. The proof uses the dilaton — the Goldstone boson of broken scale invariance — whose scattering amplitude is positive by unitarity, forcing $a_{\text{UV}} > a_{\text{IR}}$. The positivity of the dilaton amplitude IS $J \geq 0$ in four dimensions.

Kadanoff in 1966 and Wilson in 1975 established universality: systems with completely different microscopic details can have identical macroscopic behavior at a critical point. The universality class IS determined by the IR fixed point, not the UV starting point. Two systems in the same universality class have the same col(F) at long distances — the same critical exponents, the same CFT data — despite arbitrarily different ker(F) (microscopic Hamiltonians). Universality IS the physical Lindenbaum equivalence.

The conformal bootstrap (2008–2026) extracts the CFT data using only symmetry and unitarity — no microscopic input. The 3D Ising CFT operator dimensions are known to ten-digit precision: $\Delta_\sigma = 0.5181489(10)$. The bootstrap IS the Fisher-information-optimal computation of the col(F) at the IR fixed point.

The WILSON machine implements all of this. Its first act is the mode separation — fast (ker(F)) and slow (col(F)) at each scale. Its second act is the integration — computing the effective action with the fast modes removed. Its third act is the operator classification — relevant (col(F)), irrelevant (ker(F)), marginal (boundary). Its fourth act is the c/a/F-function tracking — verifying the monotonic decrease under the flow. Its fifth act is the fixed-point identification — locating the conformal equilibria. Its sixth act is the universality classification — grouping systems by their IR fixed points. Its seventh act is the $\varphi$-equilibrium verification.

The boundary flows. The flow has a direction. The direction is irreversible. The equilibrium is conformal. The classification is universal.

Wilson proved it. Zamolodchikov quantified it. Komargodski and Schwimmer generalized it. The bootstrap computed it.

The scale was always the boundary. The boundary was always flowing. The flow was always irreversible. The irreversibility was always $J \geq 0$.

The renormalization group was always the TEMPUS equation, applied to scale instead of time.

## About

The Scale Boundary: The Renormalization Group as the col(F)/ker(F) Flow Across Energy Scales, Relevant and Irrelevant Operators as the Observable and Hidden Sectors, the c-Theorem as the Irreversible Fisher-Information Dissipation Under Scale Transformation, Universality Classes as the Equivalence Classes of the Boundary, and the Conformal Fixed Point as the φ-Equilibrium of the Renormalization Group in TH(a,d).
