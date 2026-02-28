# GABA (Gamma-Aminobutyric Acid)

## Overview

GABA is the **primary inhibitory neurotransmitter** in the mammalian central nervous system. It counterbalances glutamate (the principal excitatory transmitter), regulating neuronal excitability throughout the brain and spinal cord. GABA mediates anxiolysis, sedation, anticonvulsant effects, and muscle relaxation. Approximately **30–40% of all synapses** in the brain are GABAergic.

> **Key insight** — GABA cannot cross the blood-brain barrier in meaningful quantities. Oral GABA supplementation has limited direct CNS impact unless the gut-brain axis or very specific transport mechanisms are involved. Precursor and cofactor support (glutamate + B6) is physiologically more relevant.

---

## Synthesis Pathway

```
Glucose  →  Krebs cycle
                │
                ▼
         α-Ketoglutarate
                │
          [Transamination]
                ▼
         L-Glutamate  ←── also from dietary glutamine via GLS
                │
                │ [Glutamic acid decarboxylase — GAD65 / GAD67]
                │  Cofactor: Pyridoxal-5′-phosphate (PLP / Vitamin B6)
                │  ⚠ Rate-limiting step
                │  Zn²⁺ enhances GAD stability
                ▼
         GABA
                │
                ├──► Stored in vesicles → released synaptically
                │
                └──► GABA shunt (see below)
```

### Step-by-Step Cofactor Requirements

| Step | Enzyme | Required Cofactors / Nutrients |
|---|---|---|
| **Glucose → α-KG** | Krebs cycle (multiple enzymes) | Thiamine (B1), Riboflavin (B2), Niacin (B3), Lipoic acid, Mg²⁺, Mn²⁺ |
| **α-KG → Glutamate** | GABA-T (reverse) / Aminotransferases | PLP (B6), Zn²⁺ |
| **Glutamate → GABA** ⚠ | GAD65 / GAD67 | **PLP (Vitamin B6)**, **Zn²⁺**, adequate glutamate substrate |
| **Glutamine → Glutamate** (glial supply) | Glutaminase (GLS) | — (Pi-activated) |

---

## The GABA Shunt (GABA–Krebs Cycle Link)

The GABA shunt is a metabolic bypass through which GABA re-enters the Krebs cycle:

```
GABA
  │
  │ [GABA-T — GABA transaminase]
  │  Cofactor: PLP (Vitamin B6)
  │  (Zn²⁺ activates; Mg²⁺ stabilises)
  ▼
Succinic semialdehyde (SSA)
  │
  │ [SSADH — succinic semialdehyde dehydrogenase]
  │  Cofactor: NAD⁺ (Niacin / B3)
  ▼
Succinate  →  Krebs cycle (succinyl-CoA → ATP)
```

> The shunt ensures GABA is not purely wasted — it feeds ~8–10% of Krebs cycle flux in the brain.

---

## Glutamate–Glutamine Cycle (Astrocyte–Neuron)

GABA synthesis depends on a continuous astrocytic glutamate supply:

```
Glutamatergic neuron releases glutamate → astrocyte uptake
Astrocyte: Glutamate →[GS]→ Glutamine  (GS cofactor: Mg²⁺, ATP)
Glutamine released → taken up by GABAergic neuron
Neuron: Glutamine →[GLS]→ Glutamate  → [GAD + B6] → GABA
```

---

## Degradation / Catabolism

```
GABA (synaptic)
      │
      │ Reuptake via GAT-1/3 (GABA transporters)
      ▼
Presynaptic terminal or astrocyte
      │
      │ [GABA-T]  Cofactor: PLP (B6)
      ▼
Succinic semialdehyde
      │
      │ [SSADH]  Cofactor: NAD⁺ (B3)
      ▼
Succinate → Krebs cycle
```

| Enzyme | Location | Cofactor | Inhibited By |
|---|---|---|---|
| **GABA-T** | Mitochondria (neurons + astrocytes) | PLP (B6) | **Vigabatrin** (anticonvulsant — irreversible GABA-T inhibitor) |
| **SSADH** | Mitochondria | NAD⁺ (B3) | GHB (endogenous/exogenous) competes |

