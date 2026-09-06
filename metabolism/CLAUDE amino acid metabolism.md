
# Amino Acid Metabolism

_Reorganized version of [[amino acid metabolism]] / [[amino metabolism path]]. Structure: (1) what amino acids _are_, (2) the shared entry pathway everyone goes through, (3) glucogenic vs ketogenic logic, (4) where each amino acid actually branches into central metabolism, (5) clinical correlates._

---

## 1. Amino Acid Classification

Before catabolism makes sense, you need to know _what kind_ of side chain (R-group) each [[amino acid]] has — this determines both its role in [[protein]] structure and, later, which pathway breaks it down.

|Class|Members|Notes|
|---|---|---|
|**Nonpolar aliphatic**|Gly, Ala, Val, Leu, Ile, Pro, Met|Val/Leu/Ile = **branched-chain amino acids (BCAAs)**|
|**Aromatic**|Phe, Tyr, Trp|Phe/Tyr share one pathway; Trp is unique (also makes niacin/serotonin)|
|**Polar uncharged**|Ser, Thr, Cys, Asn, Gln|Ser/Thr have –OH (phosphorylation sites); Cys has –SH|
|**Acidic (negative)**|Asp, Glu|Carboxylic acid side chains; precursors of Asn, Gln|
|**Basic (positive)**|Lys, Arg, His|Arg is a [[urea cycle]] intermediate as well as an amino acid|

**Essential** (must come from diet — human cells cannot synthesize the carbon skeleton):

> _Mnemonic "PVT TIM HALL":_ **P**henylalanine, **V**aline, **T**hreonine, **T**ryptophan, **I**soleucine, **M**ethionine, **H**istidine, **A**rginine (conditionally, in growth/illness), **L**eucine, **L**ysine

**Nonessential**: Ala, Asp, Asn, Glu, Gln, Gly, Pro, Ser, Cys, Tyr (Cys and Tyr are "conditionally essential" — made _from_ Met and Phe respectively, so they become essential if those precursors are lacking).

---

## 2. The Shared Catabolic Entry Pathway

Every amino acid, no matter its class, goes through the **same two initial steps** before its carbon skeleton is free to enter central metabolism:

### Step 1 — Transamination (moving the amino group)

```
Amino acid + α-ketoglutarate  ⇌  new α-keto acid + Glutamate
```

- Catalyzed by **aminotransferases** (ALT, AST) — clinically these are liver enzymes you already know from LFTs
- **Absolute requirement: PLP** (pyridoxal phosphate, active form of [[pyridoxine (B6)]]) as coenzyme
- Net effect: the amino group is collected onto glutamate, and the amino acid becomes a keto acid (which is a Krebs cycle intermediate or its precursor — this keto acid _is_ the "branch point" discussed in Section 4)

### Step 2 — Oxidative deamination (releasing the nitrogen)

```
Glutamate + NAD(P)+ + H2O  →  α-ketoglutarate + NH3 + NAD(P)H
```

- Catalyzed by **glutamate dehydrogenase** (mitochondrial matrix, one of the few enzymes that uses either NAD+ or NADP+)
- Regenerates α-ketoglutarate (so it can accept another amino group — transamination is catalytic, not consumed)
- Releases free **ammonia (NH3)** — toxic, must be disposed of immediately

### Step 3 — Ammonia disposal: the Urea Cycle

Free NH3 is too toxic to circulate, so the liver converts it to **urea** (neutral, water-soluble, excreted by kidney):

