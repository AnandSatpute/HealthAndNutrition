# Dopamine

## Overview

Dopamine is a catecholamine neurotransmitter serving as the chemical currency of **reward, motivation, movement, and executive function**. It is synthesised primarily in the **substantia nigra** (pars compacta, for motor control), **ventral tegmental area** (VTA, for reward and motivation), and the **hypothalamus** (for prolactin inhibition). Dopamine is also produced in the adrenal medulla as a precursor to norepinephrine, and in the gut and kidneys as a local paracrine signal.

> **Key insight** — Dopamine is not simply the "pleasure molecule." It encodes *reward prediction error* — the gap between expected and actual outcomes. It is critical for motivation to seek, not merely for pleasure upon receiving.

---

## Synthesis Pathway

```
L-Phenylalanine  (dietary essential)
      │
      │ [Phenylalanine hydroxylase — PAH]
      │  Cofactor: BH4 (tetrahydrobiopterin), Fe²⁺, O₂
      ▼
L-Tyrosine  (conditionally essential; also dietary)
      │
      │ [Tyrosine hydroxylase — TH]
      │  Cofactors: BH4, Fe²⁺, O₂, NADPH
      │  ⚠ Rate-limiting step for ALL catecholamines
      ▼
L-DOPA (L-3,4-dihydroxyphenylalanine)
      │
      │ [Aromatic L-amino acid decarboxylase — AADC / DOPA decarboxylase]
      │  Cofactor: Pyridoxal-5′-phosphate (PLP / Vitamin B6)
      ▼
Dopamine (DA)
      │
      ├──► Dopaminergic neurons: stored in vesicles → released
      │
      └──► Noradrenergic neurons:
           │ [Dopamine-β-hydroxylase — DBH]
           │  Cofactors: Vitamin C (ascorbate), Cu²⁺, O₂
           ▼
           Norepinephrine (→ Epinephrine)
```

### Step-by-Step Cofactor Requirements

| Step | Enzyme | Required Cofactors / Nutrients |
|---|---|---|
| **1. Phe → Tyrosine** | PAH | BH4, Fe²⁺, O₂, NADPH |
| **2. Tyrosine → L-DOPA** ⚠ | Tyrosine hydroxylase (TH) | **BH4**, **Fe²⁺**, O₂, NADPH; regulated by PKA (cAMP) |
| **3. L-DOPA → Dopamine** | AADC | **PLP (Vitamin B6)**, Zn²⁺ |
| **BH4 synthesis** | GTP cyclohydrolase I | **Folate (5-MTHF)**, **Riboflavin (FAD)** |
| **BH4 recycling** | DHPR | **NADPH**, **Vitamin C** (antioxidant) |

---

## BH4 — The Critical Gatekeeper

Tetrahydrobiopterin (BH4) is co-substrate for **both TH (dopamine)** and **TPH (serotonin)**. Low BH4 simultaneously collapses both pathways.

**Causes of low BH4:**
- Oxidative stress (BH4 is oxidised to BH2 and biopterin)
- Inflammation (cytokines suppress GCH1 — BH4 synthesis enzyme)
- Folate / B12 / riboflavin deficiency (impair BH4 regeneration)
- Genetic GCH1 mutations (Dopa-responsive dystonia)

**Consequences:** Simultaneous dopamine + serotonin deficiency → depression + movement disorder.

---

## Degradation Pathway

```
Dopamine
      │
      ├──► [MAO-A or MAO-B]          ├──► [COMT]
      │     Cofactor: FAD (B2)        │     Cofactor: SAM (needs B12/folate/B2/Mg)
      ▼                               ▼
3,4-Dihydroxyphenylacetaldehyde    3-Methoxytyramine (3-MT)
      │                               │
      │ [ALDH]   Cofactor: NAD⁺ (B3) │ [MAO-B]
      ▼                               ▼
3,4-Dihydroxyphenylacetic acid      Homovanillic acid (HVA)
(DOPAC)
      │
      │ [COMT] Cofactor: SAM
      ▼
Homovanillic acid (HVA)  ──► urine (primary urinary dopamine metabolite)
```

### Degradation Enzymes

| Enzyme | Location | Cofactor | Notes |
|---|---|---|---|
| **MAO-A** | Neurons, liver, gut | FAD (Riboflavin / B2) | Predominates in dopaminergic neurons |
| **MAO-B** | Platelets, glia, serotonin neurons | FAD (B2) | Major role in peripheral DA catabolism; target in Parkinson's |
| **COMT** | Postsynaptic neurons, liver, kidney | SAM → requires B12, folate, B2, Mg²⁺ | *COMT V158M* SNP (val/val = high activity, low DA; met/met = low activity, high DA) |
| **ALDH** | Cytosol/mitochondria | NAD⁺ (B3) | Converts aldehyde intermediate to acid |

