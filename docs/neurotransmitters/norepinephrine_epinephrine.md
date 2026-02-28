# Norepinephrine & Epinephrine (Catecholamines)

## Overview

Norepinephrine (noradrenaline / NE) and epinephrine (adrenaline / EPI) are catecholamines synthesised sequentially from dopamine. They are the principal mediators of the **sympathetic nervous system (fight-or-flight)** and regulate arousal, focus, cardiovascular tone, blood glucose, and the stress response.

| | Norepinephrine | Epinephrine |
|---|---|---|
| **Primary site** | Locus coeruleus (CNS); adrenal medulla; sympathetic ganglia | Adrenal medulla (chromaffin cells, ~80% of output) |
| **CNS role** | Arousal, attention, fight-or-flight, mood | Peripheral stress response; some central (minor) |
| **Peripheral role** | Vasoconstriction, cardiac output | Bronchodilation, glycogenolysis, lipolysis |

---

## Synthesis Pathway

```
L-Tyrosine
      │
      │ [Tyrosine hydroxylase — TH]  ← rate-limiting for all catecholamines
      │  Cofactors: BH4, Fe²⁺, O₂, NADPH
      ▼
L-DOPA
      │
      │ [AADC / Dopa decarboxylase]
      │  Cofactor: PLP (Vitamin B6)
      ▼
Dopamine
      │
      │ [Dopamine-β-hydroxylase — DBH]  ← occurs inside vesicles
      │  Cofactors: Vitamin C (ascorbate), Cu²⁺, O₂
      │  ⚠ Key step: Vitamin C is consumed stoichiometrically
      ▼
Norepinephrine (NE)
      │
      │ [Phenylethanolamine N-methyltransferase — PNMT]
      │  Cofactor: SAM (S-adenosylmethionine)
      │  Only in adrenal medulla and a few CNS nuclei
      │  PNMT is induced by glucocorticoids (cortisol)
      ▼
Epinephrine (EPI)
```

### Step-by-Step Cofactor Requirements

| Step | Enzyme | Required Cofactors / Nutrients |
|---|---|---|
| **1. Tyrosine → L-DOPA** ⚠ | Tyrosine hydroxylase (TH) | BH4, Fe²⁺, O₂, NADPH *(see dopamine.md)* |
| **2. L-DOPA → Dopamine** | AADC | PLP (Vitamin B6), Zn²⁺ |
| **3. Dopamine → NE** | Dopamine-β-hydroxylase (DBH) | **Vitamin C (ascorbate)**, **Cu²⁺ (copper)**, O₂ |
| **4. NE → Epinephrine** | PNMT | **SAM** (needs methionine, B9, B12, B2, Mg²⁺) |
| **Cortisol induction of PNMT** | Adrenal cortex → medulla | Cortisol upregulates PNMT gene expression |

---

## DBH — Vitamin C Dependency

**Dopamine-β-hydroxylase (DBH)** is unique in requiring **ascorbate (Vitamin C)** as an actual electron donor — not just a cofactor. Each catalytic cycle oxidises ascorbate to semi-dehydroascorbate.

- DBH is located **inside synaptic vesicles** — ascorbate must be actively transported into chromaffin granules
- **Scurvy** (severe Vitamin C deficiency) substantially impairs NE synthesis → fatigue, hypotension, mood changes
- Ascorbate transport into vesicles is mediated by SVCT2 transporter
- **Copper** is the prosthetic metal at the DBH active site — copper deficiency impairs DBH regardless of ascorbate status

---

## PNMT — SAM and Cortisol Regulation

**Phenylethanolamine N-methyltransferase (PNMT)** transfers a methyl group from SAM onto norepinephrine:
- Exclusive to adrenal chromaffin cells and a small number of brain stem neurons
- Gene expression requires **glucocorticoid** (cortisol) signalling via a GRE (glucocorticoid response element)
- **Chronic stress** → sustained cortisol → PNMT upregulation → excess EPI synthesis → adrenal exhaustion if prolonged
- **SAM depletion** (B12/folate/B2/Mg deficiency) → impaired PNMT → reduced epinephrine

---

## Degradation Pathways

Both NE and EPI are degraded by the same enzymatic machinery:

```
Norepinephrine / Epinephrine
         │
    ┌────┴──────────┐
    │               │
[MAO-A]          [COMT]
 FAD (B2)         SAM (B12/folate/B2/Mg)
    │               │
3,4-dihydroxymandelic     Normetanephrine / Metanephrine
acid (DHMA)              (major plasma/urine metabolite)
    │               │
    └──── COMT ─────┘
              │
              ▼
    3-Methoxy-4-hydroxymandelic acid
    = Vanillylmandelic acid (VMA)  ──► urine
    (also called Normetanephrine/Metanephrine intermediate)

[Additional route via MHPG → in CNS]
Central NE → 3-Methoxy-4-hydroxyphenylglycol (MHPG) → urine/CSF
```

### Degradation Enzymes

