# Histamine

## Overview

Histamine is a biogenic amine derived from **L-histidine** via a single decarboxylation step. It functions as a **neurotransmitter** in the CNS (wakefulness, attention, feeding), a **peripheral hormone/mediator** in immune responses (allergy, anaphylaxis), and a **paracrine signal** in the gastric mucosa (acid secretion). The CNS histaminergic system originates almost exclusively from the **tuberomammillary nucleus (TMN)** of the posterior hypothalamus.

> **Key insight** — Histamine has two separate degradation enzymes: **HNMT** (intracellular, CNS) and **DAO** (extracellular, gut/plasma). DAO is the critical first line of defence against dietary histamine. DAO is nutritionally sensitive — it requires B6, copper, B12, and folate for optimal activity.

---

## Synthesis Pathway

```
L-Histidine  (dietary; also from muscle protein turnover)
      │
      │ [L-Histidine Decarboxylase — HDC]
      │  Cofactor: Pyridoxal-5′-phosphate (PLP / Vitamin B6)
      │  ⚠ Rate-limiting step (product inhibition by histamine itself)
      │  Expressed in: mast cells, basophils, enterochromaffin-like (ECL) cells, TMN neurons
      ▼
Histamine
      │
      ├──► CNS: released from TMN neurons → wakefulness, attention
      ├──► Mast cells / Basophils: stored in granules → released in allergy/injury
      └──► Gastric ECL cells: released → stimulates parietal cell H2 receptor → HCl secretion
```

### Cofactor Requirements

| Step | Enzyme | Required Cofactors / Nutrients |
|---|---|---|
| **Histidine → Histamine** ⚠ | HDC | **PLP (Vitamin B6)**, L-Histidine substrate |
| **Bacterial HDC (gut)** | Bacterial HDC | B6 (from microbiome environment) — Lactobacillus, Clostridium species |

---

## Degradation Pathways

Histamine is degraded by **two distinct pathways** depending on tissue location:

### Pathway 1: HNMT (Histamine N-Methyltransferase) — CNS and Intracellular

```
Histamine (intracellular / CNS)
      │
      │ [HNMT — Histamine N-methyltransferase]
      │  Cofactor: SAM (S-adenosylmethionine)
      │           → requires B12, Folate (5-MTHF), Riboflavin (B2), Mg²⁺
      ▼
N-Methylhistamine
      │
      │ [MAO-B]  Cofactor: FAD (Riboflavin / B2)
      ▼
Methyl-imidazoleacetic acid  →  urine
```

### Pathway 2: DAO (Diamine Oxidase) — Gut and Plasma

```
Histamine (extracellular / gut lumen / plasma)
      │
      │ [DAO — Diamine Oxidase / AOC1]
      │  Cofactors: Cu²⁺ (copper), PLP (B6)
      │  Post-translational: requires topaquinone (TPQ) — derived from Cu²⁺ + tyrosine
      │  Inhibited by: alcohol, metformin, certain drugs
      ▼
Imidazole acetaldehyde
      │
      │ [ALDH]  Cofactor: NAD⁺ (Niacin / B3)
      ▼
Imidazoleacetic acid  →  urine
```

### Degradation Summary

| Enzyme | Location | Cofactors | Clinically inhibited by |
|---|---|---|---|
| **HNMT** | CNS neurons, lung, liver, kidneys | SAM (B12, folate, B2, Mg²⁺) | SKF 91488 (research); SAM depletion |
| **DAO** (AOC1) | Intestinal epithelium, placenta, kidney | Cu²⁺, PLP (B6), NAD⁺ (B3) | Alcohol, isoniazid, metformin, verapamil, histamine blockers |
| **MAO-B** | Glia, platelets | FAD (B2) | Selegiline, rasagiline |

---

## Histamine Intolerance

Histamine intolerance arises when dietary histamine accumulation exceeds the body's ability to degrade it (primarily via DAO):

