# Kynurenine Pathway

## Overview

Under normal conditions, dietary tryptophan feeds primarily into **serotonin and melatonin synthesis**. However, in the presence of inflammation, the kynurenine pathway **competitively diverts up to 95% of tryptophan** away from serotonin — producing neuroactive and neurotoxic metabolites that directly modulate mood, cognition, and neurodegeneration.

The kynurenine pathway is the **biochemical bridge between inflammation and depression**.

> **Key insight** — Depression in the context of chronic illness, autoimmune disease, or post-infection is often *not* a serotonin deficiency per se, but a *tryptophan diversion* problem: inflammation has shunted tryptophan into the kynurenine pathway, starving serotonin synthesis while simultaneously generating neurotoxic quinolinic acid.

---

## Pathway Overview

```
Dietary Tryptophan (Trp)
         │
         ├──► [TPH1/2]  →  Serotonin → Melatonin        ← Normal route (~1–5% Trp)
         │
         └──► [IDO / TDO]  ← INFLAMED route (~95% Trp under inflammation)
                  │
                  ▼
            Kynurenine (KYN)
                  │
       ┌──────────┼──────────────────────┐
       │          │                      │
       ▼          ▼                      ▼
 [KAT I–IV]  [KMO]                  [KMO blocked]
 + Vit B6     + FAD (B2)
       │          │                      │
       ▼          ▼                      ▼
 Kynurenic    3-Hydroxykynurenine   Anthranilic Acid
  Acid (KA)        │
(neuroprotective)  │ [HAAO]
                   │  + Fe²⁺
                   ▼
            3-Hydroxyanthranilic Acid (3-HAA)
                   │
                   │ [ACMSD]  ← can divert away from neurotoxic route
                   ▼
           Quinolinic Acid (QUIN)  ← NEUROTOXIC
                   │
                   │ [QPRT]
                   ▼
              NAD⁺  ← end product
```

---

## Key Enzymes

### IDO (Indoleamine 2,3-Dioxygenase) — The Inflammation Gate

IDO is the **primary rate-limiting enzyme** of the kynurenine pathway. It is expressed in:
- Dendritic cells and macrophages (strongly)
- Microglia (brain immune cells)
- Liver (minor role, TDO predominates here)
- Placenta, tumour cells

**IDO is powerfully induced by:**

| Inducer | Source |
|---|---|
| **Interferon-gamma (IFN-γ)** | T cells, NK cells — THE primary IDO inducer |
| **LPS (lipopolysaccharide)** | Gram-negative bacteria / gut permeability |
| **TNF-α** | Macrophages |
| **IL-6** | Broad inflammatory states |
| **Cortisol** | Stress (via HPA axis) |
| **Reactive oxygen species** | Oxidative stress conditions |

### TDO (Tryptophan 2,3-Dioxygenase) — The Hepatic Gate

TDO is constitutively expressed in the **liver** and is the dominant enzyme for tryptophan catabolism under non-inflammatory conditions. It is induced by:
- Tryptophan itself (substrate induction)
- Glucocorticoids (cortisol) — stress further potentiates tryptophan diversion via TDO

---

## Neuroactive Metabolites — The Kynurenine Balance

The pathway branches into **neuroprotective** and **neurotoxic** arms. The balance between these arms determines neurological outcome.

| Metabolite | Effect | NMDA Receptor | Produced by |
|---|---|---|---|
| **Kynurenic Acid (KA)** | NEUROPROTECTIVE | Antagonist (blocks) | Astrocytes (via KAT) |
| **Quinolinic Acid (QUIN)** | NEUROTOXIC | Agonist (activates) | Microglia, macrophages |
| **3-Hydroxykynurenine (3-HK)** | PRO-OXIDANT | — | Macrophages (KMO) |
| **Picolinic Acid** | Mildly neuroprotective | Chelates Zn, inhibits QUIN | Peripheral tissues |
| **NAD⁺** | Mitochondrial co-enzyme | — | All tissues (via QPRT) |

