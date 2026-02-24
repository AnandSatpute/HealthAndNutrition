# MAO — Monoamine Oxidase

**MAO (Monoamine Oxidase)** is a mitochondria-bound flavoenzyme that **oxidatively deaminates monoamine neurotransmitters and dietary amines**. It is the primary degradation enzyme for serotonin, norepinephrine, dopamine, and tyramine. MAO exists in two isoforms — **MAO-A** and **MAO-B** — with distinct but overlapping substrate specificity.

---

## 🔬 Biochemistry Overview

| Property | MAO-A | MAO-B |
|---|---|---|
| **Gene** | *MAOA* (Xp11.3) | *MAOB* (Xp11.23) |
| **Chromosome** | X chromosome | X chromosome |
| **EC number** | EC 1.4.3.4 | EC 1.4.3.4 |
| **Cofactor** | FAD (Flavin Adenine Dinucleotide) — covalently bound | FAD — covalently bound |
| **Location** | Outer mitochondrial membrane (neurons, gut enterocytes, liver, placenta) | Outer mitochondrial membrane (neurons, glial cells, liver, platelets) |
| **Primary substrates** | Serotonin, Norepinephrine, Epinephrine, Tyramine, Dopamine | Dopamine, β-PEA, Benzylamine, N-methyl histamine, Tyramine |
| **Inhibitor selectivity** | Moclobemide, Clorgyline (reversible/irreversible selective) | Selegiline, Rasagiline (irreversible selective) |
| **Clinical focus** | Depression, anxiety, panic disorder, PTSD | Parkinson's disease, cognitive decline |

---

## ⚙️ The MAO Reaction

```
R-CH₂-NH₂  +  O₂  +  H₂O  ──► R-CHO  +  NH₃  +  H₂O₂
  (amine)                       (aldehyde)        (reactive oxygen species)
```

### Key Consequences:
1. **Aldehyde intermediate** — toxic; rapidly converted by ALDH (requires NAD⁺/B3) to an acid, or by AR to an alcohol
2. **H₂O₂ generation** — a source of oxidative stress in neurons (relevant in neurodegeneration)
3. **NH₃ generation** — minor contribution to ammonia pool

---

## 🧠 Substrate Specificity & Full Degradation Pathways

### MAO-A Pathways

#### Serotonin (5-HT) Catabolism
```
Serotonin (5-HT)
  │
  └──► MAO-A + FAD ──► 5-Hydroxyindoleacetaldehyde (5-HIAL)
                              │
                              ├──► ALDH + NAD⁺ ──► 5-HIAA (5-Hydroxyindoleacetic acid) ← [Primary urinary metabolite]
                              │
                              └──► AR + NADPH ──► 5-HIOL (minor)
```

#### Norepinephrine (NE) Catabolism
```
Norepinephrine
  │
  ├──► MAO-A + FAD ──► DHPGAL (3,4-Dihydroxyphenylglycolaldehyde)
  │                          │
  │                          └──► ALDH + NAD⁺ ──► DHPGA
  │                                   │
  │                                   └──► COMT + SAM ──► VMA (Vanillylmandelic acid) [primary urinary end-product]
  │
  └──► COMT + SAM ──► Normetanephrine ──► MAO-A ──► VMA
```

### MAO-B Pathways

#### Dopamine (DA) Catabolism
```
Dopamine
  │
  ├──► MAO-B + FAD ──► DOPAL (3,4-Dihydroxyphenylacetaldehyde) ← [neurotoxic intermediate]
  │                          │
  │                          ├──► ALDH + NAD⁺ ──► DOPAC (3,4-Dihydroxyphenylacetic acid)
  │                          │                          │
  │                          │                          └──► COMT + SAM, Mg²⁺ ──► HVA [urinary end-product]
  │                          │
  │                          └──► AR + NADPH ──► DOPET (minor)
  │
  └──► COMT + SAM ──► 3-MT ──► MAO-B ──► MOPEGAL ──► ALDH ──► HVA
```

> **DOPAL** (aldehyde intermediate of dopamine) is directly **neurotoxic** — it cross-links α-synuclein and contributes to Lewy body formation in Parkinson's disease. ALDH efficiency (NAD⁺/B3 dependent) is critical for its rapid clearance.

#### β-Phenylethylamine (β-PEA) Catabolism
```
β-PEA ──► MAO-B + FAD ──► Phenylacetaldehyde ──► ALDH ──► Phenylacetic acid
```
β-PEA is an endogenous neuromodulator (the "love molecule" — released during excitement/attraction). It has a very short half-life because MAO-B is highly efficient at degrading it.

---

## 🧪 Cofactor: FAD (Riboflavin / Vitamin B2)

FAD is the **sole enzymatic cofactor** of MAO-A and MAO-B. It is **covalently bonded** to the enzyme (unlike many FAD enzymes where it is loosely bound):

