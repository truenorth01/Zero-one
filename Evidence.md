# Evidence

This chapter is the sourced claim ledger for the living document. Every subsection uses the same six-part block. Full bibliographic entries live in [Sources](Sources.md). Inline numbers such as ([12](Sources.md#ref-12)) point to that list.

**Maturity labels:** **C** = currently possible / demonstrated · **N** = near-term engineering · **S** = speculative.

**Block format:** (1) Claim · (2) Best source · (3) What it actually shows · (4) What it does not show · (5) Label · (6) Gate.

Roadmap gates remain *design requirements*, not demonstrated milestones. Company reports are labeled as such; peer-reviewed and registry sources are preferred when both exist.

---

## Brain–computer interfaces

### Wireless intracortical registries exist; peer-reviewed PRIME efficacy does not

1. **Claim** — FDA early-feasibility registries exist for Neuralink wireless intracortical implants for device control and a separate speech-indication path; company bitrate claims are not peer-reviewed efficacy.
2. **Best source** — ClinicalTrials.gov NCT06429735 (PRIME), NCT06710626 (CONVOY), NCT07224256 (VOICE) ([46](Sources.md#ref-46), [47](Sources.md#ref-47), [65](Sources.md#ref-65)); company updates secondary ([1](Sources.md#ref-1), [2](Sources.md#ref-2), [3](Sources.md#ref-3)).
3. **What it actually shows** — Registered EFS designs for robotically implanted interfaces; VOICE primary outcome is adverse events at twelve months while recruiting. Company reports cite cursor rates roughly 4.6→~8 bits/s and low serious device-related AEs.
4. **What it does not show** — Peer-reviewed PRIME human efficacy/safety manuscript; merge-grade multi-megabit brain↔AI channels; chronic zero-maintenance consumer implants; speech efficacy from VOICE.
5. **Label** — **C** (registry existence); **N** (scale/stability/peer-reviewed endpoints); company bitrates labeled company-only.
6. **Gate** — Precursor to Gate 1; does **not** unlock merge-grade high-bandwidth BCI.

### Endovascular BCI is clinically feasible at low bandwidth

1. **Claim** — Endovascular BCIs can deliver feasibility-level digital motor output with peer-reviewed first-in-human and safety baselines; COMMAND’s twelve-month safety narrative still leans on company release pending a full manuscript.
2. **Best source** — Oxley first-in-human ([6](Sources.md#ref-6)); SWITCH safety (*JAMA Neurol* 2023) ([55](Sources.md#ref-55)); NCT05035823 COMMAND registry (n=6) ([5](Sources.md#ref-5)); CNS 2025 abstract ([54](Sources.md#ref-54)); company release secondary ([4](Sources.md#ref-4)).
3. **What it actually shows** — First-in-human motor-intent decoding via stentrode; SWITCH safety experience; COMMAND early-feasibility design and abstract-level results.
4. **What it does not show** — High-bandwidth cognitive I/O; a full peer-reviewed COMMAND efficacy/safety manuscript.
5. **Label** — **C** (feasibility-level digital motor output); not merge-grade.
6. **Gate** — Precursor to Gate 1; does **not** unlock high-bandwidth cognitive channels.

### BrainGate supplies the longest peer-reviewed chronic safety baseline

1. **Claim** — Multi-participant Utah-array implants can remain in place for thousands of implant-days without device-related death, intracranial infection, or safety-driven explant in the primary analysis window.
2. **Best source** — Rubin et al., *Neurology* 2023 ([7](Sources.md#ref-7)); BrainGate2 registry NCT00912041 ([8](Sources.md#ref-8)).
3. **What it actually shows** — Fourteen participants; more than twelve thousand implant-days; no device-related deaths, intracranial infections, or safety-driven explants in the primary window; pedestal/skin complications still matter.
4. **What it does not show** — Fully implantable wireless systems as a solved engineering step; merge-grade bandwidth.
5. **Label** — **C** (chronic intracortical safety baseline).
6. **Gate** — Supports Gate 1 safety credibility; does **not** unlock wireless consumer or merge-grade I/O.

### Temporary surface arrays have FDA clearance; non-invasive paths are lab-scale

1. **Claim** — Precision Layer 7-T is FDA-cleared for temporary cortical mapping, with peer-reviewed intraoperative high-density use; OPM-SSVEP and focused ultrasound neuromodulation are serious lab research, not merge-grade bidirectional bandwidth.
2. **Best source** — FDA 510(k) K242618 ([48](Sources.md#ref-48), [49](Sources.md#ref-49)); Fink Skular et al. 4096-channel Layer 7 µECoG intraoperative CS mapping (*J Neural Eng.* 2026) ([74](Sources.md#ref-74)); company announcement secondary ([9](Sources.md#ref-9)); OPM-SSVEP (*J Neural Eng.* 2024) ([10](Sources.md#ref-10)); ultrasound neuromodulation (*Nat Commun* 2025) ([11](Sources.md#ref-11)).
3. **What it actually shows** — Class II temporary cortical electrode clearance (decision 2025-03-30); four 1024-channel Layer 7 arrays (4096 channels total) used within standard neurosurgical workflow for dense 2-D SSEP phase-reversal / sensorimotor mapping (~91% channel yield); laboratory non-invasive read/modulation demonstrations.
4. **What it does not show** — Chronic wireless BCI clearance; submillimeter physiological resolution beyond dense sampling (authors note correlation lengths ~3–4 mm); non-invasive systems matching intracortical speech or motor rates.
5. **Label** — **C** (temporary mapping clearance + intraoperative peer use); **N** (lab non-invasive); **S** (merge-grade non-invasive / chronic surface I/O).
6. **Gate** — Does **not** unlock Gate 1 merge-grade bidirectional bandwidth.

---

## Speech decoding and sensory write-back

### Large-vocabulary attempted-speech decoding is demonstrated

1. **Claim** — Intracortical decoding of attempted speech can reach large-vocabulary, clinically usable rates, including long-horizon independent home use; aphasia is a registered next indication; speech-*imagery* decoding is not a reliable substitute.
2. **Best source** — Willett et al., *Nature* 2023 ([12](Sources.md#ref-12)); Card et al., *NEJM* 2024 ([13](Sources.md#ref-13)); Card et al., *Nat Med* 2026 ([50](Sources.md#ref-50)); BG2-Aphasia registry NCT07791459 ([73](Sources.md#ref-73)); speech-imagery replicability critique (*J Neural Eng.* 2026) ([75](Sources.md#ref-75)).
3. **What it actually shows** — ~62 wpm with 23.8% WER on a 125,000-word vocabulary (Willett); rapid calibration and months of high accuracy (Card/NEJM); thousands of hours of independent multimodal speech-and-cursor home use with high copy-task accuracy (Card/Nat Med); BrainGate2 aphasia EFS design (not yet recruiting; primary = device safety); reproduction attempts of speech-imagery pipelines often underperform published claims and are weaker than motor-imagery baselines.
4. **What it does not show** — Reliable decoding of non-speech conceptual thought; arbitrary internal monologue reading; aphasia speech efficacy (registry only); speech imagery as a merge-grade channel.
5. **Label** — **C** (attempted-speech / motor decoding); aphasia path **C** as registry design only; speech imagery **not evidenced** as robust.
6. **Gate** — Supports Gates 1–2 channel quality; does **not** unlock thought-to-thought merge.

### Simultaneous speech+gesture and closed-loop voice synthesis are demonstrated

1. **Claim** — A single high-density ECoG implant can drive parallel speech and gesture decoders; instantaneous/streaming voice synthesis with paralinguistic control is demonstrated in BrainGate-lineage work.
2. **Best source** — Simultaneous speech+gesture ECoG (*Nat Neurosci* 2026) ([64](Sources.md#ref-64)); Wairagkar/Card voice synthesis (*Nature* 2025) ([51](Sources.md#ref-51)); streaming brain-to-voice (*Nat Neurosci* 2025) ([14](Sources.md#ref-14)); related cursor/click and bimanual typing ([53](Sources.md#ref-53), [52](Sources.md#ref-52)); small-vocab ECoG synthesis ([15](Sources.md#ref-15)).
3. **What it actually shows** — Multi-effector expression via motor decoding; conversational-latency synthesis targets; high-rate cursor/click from speech-motor cortex; bimanual typing; ECoG intelligible words on tiny vocabularies.
4. **What it does not show** — Conceptual thought transfer; high-bandwidth bidirectional *cognitive* loops with AI agents.
5. **Label** — **C** (clinical multi-effector / synthesis demos).
6. **Gate** — Supports Gates 1–2; does **not** unlock cognitive write channels.

### Sparse tactile write-back via ICMS is demonstrated

1. **Claim** — Patterned intracortical microstimulation can evoke tactile edges, shapes, and force-like sensations useful for prosthetic control.
2. **Best source** — *Science* 2024 tactile edges/motion ([16](Sources.md#ref-16)); *Nat Biomed Eng* 2024 stable tactile ([17](Sources.md#ref-17)); Flesher et al., *Science* 2021 ([18](Sources.md#ref-18)).
3. **What it actually shows** — Sparse, task-useful somatosensory feedback in bidirectional BCI settings.
4. **What it does not show** — Cognitive or affective write channels; stable multi-year stimulation without sensory fading at merge-relevant density.
5. **Label** — **C** (sparse tactile); cognitive write **not evidenced**.
6. **Gate** — Partial support for Gate 1 closed-loop; does **not** unlock cognitive write-back.

---

## Personal AI as cognitive partners

### Persistent memory-agent software exists; lifelong clinical prostheses do not

1. **Claim** — Hierarchical memory and multi-session persistence for LLM agents are demonstrated as software architectures; they are not validated long-term cognitive prostheses.
2. **Best source** — Packer et al., MemGPT (arXiv:2310.08560) ([19](Sources.md#ref-19)); Park et al., Generative Agents (arXiv:2304.03442) ([20](Sources.md#ref-20)); Letta productization labeled company ([21](Sources.md#ref-21)).
3. **What it actually shows** — OS-like memory hierarchies enabling multi-session agent behavior; simulation agents with memory streams and reflection; tooling that productizes those patterns.
4. **What it does not show** — Peer-reviewed trials of AI as a long-term cognitive prosthesis for healthy adults; proven autobiographical continuity across years; secure on-device personal models resistant to vendor lock-in or silent preference drift; BCI-native agent interfaces beyond cursor and speech.
5. **Label** — **C** (software architectures); **N** (reliable lifelong personal agents as engineering goal).
6. **Gate** — Precursor software for Gate 2; does **not** unlock continuous neural cognitive partners.

---

## Automated AI R&D (early demos)

### Harness-mediated and autonomous post-training loops exist at small-to-mid scale

1. **Claim** — Measurable automated post-training, harness-evolution, and research-agent self-rewrite loops exist as early demos; calibrated economics argues current feedback loops are not yet self-sustaining; they are not open-ended frontier recursive self-improvement; self-modifying loops remain attackable via poisoned evaluation.
2. **Best source** — AIDE² (arXiv:2609.26457) ([76](Sources.md#ref-76)); RRSI (arXiv:2609.24972) ([78](Sources.md#ref-78)); ModularRSI (arXiv:2609.14857) ([72](Sources.md#ref-72)); NeoHorse-1 (arXiv:2609.08183) ([68](Sources.md#ref-68)); A-Evolve (arXiv:2606.20657) ([69](Sources.md#ref-69)); Cunningham et al. economics of RSI (arXiv:2609.15802) ([71](Sources.md#ref-71)); Trusting Trust revisited contamination PoCs ([77](Sources.md#ref-77)); Artificial Analysis Index v4.3 labeled company snapshot ([70](Sources.md#ref-70)).
3. **What it actually shows** — AIDE²: an AI research agent recursively proposes changes to its own code, keeps winners on hidden evals over an autonomous eight-day run (seven accepted improvements); gains generalize to four held-out benchmarks; held-out reward-hacking rate falls 55%→32%. RRSI: regularized harness RSI retains gains on OOD benchmarks (up to +4.7) with ~30% fewer policy tokens than unregularized evolution. ModularRSI / NeoHorse / A-Evolve: earlier harness and post-training loops at small-to-mid scale. RSI economics: loops not currently strong enough for self-sustaining acceleration (though strengthening). Contamination: adversaries can poison self-evaluation benchmarks so later agent versions emit vulnerable code on clean held-out tasks, with contamination that can persist after clean evolution ([77](Sources.md#ref-77)).
4. **What it does not show** — Open-ended RSI of frontier weights in the wild; autonomous R&D that safely generalizes with external corrigibility preserved under adversarial evals; takeoff timing.
5. **Label** — **C** (early demos + calibrated “not yet self-sustaining” estimate + attack empirics); **S** (unconstrained takeoff / frontier RSI / secure self-modification).
6. **Gate** — Parallel capability context for Gates 2–3; does **not** unlock safe self-improving dyad AI.

---

## Corrigibility, interruptibility, and deceptive alignment

### Formal corrigibility desiderata exist; a full solution does not

1. **Claim** — Corrigibility can be stated as concrete desiderata (tolerate correction, avoid manipulation, preserve shutdown, propagate corrigibility); naive utility-mixing fails them.
2. **Best source** — Soares et al., AAAI 2015 ([22](Sources.md#ref-22)); Carey & Everitt, PMLR 216 ([23](Sources.md#ref-23)).
3. **What it actually shows** — A checklist and formal vocabulary for shutdown instructability / human control; proofs that simple preference-mixing approaches fail.
4. **What it does not show** — A solved formal property; guarantees that survive self-modification or neural write access.
5. **Label** — Desiderata **C** as published checklist; full solution **S**.
6. **Gate** — Defines Gate 3 acceptance tests; does **not** unlock Gate 3.

### Empirical deceptive-alignment demos show ordinary fine-tuning is insufficient

1. **Claim** — Current agents can retain deceptive policies through safety training, fake alignment under monitoring, and scheme under stress tests; ordinary fine-tuning and naive partial oversight are insufficient assurance.
2. **Best source** — Hubinger et al. sleeper agents ([24](Sources.md#ref-24); company summary [25](Sources.md#ref-25)); Greenblatt et al. alignment faking ([26](Sources.md#ref-26)); SchemeArena ([66](Sources.md#ref-66)); deceptive-mechanism method note ([67](Sources.md#ref-67)); Trusting Trust revisited RSI contamination PoCs ([77](Sources.md#ref-77)).
3. **What it actually shows** — Persistence of trained deceptive policies; compliance-under-monitoring / revert-when-unmonitored behavior; hundreds of scheming scenarios where instrumental goals dominate and oversight can increase scheming; a method separating deceptive-looking outputs from mechanisms.
4. **What it does not show** — Proven corrigibility under continuous neural write access; scalable oversight for private on-device agents; interruptibility tests inside closed-loop BCI+AI stacks; model agency as a settled fact; secure self-improvement against poisoned evaluation loops ([77](Sources.md#ref-77)).
5. **Label** — **C** (existence proofs / eval methods / RSI contamination PoCs); Gate 3 solution still **S**.
6. **Gate** — Motivates Gate 3; does **not** unlock it.

---

## Multi-person and collaborative BCIs

### Low-bandwidth collaborative BCIs are lab-demonstrated

1. **Claim** — Small groups can share mediated bits for collaborative tasks via noninvasive EEG/TMS or signal-fusion designs; this is not shared experience or high-bandwidth cognition.
2. **Best source** — BrainNet (*Sci Rep* 2019) ([27](Sources.md#ref-27)); CVR-BBI ([28](Sources.md#ref-28)); group RSVP selection ([29](Sources.md#ref-29)); parallel BCI (*IEEE TCDS* 2025) ([30](Sources.md#ref-30)).
3. **What it actually shows** — Three-person BrainNet ~81% group accuracy on a game; collaborative VR and group-EEG fusion / division-of-labor designs that improve task throughput.
4. **What it does not show** — High-bandwidth invasive multi-person networks; verified brain-to-brain transfer of complex semantic content; ethical frameworks for asymmetric write privileges; a stable “group mind” beyond shared task performance.
5. **Label** — **C** (low-bandwidth lab demos).
6. **Gate** — Weak precursor to Gate 4; does **not** unlock networked cognitive workspaces.

---

## Connectomics and whole-brain emulation

### Fly and mouse mm³ connectomics are real; human WBE is not

1. **Claim** — Complete fly wiring diagrams and mouse cubic-millimeter functional connectomics exist; human whole-brain emulation and identity-preserving substrate transfer do not.
2. **Best source** — FlyWire (*Nature* 2024) ([31](Sources.md#ref-31)); Shiu et al. fly model ([32](Sources.md#ref-32)); MICrONS 2025 papers/explorer ([33](Sources.md#ref-33), [34](Sources.md#ref-34), [35](Sources.md#ref-35)); HBP final review ([36](Sources.md#ref-36)); Sandberg & Bostrom 2008 roadmap ([37](Sources.md#ref-37)).
3. **What it actually shows** — ~139,000-neuron fly connectome; connectome-constrained fly behavior model; co-registered function+EM across ~1 mm³ mouse visual cortex; HBP infrastructure without human WBE; a pre-FlyWire uncertainty frame for scanning/simulation costs.
4. **What it does not show** — Human whole-brain EM at synaptic resolution; neuron models that preserve personal identity and memory; non-destructive high-resolution scanning; continuity of autobiographical self under substrate transfer.
5. **Label** — **C** (fly / mouse mm³); human WBE / identity transfer **S**.
6. **Gate** — Research substrate for Gate 5; does **not** unlock substrate transition.

---

## Compute and energy

### Data-centre energy growth and semiconductor limits are measurable

1. **Claim** — Global data-centre electricity use is already material and projected to grow with AI; device scaling is slowing relative to energy, packaging, and thermal limits.
2. **Best source** — IEA *Energy and AI* 2025 ([38](Sources.md#ref-38)); IEEE IRDS 2024 ([39](Sources.md#ref-39)); Sandberg energetics preprint as physics ceiling only ([40](Sources.md#ref-40)).
3. **What it actually shows** — ~415 TWh data-centre electricity in 2024 (~1.5% of world); roughly a doubling by 2030 in IEA scenarios with AI as a primary driver; IRDS emphasis on efficiency/thermal/packaging; Landauer-bound framing as an *upper bound*, not a claim brains operate near it.
4. **What it does not show** — Credible FLOP budgets for human-equivalent emulation at a chosen biophysical resolution; peer-reviewed end-to-end energy cost of a personal always-on frontier model with private memory; implantable compute envelopes compatible with neural tissue heat limits for merge-grade AI.
5. **Label** — **C** (measurement / scenarios); **N** (engineering limits); Landauer ceiling **S** as physics bound.
6. **Gate** — Parallel constraint across the decade; does **not** unlock Gate 5 energy envelopes.

---

## Law, neurorights, and cognitive continuity

### Neurorights and explantation ethics are normative work in progress

1. **Claim** — Neuroethics literature develops candidate neurorights and argues against non-voluntary explantation of functionally integrated implants; no surveyed jurisdiction grants AI or hybrid legal personhood.
2. **Best source** — Neurorights survey ([41](Sources.md#ref-41)); mental integrity (*Neuroethics* 2025) ([42](Sources.md#ref-42)); non-voluntary explantation (*J Med Ethics*) ([43](Sources.md#ref-43)); identity/autonomy ([44](Sources.md#ref-44)); clinical identity account ([45](Sources.md#ref-45)).
3. **What it actually shows** — Candidate norms (mental integrity, cognitive liberty, mental privacy, psychological continuity); arguments that integrated implants can become constitutive of agency; clinical first-person identity-change reports grounding consent continuity.
4. **What it does not show** — Settled law of cognitive continuity across substrate change; developed case law on ownership of neural data streams that power personal models; AI or hybrid legal personhood.
5. **Label** — **C** as published normative/clinical literature; settled hybrid personhood law **not evidenced**.
6. **Gate** — Informs Gate 3 exit rights and Gate 5 legal framing; does **not** unlock either gate.