### The Kynurenic Acid / Quinolinic Acid Ratio

This ratio is a critical clinical marker:
- **High KA / low QUIN** → neuroprotective state (astrocyte-dominant)
- **Low KA / high QUIN** → neurotoxic state (microglia-dominant) = seen in depression, Alzheimer's, HIV encephalopathy

---

## Quinolinic Acid — Mechanism of Neurotoxicity

Quinolinic acid (QUIN) is an **endogenous NMDA receptor agonist** and the principal neurotoxin of the kynurenine pathway.

### Mechanisms of QUIN Toxicity

```
QUIN
  │
  ├──► NMDA receptor over-activation → Ca²⁺ influx
  │         │
  │         ├──► Mitochondrial dysfunction (cytochrome c release)
  │         ├──► ROS generation (nitric oxide via nNOS)
  │         └──► Excitotoxic neuronal death
  │
  ├──► Glutamate transporter inhibition → Glutamate accumulates → Compound excitotoxicity
  │
  ├──► Oxidative stress → lipid peroxidation, DNA damage
  │
  ├──► Inhibits complex II and III of ETC (mitochondrial impairment)
  │
  └──► Suppresses BDNF → impairs hippocampal neuroplasticity
```

**Brain regions most vulnerable:**
- Hippocampus (CA1, CA3) — memory
- Striatum — movement, reward
- Cortex — cognition, executive function

---

## The Inflammation → Depression Link

The kynurenine pathway explains the **cytokine-induced depression** model (also called the inflammatory sickness model of depression):

```
Infection / Chronic illness / Gut dysbiosis / Autoimmune disease
       │
       ▼
Elevated IFN-γ, IL-6, TNF-α, LPS
       │
       ▼
IDO induction in brain MICROGLIA
       │
       ├──► Tryptophan diverted → Serotonin ↓ → Melatonin ↓
       │
       ├──► QUIN ↑ → NMDA excitotoxicity → Hippocampal damage
       │
       ├──► BDNF ↓ → Reduced neuroplasticity
       │
       └──► KA ↓ (KMO > KAT) → Loss of neuroprotective buffer
               │
               ▼
           Depression / Cognitive impairment / Psychosis risk
```

This model explains:
- Depression associated with cancer, HIV, multiple sclerosis, and post-COVID
- Elevated QUIN in CSF of suicidal patients
- Why SSRIs (which purely raise serotonin) fail in inflammatory depression
- Why anti-inflammatory interventions (omega-3, curcumin, low-dose naltrexone) show antidepressant effects

---

## Cofactor Requirements Along the Pathway

| Enzyme | Cofactor Required | Deficiency Effect |
|---|---|---|
| **TPH1/2** (Trp → 5-HTP) | BH4, Fe²⁺, O₂ | ↓ Serotonin synthesis |
| **IDO** | Fe²⁺ (haem), O₂ | IDO is less active when Fe²⁺ limited — may limit kynurenine production |
| **KMO** (Kyn → 3-HK) | FAD (Riboflavin / B2) | B2 deficiency → KYN accumulates or shunts to KA → neuroprotective shift |
| **KAT I/II/III/IV** (Kyn → KA) | **PLP (Vitamin B6)** | B6 deficiency → KA impaired → reduced neuroprotection |
| **HAAO** (3-HK → 3-HAA) | **Fe²⁺** | — |
| **QPRT** (QUIN → NAD⁺) | **Mg²⁺**, Phosphoribosyl-PP | Reduced when cellular NAD⁺ demand exceeds QPRT; QUIN builds up |

### Nutritional Implication
> **Vitamin B6 (PLP)** is critical for the KAT branch (neuroprotective arm). B6 deficiency blunts kynurenic acid production, shifting the balance toward quinolinic acid toxicity.

---

## Nutritional Modulation of the Kynurenine Pathway

