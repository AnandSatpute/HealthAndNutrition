# Glutamate

## Overview

Glutamate is the **primary excitatory neurotransmitter** in the mammalian CNS, involved in the majority of fast excitatory synaptic transmission. It is not only a neurotransmitter but also a central metabolite — participating in the Krebs cycle, amino acid transamination, and as the direct precursor to **GABA** and **glutathione**. Far from being a simple "one-way" stimulant, glutamate signalling follows a carefully regulated astrocyte–neuron recycling cycle.

> **Key insight** — Glutamate excess (excitotoxicity) kills neurons via NMDA receptor-mediated calcium overload and mitochondrial failure. Zinc and magnesium are critical physiological blockers of the NMDA receptor channel pore. Nutritional deficits in these minerals increase vulnerability to excitotoxic damage.

---

## Synthesis Pathway

Glutamate is not a single-precursor molecule — it is synthesised via multiple routes:

```
Route 1: Krebs Cycle (primary)
α-Ketoglutarate (from citric acid cycle)
      │
      │ [Glutamate dehydrogenase — GDH]
      │  Cofactors: NAD⁺ / NADH (Niacin / B3), NADP⁺ / NADPH
      │  Allosteric: Zn²⁺, Mg²⁺, ADP, leucine
      ▼
L-Glutamate

Route 2: Transamination
α-Ketoglutarate + amino acid donor (e.g., aspartate, alanine)
      │
      │ [Aminotransferases — AST, ALT]
      │  Cofactor: PLP (Vitamin B6)
      ▼
L-Glutamate

Route 3: Glutamine Hydrolysis (major in neurons)
Glutamine (from astrocytes)
      │
      │ [Glutaminase — GLS]
      │  Activated by: phosphate (Pi), NH₄⁺
      │  Inhibited by: glutamate itself
      ▼
L-Glutamate  +  NH₃
```

### Astrocyte–Neuron Glutamate–Glutamine Cycle

```
Glutamatergic Neuron                    Astrocyte
─────────────────────────────────────────────────────
Glutamate released into synapse
      │
      │ Postsynaptic action (AMPA, NMDA)
      │
      │ Excess taken up by astrocyte via EAAT (GLAST / GLT-1)
      │                              ▼
      │                   [Glutamine synthetase — GS]
      │                    Cofactors: Mg²⁺, ATP, Mn²⁺
      │                              ▼
      │                          Glutamine
      │
      │ Released by astrocyte → taken up by neuron (SNAT transporters)
      │
      │ [Glutaminase — GLS]
      ▼
  Glutamate (re-packaged into vesicles by VGLUT1/2/3)
```

---

## Cofactor Requirements for Synthesis

| Step | Enzyme | Required Cofactors / Nutrients |
|---|---|---|
| **α-KG → Glutamate** | GDH | NAD⁺ (B3), NADP⁺; Zn²⁺ (allosteric); Mg²⁺ |
| **Transamination** | AST, ALT | **PLP (Vitamin B6)** |
| **Glutamine → Glutamate** | Glutaminase | Phosphate; no specific vitamin cofactor |
| **Glutamate → Glutamine** (astrocyte) | Glutamine synthetase (GS) | **Mg²⁺**, **Mn²⁺**, ATP |
| **VGLUT loading** (vesicular) | VGLUT1/2/3 H⁺-ATPase | ATP (indirect — oxidative phosphorylation) |

---

## Degradation / Termination of Signalling

Glutamate signalling is terminated primarily by **reuptake**, not enzymatic degradation:

```
Synaptic Glutamate
      │
      ├──► Astrocyte reuptake via EAAT1 (GLAST) / EAAT2 (GLT-1)
      │           → Glutamine synthesis (GS, Mg²⁺-dependent)
      │           → Released back to neurons
      │
      ├──► Presynaptic reuptake via EAAT3 (EAAC1)
      │           → Glutamine synthesis or Krebs cycle
      │
      └──► Metabolism:
              Glutamate
                │
                ├──[GAD + B6]→ GABA (in inhibitory neurons)
                │
                ├──[GDH]→ α-KG → Krebs cycle (energy)
                │
                └──[γ-glutamylcysteine synthetase]→ Glutathione synthesis
```

---

## Excitotoxicity — The Dark Side

Glutamate **overactivation** of NMDA and AMPA receptors leads to excitotoxic cell death:

```
Excessive glutamate release or reuptake failure
      │
      ▼
Sustained NMDA activation → Ca²⁺ influx
      │
      ▼
Mitochondrial Ca²⁺ overload
      │
      ├──► Excessive ROS production
      ├──► Cytochrome c release → apoptosis
      └──► calpain / caspase activation → neuronal death
```

**Physiological NMDA channel blockers (prevent excitotoxicity):**
- **Magnesium (Mg²⁺)** — voltage-dependent pore block (removed during depolarisation)
- **Zinc (Zn²⁺)** — allosteric inhibition of NR2B-containing NMDA receptors
- **D-Serine** — co-agonist at glycine site (required for NMDA activation — not a blocker, but regulates gating)

---

## Glutamate Receptors

| Receptor Family | Type | Mechanism | Main Role |
|---|---|---|---|
| **AMPA** (GluA1-4) | Ionotropic — Na⁺/K⁺ channel | Fast depolarisation | Fast excitation; LTP induction |
| **NMDA** (GluN1/2/3) | Ionotropic — Na⁺/K⁺/Ca²⁺ channel | Slow, voltage-gated | LTP; memory; excitotoxicity; Mg²⁺-blocked at rest |
| **Kainate** (GluK1-5) | Ionotropic | Moderate kinetics | Presynaptic modulation; epilepsy |
| **mGluR Group I** (mGluR1,5) | Gq-coupled GPCR | Enhances excitability | Synaptic plasticity |
| **mGluR Group II/III** (mGluR2-4,6-8) | Gi-coupled GPCR | Reduces glutamate release | Autoreceptors; presynaptic inhibition |

---

## Cofactors and Nutritional Support — Summary

| Nutrient | Role | Effect of Deficiency |
|---|---|---|
| **Magnesium (Mg²⁺)** | NMDA receptor Mg²⁺-block (channel pore); GS cofactor | NMDA hyperactivation → anxiety, seizures, excitotoxicity |
| **Zinc (Zn²⁺)** | NMDA NR2B allosteric inhibition; GDH allosteric | Increased excitotoxicity risk |
| **Vitamin B6 (PLP)** | Transamination for glutamate synthesis; GAD for GABA | Altered Glu/GABA balance |
| **Niacin (B3) / NAD⁺** | GDH cofactor for glutamate synthesis | Reduced synthesis capacity |
| **Thiamine (B1)** | Krebs cycle → α-KG supply | Reduced glutamate synthesis (Wernicke's encephalopathy) |
| **Manganese (Mn²⁺)** | GS cofactor in astrocytes | Impaired glutamine synthesis (Mn²⁺ toxicity also impairs GS → glutamate accumulation) |
| **DHA (Omega-3)** | Maintains NMDA receptor density and membrane fluidity | Reduced NMDA signalling efficiency |
| **Taurine** | Modulates GABA-A and NMDA (indirect protection) | Reduced neuroprotection |

---

## Clinical Relevance

| Condition | Glutamate Status | Mechanism |
|---|---|---|
| **Stroke** | Massive excitotoxic release | Ischemia → ATP failure → reversal of EAAT → glutamate surge |
| **Epilepsy** | Local excess | GAD/GABA-T imbalance; reduced Mg²⁺ block |
| **ALS** | Reduced EAAT2 | Impaired astrocyte reuptake → motor neuron excitotoxicity |
| **Alzheimer's** | NMDA dysregulation | Memantine (NMDA antagonist) approved treatment |
| **Depression** | Glutamate excess (PFC/hippocampus) | Ketamine (NMDA antagonist) — rapid-acting antidepressant |
| **Schizophrenia** | NMDA hypofunction (GABA interneuron loss) | NMDA antagonists (PCP, ketamine) mimic symptoms |
| **Glutamate sensitivity (dietary)** | MSG sensitivity claims | Evidence limited; DAO/HNMT co-involvement |

---

## Drug Interactions

| Drug | Effect |
|---|---|
| **Memantine** | Uncompetitive NMDA antagonist — Alzheimer's disease |
| **Ketamine / Esketamine** | NMDA antagonist — rapid antidepressant; dissociative |
| **PCP (phencyclidine)** | NMDA antagonist — abuse/psychosis |
| **Riluzole** | Reduces glutamate release; ALS treatment |
| **Lamotrigine** | Blocks Na⁺ channels → reduces glutamate release |
| **Topiramate** | AMPA/kainate antagonist + GABA-A enhancement; anticonvulsant |
| **Alcohol** | NMDA antagonist (acute); NMDA upregulation on withdrawal → seizures |
| **Mg²⁺ supplementation** | Physiological NMDA modulation; reduces excitotoxicity |