1. NH3 + CO2 + 2ATP → **carbamoyl phosphate** (carbamoyl phosphate synthetase I, mitochondria; activated by **N-acetylglutamate**, the cycle's key regulator)
2. Carbamoyl phosphate + **ornithine** → **citrulline** (mitochondria)
3. Citrulline exported to cytosol + **aspartate** (this is how the _second_ nitrogen atom of urea enters — from an amino acid via transamination) → **argininosuccinate**
4. Argininosuccinate → **arginine** + fumarate (the fumarate re-enters the Krebs cycle — a direct link back to Section 4 below)
5. Arginine → **urea** + ornithine (arginase; ornithine regenerates to restart the cycle)

**Net:** 2 NH3 (one as free ammonia, one via aspartate) + CO2 + 3 ATP → 1 urea + fumarate. Every amino acid that's catabolized ultimately dumps its nitrogen through this cycle.

---

## 3. Glucogenic vs Ketogenic — the Rule

This follows the exact same logic as fatty acids in the [[Krebs Cycle]] hub: **anything that enters _before or at_ oxaloacetate can run gluconeogenesis; anything that enters as acetyl-CoA/acetoacetyl-CoA cannot** (no net carbon return to glucose from acetyl-CoA).

| Category                        | Amino acids                                                                    | Why                                                                                                                                  |
| ------------------------------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------ |
| **Purely ketogenic**            | **Leucine, Lysine**                                                            | Carbon skeleton enters _only_ as acetyl-CoA/acetoacetyl-CoA                                                                          |
| **Both glucogenic + ketogenic** | Isoleucine, Phenylalanine, Tyrosine, Tryptophan, Threonine                     | Molecule is split — part of the carbon skeleton exits as a Krebs intermediate, part as acetyl-CoA/acetoacetyl-CoA                    |
| **Purely glucogenic**           | All the rest (Ala, Gly, Ser, Cys, Asp, Asn, Glu, Gln, Pro, Arg, His, Val, Met) | Carbon skeleton enters as pyruvate or a Krebs cycle intermediate — can be pulled out at oxaloacetate and run through gluconeogenesis |

> _Mnemonic: "Leucine and Lysine, the only pure fat" — everything else has at least a glucogenic escape route._

---

## 4. Where Each Amino Acid Actually Enters — the 5 Branch Points

This is the part your notes call "branching out" — every amino acid's carbon skeleton funnels into central metabolism at one of **five entry points**. Grouping by entry point (rather than by essential/nonessential) is the more useful way to memorize this for exams, because it directly predicts glucogenic vs ketogenic status.

### A. → Pyruvate (glucogenic)

- **Alanine** (direct transamination — this is _the_ amino acid of the [[glucose-alanine cycle]])
- **Glycine, Serine, Cysteine** (interconvert with serine, then → pyruvate)
- **Threonine** (partially — also contributes to propionyl-CoA, see D)

### B. → α-Ketoglutarate (glucogenic)

- **Glutamate, Glutamine** (glutamine → glutamate → α-KG, one step removed)
- **Histidine** (→ glutamate → α-KG)
- **Proline** (→ glutamate → α-KG)
- **Arginine** (→ ornithine → glutamate → α-KG; note arginine is _also_ a direct urea cycle intermediate, so it has two metabolic identities)

### C. → Oxaloacetate (glucogenic)

- **Aspartate, Asparagine** (asparagine → aspartate → OAA; this is also aspartate's route _into_ the urea cycle as the second nitrogen donor)

### D. → Succinyl-CoA (glucogenic) — via propionyl-CoA → methylmalonyl-CoA

- **Valine, Isoleucine** (BCAAs), **Methionine, Threonine**
- This is the pathway that requires **[[cobalamin (B12)]]** (methylmalonyl-CoA mutase) — explains why B12 deficiency causes methylmalonic acidemia in addition to megaloblastic anemia

### E. → Fumarate (glucogenic)

- **Phenylalanine → Tyrosine** (Phe hydroxylase, needs BH4 cofactor) → further breakdown yields **both** fumarate (glucogenic) and acetoacetate (ketogenic) — hence Phe/Tyr's "both" status

### F. → Acetyl-CoA / Acetoacetyl-CoA (ketogenic)

- **Leucine** (purely this route)
- **Lysine** (purely this route, via a unique pathway with no transamination step)
- **Tryptophan** (splits — part → alanine → pyruvate [glucogenic], part → acetoacetyl-CoA [ketogenic]; also the precursor for niacin/[[niacin (B3)]] synthesis and serotonin)
- **Isoleucine** (splits between succinyl-CoA and acetyl-CoA — this is why it's "both")

---

## 5. Branched-Chain Amino Acids (BCAAs) — special mention

**Valine, Leucine, Isoleucine** deserve their own note because, unusually, their _first_ catabolic step happens in **muscle, not liver** (via branched-chain aminotransferase), which is why BCAAs are prominent in muscle protein turnover and exercise physiology. After transamination in muscle, the keto acids travel to the liver for the rest of the pathway (branched-chain α-keto acid dehydrogenase — structurally similar to pyruvate dehydrogenase, also needs thiamine).

---

## 6. Clinical Correlates (mapped to the branch points above)

|Disease|Defect|Branch point affected|
|---|---|---|
|**Phenylketonuria (PKU)**|Phenylalanine hydroxylase deficiency (or BH4 deficiency)|Blocks Phe → Tyr (branch E); Phe accumulates, shunted to phenylketones|
|**Alkaptonuria**|Homogentisate oxidase deficiency|Downstream of Tyr degradation; homogentisic acid accumulates (dark urine)|
|**Albinism**|Tyrosinase deficiency|Tyr → melanin pathway (separate from energy branch)|
|**Maple syrup urine disease**|Branched-chain α-keto acid dehydrogenase deficiency|Blocks BCAA breakdown (branch D/F) — sweet-smelling urine|
|**Homocystinuria**|Cystathionine β-synthase deficiency (needs B6)|Methionine/homocysteine metabolism|
|**Methylmalonic acidemia**|Methylmalonyl-CoA mutase deficiency or B12 deficiency|Branch D (succinyl-CoA route)|
|**Urea cycle disorders** (e.g., OTC deficiency)|Any urea cycle enzyme|Ammonia disposal → hyperammonemia, encephalopathy|

---

## 7. One-Paragraph Summary

Every amino acid is first stripped of its amino group by **transamination** (PLP/B6-dependent, transferring the nitrogen onto glutamate) and then **oxidative deamination** releases that nitrogen as free ammonia, which the **urea cycle** converts to urea for excretion — with aspartate donating the second nitrogen and fumarate exiting back into the Krebs cycle. What's left of each amino acid — its carbon skeleton — enters central metabolism at one of five points: **pyruvate** (Ala, Gly, Ser, Cys), **α-ketoglutarate** (Glu, Gln, His, Pro, Arg), **oxaloacetate** (Asp, Asn), **succinyl-CoA** (Val, Ile, Met, Thr — the B12-dependent route), or **acetyl-CoA/acetoacetyl-CoA** (Leu, Lys purely; Ile, Phe, Tyr, Trp partially). Anything entering at or before oxaloacetate is **glucogenic** (can feed gluconeogenesis); anything entering as acetyl-CoA is **ketogenic** (cannot). Leucine and lysine are the only two amino acids that are purely ketogenic — everything else retains at least a partial route back to glucose.