---

## COMT Polymorphism (rs4680)

| Genotype | COMT Activity | Dopamine Level | Trait Tendency |
|---|---|---|---|
| Val/Val | High | Low (fast breakdown) | Better stress tolerance; lower working memory |
| Val/Met | Intermediate | Moderate | Balanced |
| Met/Met | Low | High (slow breakdown) | Better cognitive performance; higher anxiety/pain sensitivity |

> **Nutrient support for Met/Met:** Avoid excessive SAM supplementation (over-methylation). Magnesium and B2 are key for balancing COMT activity.

---

## Cofactors and Nutritional Support — Summary

| Nutrient | Role | Effect of Deficiency |
|---|---|---|
| **L-Tyrosine** | Immediate dopamine precursor | Reduced DA synthesis capacity |
| **L-Phenylalanine** | PAH → tyrosine (in phenylketonuria, PAH fails) | PKU causes dopamine deficiency |
| **Vitamin B6 (PLP)** | AADC — decarboxylation of L-DOPA → dopamine | Reduced conversion efficiency |
| **Iron (Fe²⁺)** | TH cofactor (rate-limiting step) | Impaired DA synthesis; RLS, ADHD, fatigue |
| **BH4** | TH cofactor | Severe DA deficiency |
| **Folate (5-MTHF / B9)** | BH4 regeneration + SAM for COMT | Dual hit: synthesis + degradation impaired |
| **Vitamin B12** | SAM maintenance (COMT/methylation) | COMT impairment; elevated catecholamine half-life |
| **Riboflavin (B2)** | FAD for MAO-A/B; BH4 synthesis | Dysregulated catabolism |
| **Vitamin C** | DBH cofactor; BH4 stabilisation | Reduced NE synthesis from DA |
| **Copper (Cu²⁺)** | DBH cofactor | Excess DA, low NE (Menkes disease extreme) |
| **Magnesium** | COMT function; downstream receptor signalling | COMT impairment |
| **Zinc** | AADC activity; D2 receptor modulation | Reduced decarboxylation |
| **Vitamin D** | Upregulates TH gene expression | Low DA synthesis linked to mood disorders |

---

## Dopamine Receptors

| Receptor | Signalling | Location | Function |
|---|---|---|---|
| **D1** | Gs → cAMP ↑ | Striatum, PFC, cortex | Reward, working memory, movement initiation |
| **D2** | Gi → cAMP ↓ | Striatum, limbic, pituitary | Autoreceptor (inhibits DA release); antipsychotic target |
| **D3** | Gi | Limbic | Reward, motivation; addiction pharmacology |
| **D4** | Gi | Cortex, limbic | Attention (ADHD association); novelty-seeking |
| **D5** | Gs | Hippocampus, hypothalamus | Memory; motor learning |

---

## Reuptake

After synaptic release, dopamine is recycled via:
- **DAT (dopamine transporter)** — primary reuptake in striatum, meso-limbic
- **NET (norepinephrine transporter)** — in prefrontal cortex (low DAT density)
- Vesicular repackaging by **VMAT2**, or
- Degradation by **MAO-B** (mitochondria) or **COMT** (cytosol/extrasynaptic)

---

## Clinical Relevance

| Condition | Dopamine Status | Mechanism |
|---|---|---|
| **Parkinson's disease** | Low (nigrostriatal) | Loss of substantia nigra dopaminergic neurons |
| **ADHD** | Low (PFC) | Impaired DAT + reduced prefrontal DA signalling |
| **Schizophrenia** | Excess (mesolimbic) + low (PFC) | Dopamine dysregulation hypothesis |
| **Addiction** | Phasic hyper-release → tonic depletion | Reward pathway sensitisation |
| **Restless Legs Syndrome** | Low (spinal cord) | Iron/BH4 deficiency depleting DA |
| **Hyperprolactinaemia** | Low (tuberoinfundibular) | DA normally inhibits prolactin; DA deficiency → elevated prolactin |

---

## Drug Interactions

| Drug | Effect |
|---|---|
| **L-DOPA** (levodopa) | Bypasses TH rate-limit; exogenous L-DOPA → dopamine |
| **Carbidopa** | Inhibits peripheral AADC — keeps L-DOPA in blood for CNS entry |
| **MAO-B inhibitors** (selegiline) | Block DA degradation → extend action |
| **COMT inhibitors** (entacapone) | Block peripheral COMT → extend L-DOPA bioavailability |
| **Antipsychotics** | D2 receptor antagonists |
| **Methylphenidate / Amphetamines** | Block DAT / reverse transport → increased synaptic DA |
| **Cocaine** | DAT blocker |
| **Tyramine (diet + MAOIs)** | Dietary tyramine (aged cheese) + MAOI → hypertensive crisis |
