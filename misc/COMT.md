# COMT — Catechol-O-Methyltransferase

**COMT** is a Phase II biotransformation enzyme that **inactivates catecholamines and catechol-containing compounds** by transferring a methyl group (–CH₃) from **SAM (S-Adenosylmethionine)** onto the catechol ring. It is the primary route of catecholamine clearance in the **prefrontal cortex** and a key regulator of mood, motivation, pain, and stress response.

---

## 🔬 Biochemistry Overview

| Property | Detail |
|---|---|
| **Full name** | Catechol-O-Methyltransferase |
| **Gene** | *COMT* (chromosome 22q11.21) |
| **EC number** | EC 2.1.1.6 |
| **Reaction type** | O-methylation (methyl group transferred from SAM to catechol –OH) |
| **Cofactors required** | SAM (methyl donor), Mg²⁺ (structural/catalytic) |
| **Products of SAM consumption** | SAH (S-Adenosylhomocysteine) → Homocysteine |
| **Isoforms** | MB-COMT (membrane-bound, brain-dominant) · S-COMT (soluble, liver/kidney/erythrocytes) |
| **Location** | Neuronal cytoplasm & membranes; liver; adrenal gland; kidney |

---

## ⚙️ What COMT Methylates

COMT acts on any molecule with a **catechol ring** (two adjacent –OH groups on a benzene ring):

| Substrate | Product | Significance |
|---|---|---|
| **Dopamine (DA)** | 3-Methoxytyramine (3-MT) | Primary PFC clearance route |
| **Norepinephrine (NE)** | Normetanephrine (NMN) | Sympathetic downregulation |
| **Epinephrine (EPI)** | Metanephrine (MN) | Adrenal hormone clearance |
| **L-DOPA** | 3-O-Methyldopa | Reduces therapeutic L-DOPA availability |
| **2-Hydroxyestradiol (2-OHE2)** | 2-Methoxyestradiol | Detoxifies catechol-oestrogens; anti-cancer |
| **4-Hydroxyestradiol (4-OHE2)** | 4-Methoxyestradiol | Reduces genotoxic quinone formation |
| **Catechol drugs** | Methylated metabolites | e.g. catechin, isoproterenol, methyldopa |

> **Note:** COMT works in parallel with MAO. In the **periphery & liver**, MAO is dominant; in the **prefrontal cortex**, COMT is the primary catecholamine inactivator.

---

## 🧠 Dopamine Catabolism — Full Pathway

```
Dopamine
  │
  ├──► MAO-B ──► DOPAL (DOPALD)
  │                 │
  │                 └──► ALDH + NAD⁺ ──► DOPAC
  │                            │
  │                            └──► COMT + SAM, Mg²⁺ ──► HVA (homovanillic acid) [excreted in urine]
  │
  └──► COMT + SAM, Mg²⁺ ──► 3-Methoxytyramine (3-MT)
                                  │
                                  └──► MAO-B ──► MOPEGAL
                                                    │
                                                    └──► ALDH + NAD⁺ ──► HVA [excreted]
```

**HVA (Homovanillic Acid)** is the primary urinary end-product of dopamine metabolism.

---

## 🧬 Key SNPs

### Val158Met (rs4680) — The "Warrior / Worrier" SNP

This is one of the most studied pharmacogenomic variants:

| Genotype | Enzyme Activity | Prefrontal DA level | Phenotype |
|---|---|---|---|
| **Val/Val** | High (3–4× baseline) | Lower PFC dopamine | "Warrior" — better stress resilience, lower baseline cognition |
| **Val/Met** | Intermediate | Intermediate | Moderate profile |
| **Met/Met** | Low (~25–40% of Val/Val) | Higher PFC dopamine | "Worrier" — better baseline cognition, impaired stress response, ↑ pain sensitivity |

**Clinical implications:**
- **Met/Met** carriers: greater risk of anxiety, PTSD, fibromyalgia, opioid dependence, depression under stress. Higher dopamine allows better working memory in calm states.
- **Val/Val** carriers: more resilient to stress, but lower tonic dopamine → risk of impulse control issues, ADHD-like traits. Benefit more from dopamine-raising interventions.
- L-DOPA therapy in Parkinson's: **COMT inhibitors** (entacapone, tolcapone) are used to prevent peripheral L-DOPA degradation before it reaches the brain.

### Other Notable SNPs

| SNP | Effect |
|---|---|
| rs4633 | Linked to altered psychiatric risk |
| rs6269 | Affects expression levels |
| rs4818 | Alters mRNA stability and COMT activity |
| Haplotypes combining the above | Define "COMT haplotype" more precisely than Val158Met alone |

---

## 🧪 Cofactors & Nutritional Dependencies

COMT requires two essential inputs:

### 1. SAM (S-Adenosylmethionine) — Methyl Donor

SAM is depleted every time COMT runs (SAM → SAH). SAM supply depends on:

| Nutrient | Role | Deficiency Effect |
|---|---|---|
| **Methionine** (diet) | SAM precursor | ↓ SAM → impaired COMT |
| **Folate (5-MTHF / B9)** | Regenerates methionine via MTR | ↓ SAM |
| **Vitamin B12 (methylcobalamin)** | MTR cofactor | ↓ SAM |
| **Riboflavin (B2 / FAD)** | MTHFR cofactor (activates folate) | ↓ Active folate → ↓ SAM |
| **Betaine (TMG)** | Alternative methyl donor via BHMT | Spares SAM when folate/B12 low |
| **Choline** | Converted to betaine | Spares SAM |

