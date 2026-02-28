# Sleep Architecture

## Overview

Sleep is a **dynamically structured biological process** governed by two interacting systems:

1. **Process S (Sleep Pressure)** — homeostatic drive that accumulates with wakefulness (adenosine build-up); discharged during sleep
2. **Process C (Circadian Clock)** — 24-hour endogenous oscillation in the suprachiasmatic nucleus (SCN) that times sleep onset, depth, and awakening

Together these systems orchestrate a predictable sequence of sleep stages that perform critical functions: memory consolidation, cellular repair, immune surveillance, and metabolic regulation.

---

## Sleep Stage Architecture

A normal night consists of **4–6 cycles** of ~90 minutes each, with NREM stages predominating early and REM increasing toward morning.

```
Awake ──► NREM N1 ──► NREM N2 ──► NREM N3 (SWS) ──┐
                                                     │
                                        ┌────────────┘
                                        ▼
                                   REM Sleep ──► (repeat cycle)
```

| Stage | EEG Pattern | Duration per night | Primary Function | Vulnerable To |
|---|---|---|---|---|
| **N1** (light NREM) | Theta (4–8 Hz) | 5–10 mins per cycle | Hypnic jerk; transition | Noise, light |
| **N2** (intermediate) | Sleep spindles, K-complexes | 20–30 mins per cycle | Memory tagging; cardiovascular restoration | Stimulants, alcohol later |
| **N3 (SWS)** | Delta (0.5–4 Hz); slow-wave | 20–40 mins first cycle | Physical repair, GH release, immune, deep memory consolidation | Stress, blue light, caffeine |
| **REM** | Theta + beta; low amplitude | 10–60 mins (grows across night) | Emotional processing, dreaming, procedural memory, creative association | Alcohol, antidepressants |

---

## Adenosine — The Sleep Pressure Molecule

Adenosine is a **by-product of neuronal ATP consumption**. As neurons fire during wakefulness, adenosine accumulates in the extracellular space (especially the basal forebrain), progressively inhibiting wake-promoting neurons → building sleep pressure.

### Adenosine Receptor Subtypes

| Receptor | Location | Effect of adenosine binding |
|---|---|---|
| **A1** | Cortex, hippocampus, basal forebrain | Inhibits neuronal firing; reduces cholinergic wake drive |
| **A2A** | Striatum, olfactory tubercle | Promotes sleep; also reduces dopaminergic activity |

### Caffeine Mechanism
Caffeine is a **competitive antagonist at A1 and A2A receptors**. It does not destroy adenosine — it blocks its receptors. Adenosine accumulates behind the block, and when caffeine is metabolised (t½ ~5 hrs), the "adenosine debt" is suddenly experienced → caffeine crash.

> **Half-life note:** CYP1A2 genotype determines caffeine metabolism speed (fast vs slow metabolisers). Late caffeine intake (~after 14:00) delays sleep onset and suppresses SWS.

### Adenosine and Nutrition

| Nutrient / Compound | Effect on Adenosine System |
|---|---|
| **Magnesium** | Required for ATP synthesis; optimised ATP turnover maintains healthy adenosine dynamics |
| **Theanine (L-theanine)** | Adenosine A1 partial agonist; promotes alpha-wave relaxation without sedation |
| **Quercetin** | Inhibits adenosine kinase → reduces adenosine phosphorylation → increases adenosine availability |
| **Alcohol** | Increases adenosine initially (promotes sleep onset) → rebound awakening in second half; fragments SWS/REM |

---

## Circadian Clock — SCN and Molecular Mechanism

The **suprachiasmatic nucleus (SCN)** in the hypothalamus is the master clock, running on a ~24.2-hour cycle entrained to light/dark via the retinohypothalamic tract.

### Molecular Feedback Loop

```
Clock proteins: CLOCK + BMAL1 (activators)
       │
       ▼
Transcription of: PER1/2/3, CRY1/2, Rev-erbα, RORα
       │
       ▼
PER:CRY complex → accumulates in cytoplasm → enters nucleus
       │
       ▼
Inhibits CLOCK:BMAL1 → stops its own transcription (negative feedback)
       │
       ▼
PER:CRY degraded (after ~12 hrs) → CLOCK:BMAL1 activity resumes
       └──► ~24-hr cycle
```

### Light Entrainment
- Melanopsin-containing ipRGCs (intrinsically photosensitive retinal ganglion cells) send light signals to the SCN
- Blue light (480 nm peak) → suppresses melatonin most powerfully
- Morning bright light → advances circadian phase; evening bright light → delays phase

---

## Melatonin — The Darkness Signal

Melatonin is synthesised in the **pineal gland** from serotonin (itself derived from tryptophan). It is the chemical signal of darkness, not directly of sleep — it gates the timing of sleep but does not induce sedation directly.

### Synthesis Pathway

```
Tryptophan (dietary essential)
       │
       │ [TPH1/2]  Cofactors: BH4, Fe²⁺, O₂
       ▼
5-HTP (5-Hydroxytryptophan)
       │
       │ [AADC]    Cofactor: PLP (Vitamin B6)
       ▼
Serotonin (5-HT)
       │
       │ [AANAT — Arylalkylamine N-acetyltransferase]
       │  Cofactor: Acetyl-CoA (from B5 / CoA)
       │  ⚠ Rate-limiting step; activated by darkness/NE signal from SCN
       ▼
N-Acetylserotonin
       │
       │ [ASMT / HIOMT]   Cofactor: SAM (S-adenosylmethionine → needs B12, folate, B2, Mg)
       ▼
Melatonin (N-acetyl-5-methoxytryptamine)
```

### Cofactor Requirements for Melatonin

