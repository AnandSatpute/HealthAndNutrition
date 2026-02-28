# Neuroplasticity

## Overview

Neuroplasticity is the brain's capacity to **reorganise its structure, connections, and function** in response to experience, learning, injury, or environmental change. It underlies all learning and memory, and is the therapeutic target in depression, PTSD, addiction recovery, and cognitive decline.

The two major forms:

| Form | Mechanism | Timescale |
|---|---|---|
| **Synaptic plasticity** | Strength changes between existing synapses | Seconds → days |
| **Structural plasticity** | Axon sprouting, dendritic remodelling, neurogenesis | Days → weeks |

---

## Brain-Derived Neurotrophic Factor (BDNF)

BDNF is the master regulator of neuroplasticity. It binds **TrkB receptors**, activating downstream cascades (MAPK/ERK, PI3K/Akt, PLCγ) that promote neuronal survival, synaptic strengthening, and new synapse formation.

### BDNF and the CREB Pathway

```
Stimulus (exercise, novelty, learning)
       │
       ▼
[Neuronal activity] → Ca²⁺ influx → CaM-kinase activation
       │
       ▼
CREB phosphorylation (pCREB) ──► BDNF gene transcription
       │
       ▼
BDNF protein → secreted → binds TrkB (pre/post-synaptically)
       │
       ├──► MAPK/ERK → synaptic protein synthesis (LTP consolidation)
       ├──► PI3K/Akt → neuronal survival (anti-apoptotic)
       └──► PLCγ → DAG + IP3 → PKC → AMPA receptor insertion
```

### Key Insight
> **Low BDNF is consistently found in depression, Alzheimer's, and chronic stress.** Most antidepressants (SSRIs, exercise, ketamine) exert effects at least partly by raising BDNF.

---

## Long-Term Potentiation (LTP)

LTP is the cellular mechanism of **memory formation**: repeated stimulation of a synapse makes it more efficient at transmitting future signals.

### Mechanism

```
Weak stimulation → AMPA receptors open → Na⁺ influx → small EPSP

Repeated / strong stimulation:
       │
       ▼
Large Na⁺ influx → EPSP depolarises membrane
       │
       ▼
Mg²⁺ block of NMDA receptor removed (voltage-gated)
       │
       ▼
Glutamate + Glycine bind NMDA receptor → Ca²⁺ + Na⁺ influx
       │
       │                        ┌─── CaM-Kinase II (CaMKII) → AMPA phosphorylation
       ▼                        │
Large Ca²⁺ signal ────────────►│─── PKC → AMPA receptor trafficking (↑surface AMPAs)
                                │
                                └─── CREB activation → BDNF → structural changes
```

### Phases of LTP

| Phase | Duration | Mechanism | Sensitive To |
|---|---|---|---|
| **E-LTP** (early) | < 3 hrs | AMPA phosphorylation, existing proteins | Protein kinase inhibitors |
| **L-LTP** (late) | > 3 hrs / days | New protein synthesis, structural remodelling | BDNF antibodies, transcription inhibitors |

---

## NMDA-Dependent Plasticity

The NMDA receptor (NMDAr) is the **co-incidence detector** of the brain — it only opens when the synapse is active (glutamate present) AND the neuron is already depolarised (Mg²⁺ block removed). This requirement enforces Hebbian learning: "neurons that fire together, wire together."

### NMDA Receptor Subunits and Nutrition

| Subunit | Role in plasticity | Nutritional relevance |
|---|---|---|
| **GluN1** | Obligatory; binds glycine (co-agonist) | Glycine sufficiency required for activation |
| **GluN2A** | Synaptic; short deactivation | Zinc modulates (inhibitory at high conc.) |
| **GluN2B** | Extrasynaptic; long open time; key for LTP induction | Magnesium (Mg-L-threonate increases brain Mg²⁺; reduces Mg²⁺ block) |
| **GluN2D** | Hippocampus; slow deactivation | — |

### Co-agonist Site
The NMDAr requires **both glutamate and a co-agonist** (glycine or D-serine) for full activation:
- **Glycine** (dietary; synthesised from serine) — binds GluN1
- **D-Serine** (synthesised by neuronal/astrocytic serine racemase) — predominates in cortex and hippocampus

> **Deficiency note:** Low glycine or impaired serine racemase (e.g., folate-deficiency affecting one-carbon metabolism and serine synthesis) can impair NMDA-dependent LTP.

---

## Neurogenesis

Adult neurogenesis occurs primarily in:
- **Dentate gyrus (hippocampus)** — spatial memory, pattern separation, emotional regulation
- **Olfactory bulb** (via subventricular zone)