**Causes of reduced DAO activity:**
- Genetic variants in AOC1 gene (reduced DAO expression)
- **Alcohol** (competitive DAO inhibitor)
- **Copper deficiency** (DAO active site Cu²⁺)
- **Vitamin B6 deficiency** (DAO cofactor)
- **Folate / B12 deficiency** (indirect — HNMT pathway impaired)
- Gut inflammation (IBD, celiac) — damages DAO-expressing enterocytes
- Certain drugs (isoniazid, metformin, some ACE inhibitors)

**Symptoms of histamine intolerance:** headache, flushing, hives, nasal congestion, GI cramping, tachycardia, hypotension

**High-histamine foods:** fermented foods (wine, cheese, sauerkraut, soy sauce, vinegar), tinned fish, aged meat, spinach, tomatoes, alcohol

---

## Cofactors and Nutritional Support — Summary

| Nutrient | Role | Effect of Deficiency |
|---|---|---|
| **Vitamin B6 (PLP)** | HDC cofactor (histamine synthesis); DAO cofactor (degradation) | Dual: reduces synthesis AND degradation capacity |
| **Copper (Cu²⁺)** | DAO active site (TPQ formation and catalysis) | Severely impaired DAO → histamine intolerance |
| **SAM (B12 + Folate + B2 + Mg²⁺)** | HNMT cofactor (CNS and systemic methylation) | Impaired CNS histamine clearance |
| **Riboflavin (B2)** | FAD for MAO-B (downstream N-methylhistamine catabolism); BH4/SAM pathway | Reduced histamine degradation |
| **Niacin (B3) / NAD⁺** | ALDH (imidazole acetaldehyde → acid) | Minor impairment of terminal step |
| **Zinc** | Supports DAO enzyme stability | Reduced DAO activity |
| **Vitamin C** | Upregulates DAO activity (anti-inflammatory); reduces mast cell degranulation | Increased mast cell reactivity and lower DAO |

---

## Histamine Receptors

| Receptor | Signalling | Location | Function |
|---|---|---|---|
| **H1** | Gq → PLC → IP₃/DAG | Smooth muscle, endothelium, CNS | Bronchoconstriction; itch; wakefulness; allergy |
| **H2** | Gs → cAMP ↑ | Gastric parietal cells, heart | Gastric acid secretion; positive chronotropy |
| **H3** | Gi (autoreceptor) | CNS (presynaptic) | Inhibits histamine release; modulates DA, ACh, 5-HT |
| **H4** | Gi | Mast cells, eosinophils, gut | Immune cell chemotaxis; gut inflammation |

---

## Clinical Relevance

| Condition | Histamine Status | Mechanism |
|---|---|---|
| **Allergic rhinitis / Asthma** | Elevated (mast cell release) | IgE-mediated mast cell degranulation |
| **Anaphylaxis** | Massively elevated | Systemic mast cell + basophil degranulation |
| **Carcinoid / ECL tumour** | Elevated (persistent) | Tumour histidine decarboxylase overexpression |
| **Histamine intolerance** | Relative elevation | DAO insufficiency (see above) |
| **Narcolepsy** | Low CNS histamine | TMN neuronal loss; hypocretin/orexin system failure → H1 recruitment lost |
| **Peptic ulcer disease** | H2 stimulation excess | H. pylori → gastrin → ECL → histamine → acid hypersecretion |
| **Mastocytosis** | Chronic excess | Clonal mast cell proliferation |

---

## Drug Interactions

| Drug | Mechanism |
|---|---|
| **H1 antihistamines** (loratadine, cetirizine, diphenhydramine) | H1 receptor antagonists — allergy treatment |
| **H2 blockers** (ranitidine, famotidine) | H2 antagonists — acid suppression |
| **MAOI drugs** | Block MAO-B → impair N-methylhistamine catabolism |
| **Alcohol** | Inhibits DAO; promotes mast cell degranulation |
| **Isoniazid (TB drug)** | DAO inhibitor + HDC inhibitor — histamine toxicity (scombroid fish risk) |
| **Metformin** | Weak DAO inhibitor |
| **Proton pump inhibitors** | Indirect: reduce acid-suppressed bacterial histamine production |