### 2. Magnesium (Mg²⁺) — Structural Cofactor

Mg²⁺ is required in the **COMT active site** — it coordinates the SAM methyl transfer:

| Deficiency State | Effect on COMT |
|---|---|
| Low dietary Mg | ↓ COMT activity → elevated catecholamines |
| Stress (cortisol depletes Mg) | Chronic stress → chronic Mg loss → impaired COMT |
| Alcohol use | Mg wasting → ↓ COMT → catecholamine excess |

> **Combined deficiency**: Low SAM (from B12/folate deficiency) + Low Mg = severe COMT impairment even in Val/Val carriers.

---

## 🛡️ Oestrogen Detoxification Role

COMT methylates **catechol-oestrogens**, which are oxidised forms of oestrogen that can bind DNA and generate reactive quinones:

```
Oestradiol (E2)
  │
  ├──► CYP1A1/CYP3A4 → 2-OHE2 ──► COMT + SAM ──► 2-MeOE2 (protective, anti-angiogenic)
  │
  └──► CYP1B1 ──────────► 4-OHE2 ──► COMT + SAM ──► 4-MeOE2 (less reactive)
                               │
                        ↓ if COMT slow/low SAM
                               │
                               └──► 4-OHE2-o-quinones → DNA adducts → ↑ cancer risk
```

**COMT** is thus a **cancer-protective enzyme** particularly relevant in oestrogen-driven cancers (breast, endometrial). Met/Met carriers with low methylation nutrients are at elevated risk.

---

## 💊 Pharmacological Relevance

| Drug Class | Interaction with COMT |
|---|---|
| **COMT inhibitors** (entacapone, tolcapone) | Used in Parkinson's to extend L-DOPA half-life |
| **L-DOPA** | ~80% is methylated by peripheral COMT before reaching brain |
| **Catecholamine drugs** (dobutamine, isoprenaline) | Substrates for COMT; dosing affected by COMT activity |
| **Tolcapone** | Also inhibits hepatic COMT; risk of hepatotoxicity |
| **Methyldopa** | Antihypertensive; metabolised first by COMT |

---

## 🍽️ Dietary Modulators

| Food / Compound | Effect on COMT |
|---|---|
| **Green tea (EGCG)** | COMT inhibitor — raises catecholamine levels; slows oestrogen clearance |
| **Quercetin** | Weak COMT inhibitor |
| **Luteolin, fisetin** | Mild COMT inhibition |
| **Methionine-rich diet** (meat, eggs) | ↑ SAM → supports COMT |
| **Cruciferous vegetables** | ↑ Substrate (catechol-oestrogens) via CYP1B1 + protects via COMT support |
| **Magnesium-rich foods** | Supports COMT active site |

> **Practical note:** In Met/Met individuals (already low COMT activity), excessive EGCG (e.g. high-dose green tea extract) may worsen dopamine/oestrogen accumulation.

---

## 🧠 Mental Health & Neuroscience

| Condition | COMT Relevance |
|---|---|
| **Schizophrenia** | Val158Met strongly implicated; 22q11 deletion syndrome (COMT gene deleted) doubles schizophrenia risk |
| **ADHD** | Low COMT activity (Met/Met) + adequate DA → fewer ADHD symptoms; but stress worsens |
| **PTSD** | Met/Met → exaggerated fear extinction deficits; Val/Val more resilient |
| **Bipolar disorder** | COMT haplotypes linked to mood cycling |
| **Chronic pain / fibromyalgia** | Met/Met → elevated DA/NE → paradoxically lower μ-opioid receptor binding → ↑ pain |
| **OCD** | Val/Val associated (lower PFC DA → compulsive circuits more active) |
| **Anxiety** | Met/Met → higher PFC DA → rumination, worry, hypervigilance |

---

## ⚠️ Signs of High vs. Low COMT Activity

| COMT Activity | Downstream Effect | Clinical Pattern |
|---|---|---|
| **High (Val/Val)** | Rapid DA clearance in PFC | Low working memory, impulsivity, stress resilience, low anxiety baseline |
| **Low (Met/Met)** | Slow DA clearance in PFC | High working memory, anxiety, worry, pain sensitivity, poor stress resilience |
| **Combined with low SAM or Mg** | COMT further impaired | Elevated catecholamines, high BP, anxiety, insomnia |

---

## 📊 Clinical Testing

| Test | What It Shows |
|---|---|
| COMT Val158Met genotyping | Genetic activity level |
| Plasma/urine catecholamines | Functional output (DA, NE, EPI) |
| Urinary HVA, VMA, normetanephrine | Downstream metabolite ratios |
| Plasma homocysteine | SAM/methylation adequacy |
| SAM : SAH ratio | Direct methylation status |
| Serum/RBC magnesium | Cofactor availability |

---

## Summary

COMT is a methylation-dependent enzyme that inactivates **dopamine, norepinephrine, epinephrine, and catechol-oestrogens**. Its activity is genetically modulated by the **Val158Met SNP**, nutritionally dependent on **SAM (B12, folate, B2, methionine)** and **Magnesium**, and pharmacologically inhibited by **EGCG and COMT inhibitor drugs**. Optimising COMT function — through adequate methylation nutrients and Mg — is clinically relevant for mood disorders, pain, hormone balance, and neurodegenerative disease.