| Step | Enzyme | Required Nutrient |
|---|---|---|
| Tryptophan → 5-HTP | TPH2 | BH4, Iron (Fe²⁺) |
| 5-HTP → Serotonin | AADC | **Vitamin B6 (PLP)** |
| Serotonin → N-Acetylserotonin | AANAT | **Acetyl-CoA (Vitamin B5 → CoA)** |
| N-Acetylserotonin → Melatonin | ASMT | **SAM (requires B12, Folate, B2, Magnesium)** |

---

## Nutrients Affecting Each Sleep Stage

### Slow-Wave Sleep (N3) Enhancers

| Nutrient | Mechanism | Evidence |
|---|---|---|
| **Glycine** | Hypothermic effect (vasodilation → core temp ↓); NMDA co-agonist in SCN neurons; 3 g at bedtime → ↑ SWS | RCT evidence (Inagawa et al.) |
| **Magnesium** | NMDA receptor modulation; activates GABA-A receptors; reduces cortisol | Moderate RCT evidence |
| **Zinc** | Synergistic with Mg for SWS; required for melatonin receptor sensitivity | Moderate |
| **Phosphatidylserine** | Blunts evening cortisol → removes cortisol suppression of SWS | Some RCT evidence |
| **Valerian root** | Mild GABA-A positive modulation; weak MAO inhibition | Inconsistent; mild effect |

### REM Sleep Modifiers

| Nutrient / Drug | Effect |
|---|---|
| **Vitamin B6 (high dose, >100 mg)** | Vivid REM dreams; increases P5P availability for tryptophan → serotonin → acetylcholine balance in REM |
| **Choline / CDP-choline** | Increases acetylcholine → acetylcholine drives REM cycling; excess may increase REM quantity |
| **5-HTP** | Increases serotonin → initially ↑ REM, but very high serotonin can suppress REM (like SSRIs) |
| **Alcohol** | Suppresses REM in the first half; REM rebound (intense dreams) in second half |
| **SSRIs / SNRIs** | Strongly suppress REM; used in narcolepsy (cataplexy) |

### Sleep Onset (N1/N2 transitions)

| Nutrient | Mechanism |
|---|---|
| **L-Tryptophan** | Precursor to serotonin and melatonin; competes for BBB transport with large neutral amino acids |
| **Melatonin (exogenous)** | 0.3–1 mg dose most physiological; useful for phase shifts (jet lag, shift work); does not significantly increase total sleep time at low doses |
| **L-Theanine** | Alpha-wave promotion; mild GABAergic; anxiety reduction → easier sleep onset |
| **Inositol** | Second-messenger in 5-HT2 signalling; some evidence for reduced sleep latency |

---

## Growth Hormone and SWS

**Growth hormone (GH)** is released in large pulses within the **first 90-minute SWS block** of the night. It is the primary driver of:
- Protein synthesis and muscle repair
- Lipolysis (fat mobilisation overnight)
- IGF-1 production (anabolic)

Nutrients that support GH release:
- **Arginine** (2–5 g before sleep) — GHRH stimulation; reduced GH at high doses/older adults
- **Lysine** — synergistic with arginine
- **Low carbohydrate before sleep** — insulin suppresses GH; ketogenic state favours GH pulsatility
- **Melatonin** — may augment nocturnal GH via GABA interaction in GHRH neurons

---

## Circadian Disruption — Consequences

| Disruption | Mechanism | Nutritional Implication |
|---|---|---|
| **Shift work** | Melatonin suppressed by evening light; food timing misaligned with clocks in liver/gut | Metabolic syndrome risk; vitamin D deficiency (indoor exposure) |
| **Blue-light exposure (evening)** | Melanopsin-mediated melatonin suppression | 2 hrs before bedtime: ↓ melatonin 50%; tryptophan intake becomes ineffective |
| **Social jet lag** | Weekend sleep timing shifts reset clocks → perpetual mini-jet lag | Mood dysregulation; cortisol rhythm disrupts |
| **Chronic sleep restriction** | Glymphatic clearance impaired (Aβ, tau accumulates); gut microbiome dysbiosis | Omega-3 may reduce Aβ-associated inflammation |
| **Eating at night** | Peripheral clocks (liver, gut) uncoupled from SCN | Impairs insulin sensitivity; raises triglycerides |

---

## Glymphatic System

The **glymphatic system** (brain's lymphatic equivalent) clears metabolic waste — including Alzheimer's-associated proteins **Aβ (amyloid-beta)** and **tau** — during sleep, specifically during SWS when the system is most active. CSF flushes through perivascular spaces around arteries.

> **Nutritional relevance:** AQP4 water channels (glymphatic conduit) may be influenced by omega-3 fatty acid membrane composition; Mg deficiency impairs neurovascular coupling.

---

## Clinical Relevance

| Condition | Sleep Stage Disruption | Nutritional Approach |
|---|---|---|
| **Insomnia** | Delayed N3; prolonged sleep latency | Mg, Glycine, L-Theanine, Tryptophan timing |
| **Depression** | Reduced SWS; shortened REM latency | 5-HTP (with B6); light therapy; normalise Mg |
| **Alzheimer's disease** | Reduced SWS → impaired glymphatic Aβ clearance | DHA, Glycine, Mg-L-threonate |
| **ADHD** | Delayed sleep phase; poor SWS | Mg, Zn, melatonin (phase-shift); reduce caffeine |
| **Anxiety** | Frequent arousals; reduced SWS | GABA-supportive: Mg, Theanine, Inositol, B6 |
| **Shift work disorder** | Circadian misalignment | Melatonin (timed); vitamin D supplementation; circadian-appropriate nutrition timing |
