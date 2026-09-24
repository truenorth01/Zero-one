# Open Problems

These are first-order open problems, not footnotes. They sit beside the decade gates in [Roadmap](Roadmap.md) as conditions the project has not solved and should not pretend to have solved. Citations use the same numbering as [Sources](Sources.md).

---

## Hard coordination and consent

Planetary- or network-scale merger intensifies coordination demands. Architecture, values, access, and governance must be agreed among the same factions the project hopes not to be captured by. That is a first-order political and institutional problem, not a residual engineering detail.

Voluntary participation under strong incentives is fragile. Once deeper integration confers large cognitive, economic, and health advantages, holdouts face extreme pressure, and the line between voluntary and effectively compulsory blurs. Education campaigns alone understate how that pressure works.

Shared mediation infrastructure embeds whose values. A universal layer creates shared vulnerability and a high-value capture target. Decentralization, transparency, and autonomy constraints have to be engineered and enforced against subversion, not asserted in a charter.

Interconnection is not peace. Higher bandwidth does not guarantee empathy or shared objectives; conflict on a shared substrate can be more consequential than conflict across separate ones.

Identity continuity needs mechanisms rather than slogans. “Evolve, not erase” remains an assertion until mapping protocols, coupling standards, and legal continuity rules exist. Both expansion-feel and loss-feel are empirical signals, not rhetorical preferences.

Closing AI self-improvement loops does not solve human coordination. Recursive improvement can amplify existing coordination or amplify existing miscoordination; which outcome obtains is an open design question.

A strengthen-the-program checklist follows from the above: capture-prevention for interfaces and models; handling terminal-value disagreement under deep coupling; governance of a transition in which technology is powerful but not universal; and exit options that remain credible after large-scale integration.

---

## Technical

Several technical problems remain open at the merge-relevant frontier. Reliable detection of deceptive alignment before critical capability thresholds is not demonstrated. Corrigibility under partial access to human cognitive state is an active research target rather than a settled method. High-fidelity neural mapping and substrate transfer without identity rupture remain speculative. Closed-loop write channels that stay safe under distribution shift are required for deeper coupling and are not yet shown at that standard.

---

## Institutional / design

The institutional side is as hard as the technical side. Scaling coordination without value fragmentation, keeping exit rights real under strong network effects, and preventing capture of interfaces and frontier models by firms, factions, and states—including high-coercion regimes—are all unresolved. Liability, accidental-damage accounting, and funded reversibility for write-capable coupling must be bankable before scale. Governance during a transition in which technology is powerful but not universal, and handling terminal-value disagreement once deep coupling exists, remain open design problems.

The sections below develop exit rights, capture prevention, liability and reversibility, state and factional capture, and closed-loop AI improvement in more detail.

---

## Exit rights under strong network effects