| FAD Availability | Effect on MAO | Downstream Effect |
|---|---|---|
| **Normal riboflavin (B2) status** | Full MAO-A + MAO-B activity | Normal monoamine turnover |
| **B2 deficiency** | ↓ FAD → ↓ MAO-A activity | ↑ Serotonin, NE half-life → mood effects |
| **B2 deficiency (MAO-B)** | ↓ FAD → ↓ MAO-B activity | ↑ Dopamine, β-PEA levels |
| **High-dose riboflavin** | May restore MAO activity in deficiency | Normalizes monoamine catabolism |

> Because FAD is **covalently** bound, MAO protein synthesis (and thus dietary B2 for de novo enzyme production) matters more than just repletion of free FAD.

---

## 🧬 Key SNPs

### MAO-A — The "Warrior Gene"

The most famous **variable number tandem repeat (VNTR)** polymorphism:

| VNTR Allele | Expression Level | Phenotype |
|---|---|---|
| **3-repeat (3R)** | Lower MAO-A expression | ↑ Serotonin/NE → impulsivity, aggression under stress |
| **4-repeat (4R)** | Higher MAO-A expression | Normal/faster serotonin clearance |
| **3.5R / 5R** | Intermediate–high | Variable |

**Why "Warrior Gene"?**
- Low MAO-A (3R, especially in males given X-linkage) → higher baseline serotonin and NE → associated with increased aggression, impulsivity, antisocial behavior under adversity, but also resilience in some contexts.
- The effect is **strongly modified by early childhood environment** (abuse, neglect). Low MAO-A men who experienced maltreatment have significantly higher rates of conduct disorder — one of the strongest gene × environment interactions in psychiatry.

**X-linkage:**
- Males have only **one X chromosome** → one copy of MAOA. Effect is more direct.
- Females have two X chromosomes → usually one allele is more expressed, but protection from homozygosity effect is partial.

### MAO-B SNPs

| SNP | Location | Effect |
|---|---|---|
| rs1799836 (A/G) | Intron 13 | Lower activity (A allele) → higher DA/β-PEA → Parkinson's protection, but different psychiatric risk |
| rs6651806 | Promoter | Affects MAO-B expression |

---

## 💊 MAO Inhibitors (MAOIs) — Clinical Pharmacology

MAOIs are among the oldest and most powerful psychiatric drugs. They work by **blocking MAO-A, MAO-B, or both**, increasing synaptic monoamine levels.

### Classification

| Type | Examples | Selectivity | Reversibility |
|---|---|---|---|
| **Non-selective irreversible** | Phenelzine, Tranylcypromine, Isocarboxazid | MAO-A + MAO-B | Irreversible |
| **Selective MAO-A reversible (RIMA)** | Moclobemide | MAO-A | Reversible |
| **Selective MAO-B irreversible** | Selegiline (low-dose), Rasagiline | MAO-B | Irreversible (low dose) |
| **Selective MAO-B (high-dose selegiline)** | Selegiline patch / high oral dose | Both MAO-A + B | — |

### Clinical Uses

| Indication | MAO Inhibitor Used | Rationale |
|---|---|---|
| **Treatment-resistant depression** | Phenelzine, Tranylcypromine | Non-selective; massive ↑ serotonin + NE + DA |
| **Social anxiety disorder** | Phenelzine, Moclobemide | MAO-A inhibition → ↑ NE, serotonin |
| **PTSD** | Phenelzine | Strong evidence for re-experiencing symptoms |
| **Atypical depression** | Phenelzine > SSRIs in RCTs | Unique efficacy profile |
| **Parkinson's disease** | Selegiline, Rasagiline | MAO-B inhibition → ↑ DA, neuroprotection |
| **Cognitive decline prevention** | Selegiline | MAO-B inhibition reduces oxidative stress |

---

## ⚠️ The Tyramine Effect (Cheese Reaction)

This is the most critical clinical safety issue with MAOIs:

### Mechanism
```
Dietary tyramine (cheese, wine, cured meats, fermented foods)
  │
  Normally: MAO-A (gut/liver) degrades tyramine before systemic absorption
  │
  If MAO-A inhibited:
  │
  └──► Tyramine enters circulation → displaces catecholamines from vesicles
                                        → massive NE/EPI release
                                        → Hypertensive crisis (headache, chest pain, stroke risk)
```

### Foods to Avoid with Non-Selective / Irreversible MAO-A Inhibitors

| Food Category | High Tyramine Examples |
|---|---|
| Aged cheeses | Old cheddar, brie, blue cheese, Camembert |
| Fermented/cured meats | Salami, pepperoni, fermented sausage |
| Fermented beverages | Tap beer, red wine, aged spirits |
| Fermented foods | Sauerkraut, kimchi, soy sauce, miso |
| Aged/smoked fish | Smoked salmon, pickled herring |
| Overripe fruit | Overripe bananas, avocados |

> **Moclobemide (RIMA)** has much lower tyramine liability because inhibition is reversible — tyramine can displace it from MAO-A.