Regulated by:
- ↑: Exercise (↑ BDNF, ↑ VEGF), caloric restriction, omega-3, curcumin, low stress
- ↓: Chronic stress (elevated cortisol), sleep deprivation, alcohol, neuroinflammation

---

## Nutrients That Upregulate BDNF and Neuroplasticity

| Nutrient / Compound | Mechanism | Evidence Level |
|---|---|---|
| **Omega-3 (DHA)** | DHA is incorporated into neuronal membranes → increases TrkB density; reduces neuroinflammation (prostaglandin E2 ↓) | Strong (human RCTs) |
| **Magnesium (Mg-L-threonate)** | Raises synaptic Mg²⁺ → enhances NMDA function at optimal levels; activates CREB | Moderate (animal model; human trials ongoing) |
| **Zinc** | TrkB → BDNF signalling modulator; regulates NMDA GluN2 subunit sensitivity | Moderate |
| **Curcumin** | Activates CREB; inhibits NF-κB (reduces BDNF-suppressing inflammation); inhibits MAO | Moderate (poor bioavailability unless with piperine) |
| **Vitamin D** | VDR (vitamin D receptor) upregulates NGF and NT-3 (similar to BDNF); modulates synaptic plasticity genes | Moderate |
| **Resveratrol** | SIRT1 activation → PGC-1α → mitochondrial biogenesis; increases BDNF indirectly | Moderate |
| **Lion's Mane (Hericium erinaceus)** | Hericenones / erinacines stimulate NGF synthesis via same CREB pathway | Moderate (human trials small) |
| **Exercise (exerkines)** | FNDC5/irisin → PGC-1α → BDNF mRNA; also VEGF, IGF-1 (crosses BBB) | Very strong |
| **Caloric restriction / fasting** | AMPK activation; ↑ BDNF via ketone body β-OHB signalling | Moderate |
| **B vitamins (B6, B9, B12)** | Homocysteine control (elevated Hcy is NMDA hyper-activator → excitotoxicity, damages synapses) | Strong |

---

## Factors That Suppress Neuroplasticity

| Factor | Mechanism |
|---|---|
| **Chronic cortisol** | Dendrite retraction in hippocampus; suppresses BDNF gene transcription |
| **Neuroinflammation (IL-6, TNF-α)** | IDO activation → tryptophan → quinolinate (NMDA agonist toxicity); ↓ BDNF |
| **High homocysteine** | Excitotoxic NMDA over-activation; DNA damage in neurons; B9/B12 deficiency |
| **Alcohol** | Acutely inhibits NMDA (anaesthetic effect); chronic → NMDA upregulation + withdrawal excitotoxicity |
| **Sleep deprivation** | Impairs synaptic homeostasis (SHY hypothesis); reduces hippocampal BDNF |
| **Oxidative stress** | Oxidises BDNF, damages TrkB receptors; depletes Mg, Zn, Se |

---

## Synaptic Homeostasis Hypothesis (SHY)

Sleep is not merely restorative — it is a **mandatory downscaling** of synaptic strength. During wakefulness, LTP-like processes build up synaptic weights throughout the day; sleep (especially slow-wave sleep) globally downscales synapses via **LTD (long-term depression)**, restoring signal-to-noise ratio and energy efficiency.

Nutritional relevance: Glycine supplementation (3 g before sleep) promotes deep SWS in human trials — proposed mechanism involves hypothermic effect (vasodilation) and NMDA receptor modulation in the suprachiasmatic nucleus.

---

## Clinical Relevance

| Condition | Plasticity Mechanism | Nutritional Application |
|---|---|---|
| **Depression** | Reduced BDNF (blunted hippocampal neurogenesis) | DHA, Mg, Zn, curcumin, exercise |
| **Alzheimer's disease** | Tau-disrupted BDNF transport; Aβ inhibits TrkB | DHA, curcumin, Lion's Mane (NGF), vitamin D |
| **PTSD** | Over-consolidated fear memories (amygdala LTP); reduced hippocampal BDNF | MDMA-assisted therapy increases BDNF; omega-3 |
| **Addiction** | Pathological LTP in reward circuits (NAc, PFC) | Curcumin (blunts ΔFosB), Mg (modulates NMDA craving circuits) |
| **Stroke / TBI** | Reduced BDNF in peri-lesion cortex | DHA (neuroprotective), Mg (reduces excitotoxicity acutely) |
| **Cognitive ageing** | Declining BDNF, synaptic loss, reduced neurogenesis | Multimodal: exercise + DHA + Mg + sleep optimisation |