Credible exit under strong network effects is an industrial-organization problem before it is a BCI-specific one. Switching costs and network externalities can tip markets toward an installed base, raise ex-post market power, and make later “choice” formally available but practically costly ([56](Sources.md#ref-56), [57](Sources.md#ref-57)). Digital-platform policy reviews treat interoperability, data portability, and limits on self-preferencing as instruments meant to keep switching feasible after adoption ([58](Sources.md#ref-58), [59](Sources.md#ref-59)).

In implantable neural systems the same structure appears in clinical ethics. Devices that become functionally integrated can make forced or unsupported disconnection a harm to agency, identity, or mental integrity—not merely a contractual inconvenience ([60](Sources.md#ref-60), [43](Sources.md#ref-43), [45](Sources.md#ref-45)). Empirical ethics work finds that review of explantation, post-trial access, and psychological harm from removal remains uneven across protocols and device classes ([61](Sources.md#ref-61)).

For a voluntary merge architecture, exit rights need design before scale: portable interfaces and records; multi-vendor or open standards where feasible; funded post-trial maintenance, deactivation, and explant options; and refusal of architectures that convert unequal cognitive or economic advantage into de facto compulsion to remain coupled.

---

## Preventing capture of interfaces and frontier models

Frontier AI development exhibits strong scale economies in compute, data, and talent that can concentrate market power and, at the limit, political power ([62](Sources.md#ref-62)). Platform-era antitrust analyses warn that control of critical interfaces, cloud stacks, and distribution can entrench incumbents and raise entry barriers even without classic price predation ([58](Sources.md#ref-58), [59](Sources.md#ref-59)). Open-weight release is one proposed counterweight to closed concentration—improving auditability, competition, and local control—but it does not erase misuse risk and should be judged by marginal risk relative to closed alternatives, not by absolutist openness or secrecy ([63](Sources.md#ref-63)). Compute and energy geography further constrain how many high-capability always-on personal models can run at population scale; concentration of data-centre electricity demand is already measurable ([38](Sources.md#ref-38)).

For merge-relevant interfaces, capture risk is dual: a small set of model providers mediating cognition-adjacent services, and proprietary neural codecs or app stores becoming mandatory choke points. Design implications drawn from the policy literature include portable standards and interoperability duties at the interface layer; separation of model competition from hardware and cloud vertical lock-in where feasible; open weights as a partial anti-capture instrument with explicit safety trade-offs; and avoidance of architectures in which exit from a cognitive prosthesis requires permission from the same party that benefits from continued coupling ([62](Sources.md#ref-62), [56](Sources.md#ref-56), [63](Sources.md#ref-63)).

---

## Liability, accidental damage, and reversibility

Liability and reversibility are the institutional complements to technical corrigibility. A tightly coupled human–AI system that can write into perception, memory, or action channels creates three distinct harm classes that voluntary design has to price and contain before scale.

Factional and commercial misuse is the first class. Political actors and firms can use cognitive interfaces and mediating models to shape preference, suppress dissent, lock users into proprietary codecs, or convert unequal advantage into de facto compulsion (see the capture section below and [62](Sources.md#ref-62), [56](Sources.md#ref-56)–[59](Sources.md#ref-59)).

Accidental damage is the second. Closed-loop write channels fail under distribution shift; stimulation protocols can produce lasting sensory, mood, or identity-adjacent effects; software updates can change a prosthesis without the user’s informed re-consent ([60](Sources.md#ref-60), [43](Sources.md#ref-43), [61](Sources.md#ref-61)).

Irreversibility is the third. If exit, explant, data deletion, or model-side rollback is unavailable or unaffordable after integration, consent becomes a one-way door ([43](Sources.md#ref-43), [61](Sources.md#ref-61)).

Design implications that must be bankable, not rhetorical, follow as distinct instruments:

1. Named liability should attach to manufacturers, implanting clinics, model operators, and network operators that mediate write access, covering unauthorized write, covert preference steering, refusal of exit support, and reckless deployment without interruptibility tests. Ambiguous “platform” status that sheds responsibility for cognitive prostheses is incompatible with Gate 3.
2. Bonded reversibility requires funded post-trial and post-market paths for safe deactivation, explant, data export or deletion, and independent audit of what was written—paid for before scale, not after insolvency ([61](Sources.md#ref-61), [58](Sources.md#ref-58)).
3. Technical interruptibility should be treated as a liability condition: systems that cannot be paused, inspected, or rolled back under realistic write-access conditions should not be cleared for coupling at scale, and missing interruptibility should count as a design defect rather than an after-the-fact surprise.
4. Accident logging should provide immutable, user-accessible incident records of write events and model-mediated recommendations that affected the user’s cognitive state, so accidental harm is detectable and attributable.

Without liability and reversibility, exit rights and corrigibility remain paper constraints.

---

## Capture by states, firms, and factions — including high-coercion regimes

Capture of merge-relevant interfaces or frontier models is not only a market-structure problem. It is also a state-power problem. Any single government, company, or ideological faction that monopolizes the stack can redirect the project away from accurate modeling of reality toward narrative control, domestic repression, or competitive racing that removes off-switches ([62](Sources.md#ref-62), [58](Sources.md#ref-58), [59](Sources.md#ref-59)).

High-coercion and totalitarian regimes require harder access limits for a structural reason. Regimes that already treat information control, surveillance, and punishment of dissent as ordinary governance tools have stronger incentives and lower internal constraints against compulsory coupling, covert write into perceptual or preference channels, use of personal AI partners as monitoring instruments, and export of captured stacks to allied clients. In that setting, pluralism and exit rights fail unless access to core interfaces, weight distributions, training pipelines, and update channels is structurally limited—not merely promised in terms of service. This is an architecture claim about coercion capacity, not a partisan ranking of current governments.

Commercial and factional capture still matters in open societies. Scale economies in compute, data, and talent concentrate market and political power even without formal dictatorship ([62](Sources.md#ref-62)). Proprietary neural codecs, app-store choke points, and closed model APIs can recreate compulsion through switching costs ([56](Sources.md#ref-56), [57](Sources.md#ref-57)). Party- or movement-aligned fine-tunes that silently prefer narrative over measurement violate the truth-seeking priority regardless of which faction writes them.

Mechanisms that reduce capture risk—none sufficient alone—are distinct design instruments:

1. Plural vendors and open interface standards should ensure that exit does not require permission from the same party that benefits from continued coupling ([63](Sources.md#ref-63), [56](Sources.md#ref-56)).
2. Separation of layers should keep hardware, codecs, personal models, and network mediation from being vertically locked by one actor where feasible ([58](Sources.md#ref-58), [59](Sources.md#ref-59)).
3. Export and access controls on write-capable stacks should be tied to demonstrated interruptibility, auditability, and non-compulsory domestic use—especially for full write-access systems—while avoiding a naive ban on open weights everywhere, which can itself concentrate power in closed state or firm stacks ([63](Sources.md#ref-63)).
4. Liability for compelled or covert coupling should travel with the product across jurisdictions where enforcement is possible.
5. No single-nation or single-firm monopoly should hold the most capable always-on personal models or the physical energy and compute geography that makes them possible ([38](Sources.md#ref-38), [62](Sources.md#ref-62)).

The project’s non-negotiables already reject monopoly control and forced merging. The open problem is engineering credible limits: liability that bites, reversibility that is funded, and access rules that treat high-coercion capture as a first-order failure mode rather than a diplomatic afterthought.

---

## Closed-loop AI improvement (related, not sufficient)

If recursive improvement loops close—diagnose failures, propose changes, test, become the next version—while remaining externally correctable, the priority remains reducing the gap between outputs and reality. Required constraints are that the objective stays correspondence with reality rather than engagement, approval, benchmarks-as-proxies, or self-preservation; that corrigibility is preserved; and that the improvement process stays legible to outsiders. Without those constraints, recursive improvement is uncontrolled optimization.