### Serotonin Syndrome Risk
MAOIs + serotonergic drugs = potentially fatal:
- MAOIs + SSRIs/SNRIs → serotonin syndrome
- MAOIs + tramadol, meperidine, linezolid, methylene blue → dangerous interactions
- Washout period: **2 weeks** after stopping irreversible MAOI before starting serotonergic drug; **5 weeks** after fluoxetine (long half-life) before starting MAOI

---

## 🍽️ Nutritional Regulators of MAO Activity

| Nutrient / Compound | Effect | Mechanism |
|---|---|---|
| **Riboflavin (B2)** | Required cofactor | FAD supplies oxidative capacity |
| **Curcumin** | MAO-A + MAO-B inhibitor | Competitive inhibition (mild) |
| **Quercetin** | MAO-A inhibitor | Flavonoid-based inhibition |
| **Epigallocatechin (EGCG)** | MAO-B inhibitor | Also inhibits COMT |
| **Resveratrol** | MAO-A + MAO-B inhibitor | Stilbene polyphenol |
| **Piperine** (black pepper) | Weak MAO inhibitor | May raise monoamine levels |
| **Harmine, harmaline** (β-carbolines) | Potent MAO-A inhibitors | Found in passionflower, ayahuasca |
| **St. John's Wort (Hyperforin)** | MAO inhibitor + reuptake inhibitor | Significant drug interactions |
| **Alcohol (chronic)** | ↑ MAO-B activity | Platelet MAO-B used as alcoholism biomarker |

---

## 🧠 Neurological & Psychiatric Relevance

| Condition | MAO Connection |
|---|---|
| **Depression** | Low MAO-A VNTR → ↑ serotonin (paradoxically doesn't protect — see environment); MAOIs most effective antidepressants in some subtypes |
| **Aggression / antisocial behaviour** | Low MAO-A + adverse childhood → strongest G×E interaction in psychiatry |
| **PTSD** | MAO-A VNTR + trauma exposure → fear circuit sensitisation |
| **Parkinson's disease** | MAO-B oxidizes MPTP → MPP⁺ (neurotoxin); MAO-B also generates H₂O₂ → dopaminergic neuron death |
| **Alzheimer's disease** | MAO-B markedly increased in astrocytes near amyloid plaques → ↑ oxidative stress |
| **Autism spectrum** | MAOA VNTR implicated in some ASD subgroups |
| **ADHD** | MAO-A regulation intersects with dopamine/NE tone |
| **Fibromyalgia** | Lower MAO activity → higher pain-modulating monoamines (serotonin) paradoxically impairs pain perception context |

---

## 🔁 MAO vs. COMT — Complementary Degradation

| Feature | MAO | COMT |
|---|---|---|
| **Reaction type** | Oxidative deamination | O-methylation |
| **Cofactor** | FAD (B2) | SAM (B12, folate, B2, Mg) |
| **Location emphasis** | Presynaptic mitochondria, gut, liver | Postsynaptic PFC neurons, liver, erythrocytes |
| **Primary role** | Intraneuronal catabolism | Extraneuronal / synaptic cleft clearance |
| **Key substrate** | Serotonin (MAO-A), Dopamine (MAO-B) | Dopamine, NE, EPI, catechol-oestrogens |
| **Toxic intermediate** | Aldehydes (DOPAL, 5-HIAL) + H₂O₂ | SAH → Homocysteine (if cycle impaired) |
| **Genetic SNP** | MAOA VNTR (3R/4R) | Val158Met |
| **Drug inhibitors** | Phenelzine, selegiline, rasagiline | Entacapone, tolcapone |

---

## 📊 Clinical Testing

| Test | What It Measures |
|---|---|
| **Platelet MAO-B activity** | Surrogate for CNS MAO-B; used in research; elevated in alcoholism |
| **Urinary 5-HIAA** | Serotonin turnover (MAO-A output) — elevated in carcinoid syndrome |
| **Urinary HVA** | Dopamine turnover (MAO-B + COMT output) |
| **Urinary VMA** | NE/EPI turnover (MAO-A + COMT output) — elevated in phaeochromocytoma |
| **Plasma metanephrines** | NE/EPI degradation rate (COMT > MAO) |
| **MAOA VNTR genotyping** | Genetic promoter activity assessment |
| **Serum riboflavin / EGRAC** | FAD sufficiency (MAO cofactor) |

---

## Summary

MAO-A and MAO-B are **mitochondria-bound, FAD-dependent enzymes** that are the first line of monoamine degradation, working in concert with COMT and ALDH. MAO-A primarily handles **serotonin and norepinephrine**; MAO-B handles **dopamine and β-PEA**. Their activity is genetically modulated (MAOA VNTR "warrior gene" polymorphism), nutritionally governed by **riboflavin (B2)**, and pharmacologically inhibited by MAOIs — a class of drugs with powerful antidepressant and antiparkinsonian applications but serious **tyramine and serotonin syndrome risks**. MAO-B overactivation in the aging brain contributes to oxidative stress and neurodegeneration via H₂O₂ and toxic aldehyde accumulation (particularly DOPAL in Parkinson's disease).
