# Melatonin

## Overview

Melatonin (N-acetyl-5-methoxytryptamine) is an indolamine hormone and neuromodulator synthesised primarily by the **pineal gland** from serotonin. It is the **principal signal of circadian night**, communicating darkness to the body and regulating sleep onset, immune modulation, antioxidant defence, and reproductive seasonality. Because melatonin is made from serotonin, it sits at the downstream end of the tryptophan cascade and is directly affected by all the upstream cofactors that govern serotonin synthesis.

> **Key insight** — Melatonin synthesis is controlled almost entirely by **light exposure**, not by substrate availability alone. Blue-light exposure at night (480 nm) suppresses melatonin via retino-hypothalamic tract → suprachiasmatic nucleus (SCN) → paraventricular nucleus → superior cervical ganglion → pineal gland. Nutritional support is necessary but insufficient without circadian light hygiene.

---

## Synthesis Pathway

```
L-Tryptophan  (dietary essential amino acid)
      │
      │ [Tryptophan hydroxylase 1 — TPH1 (pineal)]
      │  Cofactors: BH4, Fe²⁺, O₂, NADPH
      ▼
5-HTP (5-Hydroxytryptophan)
      │
      │ [AADC — Aromatic amino acid decarboxylase]
      │  Cofactor: PLP (Vitamin B6)
      ▼
Serotonin (5-HT)
      │
      │  Nighttime: NE released from SCG (from SCN entrainment)
      │  NE activates β/α1-adrenoceptors → cAMP ↑ → PKA → AANAT transcription
      │
      │ [AANAT — Arylalkylamine N-acetyltransferase]
      │  Cofactor: Acetyl-CoA (requires B5/pantothenate chain)
      │  ⚠ Rate-limiting step for melatonin (controlled by circadian clock)
      ▼
N-Acetylserotonin (NAS)
      │
      │ [ASMT — Acetylserotonin O-methyltransferase]
      │  Cofactor: SAM (S-adenosylmethionine)
      │            → requires B12, Folate (5-MTHF), Riboflavin (B2), Mg²⁺, Methionine
      ▼
Melatonin (N-acetyl-5-methoxytryptamine)
      │
      ▼
Released directly into blood and CSF (no vesicle storage — lipid soluble)
```

### Step-by-Step Cofactor Requirements

| Step | Enzyme | Required Cofactors / Nutrients |
|---|---|---|
| **Tryptophan → 5-HTP** | TPH1 | BH4, Fe²⁺, O₂, NADPH |
| **5-HTP → Serotonin** | AADC | **PLP (Vitamin B6)**, Zn²⁺ |
| **Serotonin → NAS** ⚠ | AANAT | **Acetyl-CoA** (from B5, B1, B2, B3, lipoic acid) |
| **NAS → Melatonin** | ASMT | **SAM** (methionine + B12 + 5-MTHF + B2 + Mg²⁺) |
| **BH4 regeneration** | DHFR, DHPR | Folate (B9), Riboflavin (B2), NADPH |

---

## Light Regulation (Circadian Control of AANAT)

```
Light (daytime) → Retina → Retino-hypothalamic tract → SCN
      │
      └──► SCN inhibits PVN → inhibits SCG → inhibits pineal
           → AANAT is low → no melatonin

Dark (nighttime) → SCN disinhibits PVN → SCG activated
      │
      └──► Norepinephrine released onto pinealocytes
           → β1 + α1 adrenoceptors → cAMP + PKC ↑
           → AANAT transcription + post-translational stabilisation
           → Melatonin surge (peaks ~2–4 am)
```

**Blue light (480 nm)** is the most potent melatonin suppressor — targets melanopsin-containing intrinsically photosensitive retinal ganglion cells (ipRGC).

---

## Degradation Pathway

```
Melatonin (blood, tissues)
      │
      ├──► Liver (major route):
      │    [CYP1A2, CYP1A1, CYP1B1]
      │     → 6-Hydroxymelatonin
      │         │
      │         │ [SULT / UGT Phase II conjugation]
      │         ▼
      │     6-Sulphatoxymelatonin (aMT6s) → urine (principal metabolite, standard biomarker)
      │
      └──► Brain:
           [AFMK pathway — enzymatic + non-enzymatic]
           Melatonin → AFMK (N1-acetyl-N2-formyl-5-methoxykynuramine)
                     → AMK (N1-acetyl-5-methoxykynuramine)
                     (antioxidant metabolites — free radical cascade)
```