---

## Cofactors and Nutritional Support — Summary

| Nutrient | Role | Effect of Deficiency |
|---|---|---|
| **Vitamin B6 (PLP)** | GAD cofactor (glutamate → GABA); GABA-T (catabolism) | Low GABA → anxiety, seizures; B6 deficiency seizures in infants |
| **Zinc** | Enhances GAD isoform stability; modulates GABA-A receptor | Reduced GABA synthesis; anxiety |
| **Magnesium** | GABA-A receptor allosteric modulation; GS cofactor for glutamine | Hypomagnesaemia → anxiety, muscle spasms |
| **Thiamine (B1)** | ATP production for Krebs cycle → glutamate supply | Reduced GABA substrate |
| **Niacin (B3)** | NAD⁺ for SSADH (GABA catabolism); Krebs cycle | Dysregulated GABA turnover |
| **Glutamate (glutamine)** | Direct GABA precursor | Substrate limitation |
| **Taurine** | GABA-A receptor agonist; inhibitory co-transmitter | Reduced inhibitory tone |
| **L-Theanine** | Increases GABA and reduces glutamate signalling | N/A (supplemental) |

---

## GABA Receptors

| Receptor | Type | Mechanism | Key Features |
|---|---|---|---|
| **GABA-A** | Ligand-gated Cl⁻ channel (ionotropic) | Increases Cl⁻ influx → hyperpolarisation | Benzodiazepine site; alcohol; barbiturate site; neurosteroid site |
| **GABA-B** | Gi-coupled GPCR (metabotropic) | Decreases cAMP; opens K⁺ channels | Baclofen target; pre- and post-synaptic |
| **GABA-C** (now GABA-A ρ) | Cl⁻ channel | Similar to GABA-A; slower kinetics | Retinal cells |

**Key allosteric modulators of GABA-A:**
- **Benzodiazepines** — increase frequency of Cl⁻ channel opening (anxiolytic, sedative)
- **Barbiturates** — increase duration of channel opening (anticonvulsant)
- **Alcohol (ethanol)** — positive modulator of GABA-A (also inhibits NMDA)
- **Neurosteroids** (allopregnanolone, THDOC) — endogenous ligands; fluctuate with menstrual cycle, stress, and pregnancy
- **Magnesium** — modulates receptor sensitivity

---

## Clinical Relevance

| Condition | GABA Status | Mechanism |
|---|---|---|
| **Epilepsy** | Low GABA | GAD deficiency; GABA-T excess; channelopathies |
| **Anxiety disorders** | Low GABA tone | Reduced GAD67 expression; chronic stress |
| **PTSD** | Low GABA (amygdala) | HPA activation depletes GABA; BZ receptor downregulation |
| **Alcohol use disorder** | GABA-A tolerance | Chronic alcohol → GABA-A downregulation → withdrawal seizures |
| **SSADH deficiency** | Elevated GABA | Rare metabolic disorder (NAD+ enzyme failure) |
| **Huntington's disease** | Loss of GABAergic striatal neurons | Disinhibition of thalamus → choreiform movements |

---

## Drug Interactions

| Drug | Effect |
|---|---|
| **Benzodiazepines** (diazepam, lorazepam) | Positive GABA-A modulator — potentiate Cl⁻ influx |
| **Barbiturates** (phenobarbitone) | GABA-A positive allosteric modulator — higher abuse risk |
| **Vigabatrin** | Irreversible GABA-T inhibitor → raises brain GABA |
| **Baclofen** | GABA-B agonist — muscle relaxant, alcohol craving reduction |
| **Sodium valproate** | GABA-T inhibitor + GAD activator + Na⁺ channel block |
| **Gabapentin / Pregabalin** | Bind α2δ subunit of voltage-gated Ca²⁺ channels; reduce glutamate (indirect GABA enhancement) |
| **Alcohol** | GABA-A agonist + NMDA antagonist (acute); reverse on withdrawal |
| **Flumazenil** | Benzodiazepine receptor antagonist (reversal agent) |