| Nutrient / Compound | Effect on Pathway | Mechanism |
|---|---|---|
| **Omega-3 (EPA especially)** | ↓ IDO induction | Reduces IFN-γ, IL-6, TNF-α; reduces NF-κB → less IDO transcription |
| **Vitamin B6 (PLP)** | ↑ KA production (neuroprotective) | KAT cofactor; improves kyn → KA ratio |
| **Vitamin B3 (Niacin / Nicotinamide)** | Reduces IDO activity (via NAD⁺ feedback) | Niacin supplies NAD⁺ independently → reduces metabolic pressure on QPRT path |
| **Curcumin** | ↓ IDO expression; ↓ NF-κB | Anti-inflammatory; also chelates Fe (reduces IDO haem availability as secondary effect) |
| **Resveratrol** | ↓ IDO; ↓ SIRT1-mediated kynurenine flux | SIRT1 pathway, reduces TDO under liver stress |
| **Tryptophan restriction** | ↓ TDO activity (substrate withdrawal) | Exploited in tumour immunology |
| **Melatonin** | ↓ IDO induction; direct ROS quenching | Anti-inflammatory; also has scavenging effect on QUIN-generated ROS |
| **NAC (N-Acetylcysteine)** | Reduces QUIN-driven oxidative stress | Glutathione precursor; direct ROS scavenging |
| **Zinc** | Competes with QUIN at NMDA site (picolinic acid chelates Zn — supplementing Zn counteracts) | Reduces QUIN-driven excitotoxicity |
| **Magnesium** | NMDA receptor Mg²⁺ block → reduces QUIN's excitotoxic access | Voltage-dependent NMDA block |

---

## NAD⁺ Production via the Kynurenine Pathway

The kynurenine pathway is the **de novo route for NAD⁺ synthesis** in humans. This has significant implications:

- Under high IDO activity (chronic inflammation): QUIN → NAD⁺ via QPRT is the primary NAD⁺ source
- Niacin (vitamin B3) provides the **salvage pathway** — maintaining NAD⁺ without requiring tryptophan flux through QUIN
- NMN and NR (NAD⁺ precursors) similarly bypass QUIN toxicity

> **Clinical pearl:** In conditions with chronic inflammation (HIV, lupus, IBD), NAD⁺ supplementation (niacin, NMN, NR) may serve the dual role of restoring NAD⁺ AND reducing pressure on the QUIN arm of the kynurenine pathway.

---

## Clinical Relevance

| Condition | Kynurenine Pathway Status | Clinical Implication |
|---|---|---|
| **Major Depression (inflammatory subtype)** | ↑ IDO, ↑ QUIN, ↓ KA, ↓ serotonin | IDO inhibitors (experimental); omega-3; B6; anti-inflammatory diet |
| **Schizophrenia** | ↑ KA (over-blocks NMDA → negative symptoms) | High KA = NMDA hypofunction; KMO inhibitors investigated |
| **Alzheimer's disease** | ↑ QUIN in plaques; IDO active in microglia | Tryptophan → QUIN may contribute to Aβ-associated neurodegeneration |
| **Post-COVID (neurological)** | ↑ IDO (IFN-γ surge); ↓ tryptophan; ↑ kynurenine | Explains fatigue, cognitive fog; omega-3 + B6 + NAD⁺ support |
| **Cancer (tumour immune evasion)** | Tumours express IDO to deplete Trp in tumour microenvironment → suppresses T cells | IDO1 inhibitors (epacadostat etc.) in clinical trials |
| **HIV encephalopathy** | Elevated QUIN in CSF | QUIN from activated macrophages drives CNS damage |
| **Sepsis** | Massive IDO induction → tryptophan collapse | Nutritional tryptophan matters; reduces serotonergic depression post-sepsis |
| **IBD / Gut dysbiosis** | Gut IDO1 activation; LPS → systemic IDO | Probiotic restoration reduces LPS → reduces IDO → improves kynurenine balance |