| Route | Enzyme | Cofactor | Product | Significance |
|---|---|---|---|---|
| **Hepatic hydroxylation** | CYP1A2 | Haem, O₂, NADPH | 6-OH-Melatonin | Primary metabolic route |
| **Phase II conjugation** | SULT1A/UGT | PAPS (sulfotransfer) / UDPGA | 6-sulphatoxymelatonin | Urinary biomarker (nighttime peak) |
| **Free-radical neutralisation** | Non-enzymatic | None | AFMK, AMK | Antioxidant cascade (each melatonin → 10+ ROS scavenged) |

---

## Cofactors and Nutritional Support — Summary

| Nutrient | Role | Effect of Deficiency |
|---|---|---|
| **L-Tryptophan** | Serotonin (and thus melatonin) precursor | Reduced substrate; low serotonin and melatonin |
| **Vitamin B6 (PLP)** | AADC cofactor (5-HTP → serotonin) | Reduced melatonin upstream |
| **Pantothenate (B5)** | Acetyl-CoA for AANAT (serotonin → NAS) | Reduced rate-limiting step |
| **SAM (Methionine + B12 + Folate + B2 + Mg²⁺)** | ASMT cofactor — methyl group transfer (NAS → melatonin) | NAS accumulates; melatonin reduced |
| **Vitamin B12 (methylcobalamin)** | SAM regeneration (ASMT) | Impaired melatonin methylation |
| **Folate (5-MTHF/B9)** | BH4 regeneration (TPH1) + SAM cycle | Upstream and methylation impairment |
| **Riboflavin (B2)** | FAD for BH4 synthesis; SAM cycle | Impairs TPH1 and ASMT indirectly |
| **Iron (Fe²⁺)** | TPH1 cofactor | Reduced 5-HTP production |
| **Magnesium** | No direct melatonin enzyme; binds to melatonin receptors; regulates ASMT cycle | Sleep complaints; low melatonin receptor sensitivity |
| **Zinc** | AADC activity | Reduced serotonin → melatonin |
| **Vitamin D** | Upregulates TPH1 expression in pineal | Low melatonin linked to vitamin D deficiency |

---

## Melatonin Receptors

| Receptor | Signalling | Location | Function |
|---|---|---|---|
| **MT1 (MTNR1A)** | Gi → cAMP ↓ | SCN, pituitary, peripheral tissues | Acute sleep signal; reproductive regulation |
| **MT2 (MTNR1B)** | Gi → cAMP ↓ | Retina, SCN | Phase shifting (circadian reset); type 2 diabetes association |
| **MT3** | NRH quinone oxidoreductase | Peripheral tissues | Physiological role unclear; may be quinone reductase |

---

## Melatonin as an Antioxidant

Melatonin is a potent free radical scavenger — via two mechanisms:
1. **Direct** — scavenges ·OH, ONOO⁻, H₂O₂ (no receptor required)
2. **Indirect** — ASMT metabolites (AFMK, AMK) continue scavenging downstream

> One melatonin molecule can neutralise up to **10 reactive oxygen species** through this cascade — far exceeding Vitamin C or E.

Additionally, melatonin upregulates antioxidant enzymes: SOD, GPx, GR, catalase.

---

## Clinical Relevance

| Condition | Melatonin Status | Notes |
|---|---|---|
| **Insomnia / delayed sleep phase** | Low or phase-shifted | Exogenous melatonin (0.5–5 mg) advances phase |
| **Jet lag** | Arrhythmic | Timed melatonin administration resets SCN |
| **Night shift workers** | Suppressed (light exposure) | Blackout environment + timed supplementation |
| **Autism spectrum disorder** | Low (some individuals) | ASMT mutations found in cohort studies |
| **Breast / prostate cancer** | Epidemiologically low | Night shift → suppressed melatonin → MT1 loss of oncostatic signalling |
| **Type 2 diabetes** | MT2 variant (MTNR1B rs10830963) | Associated with elevated fasting glucose |
| **Mitochondrial disorders** | Depleted | Oxidative stress consumes melatonin non-regeneratively |

---

## Drug Interactions

| Drug | Effect |
|---|---|
| **Fluvoxamine (SSRI)** | Potent CYP1A2 inhibitor → raises melatonin 10-fold |
| **Ramelteon / Tasimelteon** | MT1/MT2 agonists — approved for insomnia and non-24 disorder |
| **Agomelatine** | MT1/MT2 agonist + 5-HT2C antagonist — antidepressant |
| **Beta-blockers (propranolol)** | Block β1 adrenoceptors in pineal → suppress AANAT → reduce melatonin |
| **NSAIDs (aspirin, ibuprofen)** | PGE₂ inhibition → may reduce melatonin (mechanism unclear) |
| **Caffeine** | CYP1A2 competitor → may marginally raise melatonin |
| **Alcohol** | Suppresses melatonin secretion acutely; disrupts circadian rhythm |
| **Corticosteroids** | Suppress melatonin secretion |