| Enzyme | Action | Cofactor | Notes |
|---|---|---|---|
| **MAO-A** | Oxidises NE/EPI to aldehyde | FAD (B2) | Primary neuronal route |
| **COMT** | O-methylation | SAM (B12/folate/B2/Mg) | Primary extraneuronal/hepatic route |
| **ALDH** | Aldehyde → acid | NAD⁺ (B3) | Converts DHMA; also handles acetaldehyde |

**Urine biomarkers:**
- **VMA** (vanillylmandelic acid) — elevated in pheochromocytoma
- **Normetanephrine / Metanephrine** — highly sensitive for pheo
- **MHPG** — central NE catabolism marker (low in depression correlating with NE deficiency)

---

## Cofactors and Nutritional Support — Summary

| Nutrient | Role | Effect of Deficiency |
|---|---|---|
| **L-Tyrosine** | Dopamine (and thus NE/EPI) precursor | Reduced catecholamine synthesis under stress |
| **Vitamin C (Ascorbate)** | DBH electron donor (dopamine → NE) | Impaired NE synthesis; fatigue, hypotension |
| **Copper (Cu²⁺)** | DBH active site metal | Impaired NE synthesis (Menkes disease) |
| **Vitamin B6 (PLP)** | AADC cofactor (L-DOPA → DA) | Reduced dopamine for NE synthesis |
| **Iron (Fe²⁺)** | TH cofactor (rate-limiting) | Rate-limited synthesis |
| **BH4** | TH cofactor | Collapse of all catecholamine synthesis |
| **Folate (5-MTHF)** | BH4 regeneration + SAM (PNMT) | Dual impairment |
| **Vitamin B12** | SAM maintenance | PNMT impaired; catecholamine methylation reduced |
| **Riboflavin (B2)** | FAD for MAO-A; BH4 synthesis | Dysregulated catabolism |
| **Magnesium** | COMT function; adrenal regulation | Exaggerated catecholamine half-life |
| **Pantothenate (B5)** | Acetyl-CoA → adrenal steroid synthesis (cortisol induces PNMT) | Indirect impairment of EPI |
| **Vitamin D** | Regulates TH and catecholamine pathway gene expression | Reduced catecholamine synthesis |
| **Zinc** | AADC activity; adrenal function | Indirectly reduces DA substrate |

---

## Norepinephrine Reuptake

- **NET (norepinephrine transporter)** is the primary reuptake mechanism
- NET is expressed densely in sympathetic nerve terminals and locus coeruleus neurons
- In PFC, NET also clears dopamine (low DAT density → NET is primary dopamine transporter here)
- **SNRIs** (venlafaxine, duloxetine) and **TCAs** block NET → raised synaptic NE
- **Atomoxetine** (ADHD) is a selective NET inhibitor

---

## Adrenoceptors

| Receptor | Signalling | Location | Function |
|---|---|---|---|
| **α1** | Gq → IP₃ | Vasculature, iris | Vasoconstriction, pupil dilation |
| **α2** | Gi → cAMP ↓ | Presynaptic (autoreceptor), PFC | Inhibits NE release; PFC attention |
| **β1** | Gs → cAMP ↑ | Heart | Increased heart rate and contractility |
| **β2** | Gs → cAMP ↑ | Bronchioles, skeletal muscle vasculature | Bronchodilation, vasodilation |
| **β3** | Gs | Adipocytes | Lipolysis |

---

## Clinical Relevance

| Condition | NE/EPI Status | Mechanism |
|---|---|---|
| **Depression** | Low NE (noradrenergic deficiency) | Reduced locus coeruleus output; fatigue, anhedonia |
| **ADHD** | Low NE in PFC | Impaired α2A-adrenergic signalling → poor attention |
| **PTSD** | Chronic NE excess | Hyperactivated locus coeruleus; amygdala hyperreactivity |
| **Pheochromocytoma** | Massive NE/EPI excess | Adrenal tumour; hypertensive crisis |
| **Orthostatic hypotension** | Insufficient NE | Impaired vasoconstriction on standing (e.g., DBH deficiency) |
| **Heart failure** | Chronic NE excess | Cardiac remodelling; β1 downregulation |

---

## Drug Interactions

| Drug | Effect |
|---|---|
| **SNRIs** (venlafaxine, duloxetine) | NET blocker → increased synaptic NE |
| **TCAs** (amitriptyline, nortriptyline) | NET + SERT blocker |
| **Atomoxetine** | Selective NET inhibitor (ADHD) |
| **Guanfacine / Clonidine** | α2A agonist → reduced NE release; ADHD/PTSD |
| **Propranolol** | β-blocker → reduces cardiovascular NE effects |
| **Phentolamine** | α-blocker; used in pheo hypertensive crisis |
| **Cocaine / Amphetamines** | NET blocker / reverse transport |
| **MAOIs** | Prevent NE degradation → excess accumulation |
| **Tyramine (cheese effect)** | Tyramine displaces NE from vesicles; dangerous with MAOIs |
