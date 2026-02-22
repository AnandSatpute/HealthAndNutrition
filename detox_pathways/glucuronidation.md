# Glucuronidation Pathway

## Overview

Glucuronidation is **quantitatively the most important Phase II conjugation pathway** in humans, accounting for the metabolism of roughly 35–40% of all drugs that undergo conjugation. It is performed by the **UDP-glucuronosyltransferase (UGT)** enzyme family, which attaches glucuronic acid to nucleophilic atoms (–OH, –NH₂, –COOH, –SH) on substrates.

The resulting **glucuronide conjugates** are highly polar, water-soluble, and typically pharmacologically inactive, making them ideal for biliary or urinary excretion.

---

## Enzymology

### UDP-Glucuronosyltransferases (UGTs)

- **Location**: Endoplasmic reticulum membrane (lumenal face)
- **Human isoforms**: 22 functional genes in two families — UGT1 (UGT1A1–1A13) and UGT2 (UGT2A1–2A3, UGT2B4–2B28)
- **Cofactor**: UDP-glucuronic acid (UDPGA), synthesised from glucose-1-phosphate + UDP-glucose

### UDPGA Synthesis

```
Glucose-1-phosphate + UTP  →  UDP-glucose (UGK enzyme)
UDP-glucose + 2 NAD⁺  →  UDP-glucuronic acid + 2 NADH  (UGDH enzyme)
```

Availability of UDPGA depends on adequate glucose (energy substrate) and NAD⁺ (from niacin, B3). Fasting or prolonged low-carbohydrate states can modestly impair UDPGA availability.

---

## Key UGT Isoforms and Their Substrates

| Isoform | Primary Substrates | Clinical Notes |
|---|---|---|
| **UGT1A1** | Bilirubin, oestrogens, irinotecan (SN-38), etoposide | Most clinically studied; *UGT1A1*28* variant → Gilbert's/CN syndrome |
| **UGT1A3** | Bile acids, carboxylic acid drugs, T3 | — |
| **UGT1A4** | Lamotrigine, trifluoperazine, androgens | Induced by rifampicin, carbamazepine |
| **UGT1A6** | Small planar phenols: serotonin, acetaminophen, aspirin | — |
| **UGT1A9** | Propofol, mycophenolic acid, furosemide | — |
| **UGT2B7** | Morphine → M6G (active), codeine, valproic acid, AZT | M6G is more potent than morphine; accumulates in renal failure |
| **UGT2B15** | Oxazepam, testosterone, DHT, S-lorazepam | Androgen inactivation |
| **UGT2B17** | Testosterone, DHT, androsterone | Individual variability; gene copy number varies widely |

---

## Endogenous Substrates

Beyond xenobiotics, glucuronidation is essential for normal physiology:

| Endogenous Compound | Result of Glucuronidation |
|---|---|
| **Bilirubin** | Bilirubin diglucuronide → water-soluble; excreted in bile |
| **Oestradiol (E2)** | E2-3G, E2-17G → inactivated; biliary excretion |
| **Oestrone (E1)** | E1-3G → excreted; reversible via gut β-glucuronidase |
| **T3/T4 (thyroid)** | Glucuronide conjugates → biliary excretion; enterohepatic cycling |
| **Testosterone/DHT** | Androgen glucuronides → urinary excretion (sport doping detection) |
| **Retinoic acid** | Retinyl β-glucuronide → excreted |
| **Serotonin** | Minor glucuronide pathway |

---

## UGT1A1*28 — Gilbert's Syndrome

The most common UGT variant in clinical practice:

- **Variant**: Extra TA repeat in UGT1A1 promoter (7 TA repeats vs. normal 6) — *UGT1A1*28*
- **Frequency**: ~10% homozygous, ~40% heterozygous in Western populations
- **Effect**: 70–75% reduction in UGT1A1 expression → impaired bilirubin glucuronidation
- **Clinical**: Mild unconjugated hyperbilirubinaemia, typically benign; yellowing with fasting/illness/fever

**Practical implications:**
- Increased GI toxicity with irinotecan (UGT1A1 glucuronidates active metabolite SN-38)
- Potentially enhanced oestrogen levels (reduced E2 glucuronidation)
- Consider lower dose irinotecan in *28/*28 patients (FDA recommends genotyping)

---

## Enterohepatic Recirculation (EHC) of Glucuronides

EHC is the major "escape" route that can nullify glucuronidation — see `phase_3_transport.md` for the full mechanism.

**Key clinical examples:**

| Compound | EHC Consequence |
|---|---|
| Oestrogens | Prolonged oestrogen exposure; relevant to HRT, contraceptives |
| Morphine-6-glucuronide | Prolonged opioid effect (particularly in renal impairment) |
| Bilirubin (neonates) | Neonatal jaundice — immature UGT1A1 + active intestinal β-glucuronidase |
| NSAIDs (acyl glucuronides) | Reactive acyl glucuronides re-released → GI mucosal damage |
| Irinotecan (SN-38-G) | SN-38 re-released in colon → colonic toxicity |

**Reducing EHC:**
- **Calcium D-glucarate** (Ca-D-glucarate): Hydrolysed to D-glucaric acid → inhibits β-glucuronidase; studied for oestrogen modulation and cancer chemoprevention
- **Dietary fibre** (inulin, psyllium, cellulose): Binds deconjugated compounds in gut
- Probiotic strains with low β-glucuronidase activity

---

## Inducers and Inhibitors of UGTs

### Inducers (increase glucuronidation)

| Inducer | Mechanism/Source |
|---|---|
| Cruciferous vegetables (sulforaphane, DIM) | Activate Nrf2 and AhR → UGT1A1, 1A6 upregulation |
| St. John's Wort | PXR activation → UGT induction |
| Rifampicin (antibiotic) | Strong PXR agonist |
| Phenobarbital | CAR receptor activation |
| Alcohol (chronic) | Variable UGT induction |

### Inhibitors (decrease glucuronidation)

| Inhibitor | Effect |
|---|---|
| Valproic acid | Competes for UGT2B7 (morphine, lamotrigine interactions) |
| Probenecid | Competes for UGT and renal transporters |
| Ketoconazole | Broad inhibition |
| High bilirubin load | Competitive inhibition of UGT1A1 |

---

## Nutritional and Lifestyle Support

| Compound | Effect on Glucuronidation |
|---|---|
| **Cruciferous vegetables** (broccoli, Brussels sprouts, kale) | Induce UGT1A1/1A6 via DIM and sulforaphane |
| **Niacin (B3)** | NAD⁺ for UDPGA synthesis |
| **Adequate glucose** (carbohydrates) | UDPGA precursor (not a reason to overeat; normal diet sufficient) |
| **Magnesium** | Cofactor in UDP-glucose metabolism |
| **Calcium D-glucarate** | Inhibits β-glucuronidase → reduces EHC |
| **Probiotics** | Reduce intestinal β-glucuronidase activity |
| **Dietary fibre** | Binds reabsorbable aglycones |
| **Avoid excessive alcohol** | Chronic alcohol disrupts UGT activity and increases EHC |
