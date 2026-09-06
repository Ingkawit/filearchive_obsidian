# Integrated Metabolism — How All the Pathways Connect

_Built from your [[carbohydrate metabolism]], [[fatty acid metabolism]], [[amino acid metabolism]], and [[cholesterol metabolism]] notes. Central idea: almost every pathway either feeds into or is fed by the [[Krebs Cycle]] through [[acetyl coA]]._

---

## 0. The Big Picture — One Hub, Three Fuels

Think of metabolism as a **hub-and-spoke system**:

```
        CARBOHYDRATE            LIPID              PROTEIN
        (glucose)          (fatty acid)        (amino acid)
             \                   |                   /
              \                  |                  /
           pyruvate      beta-oxidation      transamination/
               \                 |            deamination
                \                |                /
                 \               |               /
                  ▼              ▼              ▼
                     [[acetyl coA]]  ◄── HUB ──► glucogenic AAs → OAA
                              |
                              ▼
                      [[Krebs Cycle]]  (matrix of [[mitochondria]])
                              |
                    NADH, FADH2, GTP/ATP
                              |
                              ▼
              [[electron transport chain]]  →  ATP (oxidative phosphorylation)
```

**Rule to memorize:** _Acetyl-CoA is a one-way door._ Once carbon enters the Krebs cycle as acetyl-CoA, it **cannot go back to glucose** (no net gluconeogenesis from acetyl-CoA/fat). This single fact explains why fat can't be turned into glucose, but glucose and most amino acids _can_ be turned into fat or ketones.

---

## 1. Carbohydrate Metabolism — the entry pathway

Your [[carbohydrate metabolism]] note links [[carb digest pathway]] → [[glucose metabolism path]] → downstream branches. Flow:

1. **Digestion**: [[polysaccharide]] → [[disaccharide]] → [[monosaccharide]] (via [[pancreatic amylase]], maltase, sucrase, lactase) → absorbed via [[glucose]] transporters (SGLT1/GLUT)
2. **[[glycolysis]]** (cytosol): glucose → 2 [[pyruvate]] (net 2 ATP, 2 NADH)
    - Key regulated enzymes: [[hexokinase]]/[[glucokinase]], phosphofructokinase-1 (committed step), pyruvate kinase
3. **Fate of pyruvate** — the fork in the road:
    - **No O₂ / RBC**: pyruvate → [[lactic acid]] (lactate dehydrogenase, regenerates NAD+) → feeds the **[[Cori cycle]]** (lactate → liver → [[gluconeogenesis]] → glucose back to muscle)
    - **Aerobic**: pyruvate → **[[acetyl coA]]** (pyruvate dehydrogenase complex, needs [[thiamine (B1)]], [[riboflavin (B2)]], [[niacin (B3)]], lipoic acid, [[coenzyme A]]) → enters **[[Krebs Cycle]]**
4. **[[glycogen]]** — glucose storage/release
    - [[glycogenesis]] (build, insulin-stimulated) vs [[glycogenolysis]] (breakdown, glucagon/epinephrine-stimulated)
5. **[[gluconeogenesis]]** — making glucose _from_ pyruvate/lactate/glycerol/glucogenic amino acids (**not** from acetyl-CoA/fat) — occurs mainly in liver, uses reverse-glycolysis enzymes plus bypass enzymes (pyruvate carboxylase [[biotin (B7)]]-dependent, PEP carboxykinase, fructose-1,6-bisphosphatase, glucose-6-phosphatase)
6. **[[pentose phosphate pathway]]** — side-branch off [[glucose-6-phosphate]], doesn't make ATP; makes:
    - [[NADPH]] (fatty acid/cholesterol synthesis, antioxidant defense — this is why [[G6PD deficiency]] causes oxidative hemolysis)
    - ribose-5-phosphate (for [[nucleic acid]]/nucleotide synthesis)
7. **[[glucose-alanine cycle]]** — muscle exports nitrogen as alanine → liver deaminates it → the carbon skeleton (pyruvate) re-enters gluconeogenesis, and the nitrogen enters the **[[urea cycle]]** — this is the bridge from carbohydrate metabolism into amino acid metabolism.

---

## 2. Lipid Metabolism — the energy-dense fuel

Two directions, both centered on **[[acetyl coA]]**:

### A. Breakdown (catabolism) → makes acetyl-CoA

- [[triacylglycerol]] (stored fat) → lipolysis (hormone-sensitive lipase) → [[fatty acid]] + [[glycerol]]
    - **Glycerol** re-enters glycolysis/gluconeogenesis at [[DHAP]]/[[G3P]] — this is the _only_ part of a fat molecule that can become glucose
    - **Fatty acids** → **[[fatty acid oxidation]]** (mitochondria; carnitine shuttle for long-chain FAs) → repeated **[[beta-oxidation]]** cycles → acetyl-CoA + NADH + FADH2 → straight into Krebs Cycle/ETC

### B. Synthesis (anabolism) ← from acetyl-CoA

- **[[fatty acid synthesis]]**: excess acetyl-CoA (from glucose or amino acids, fed state, high insulin) → cytosol → acetyl-CoA carboxylase ([[biotin (B7)]]-dependent, rate-limiting) → malonyl-CoA → palmitate, using **NADPH from the pentose phosphate pathway**
- This is why **carb overfeeding still makes you fat**: excess glucose → pyruvate → acetyl-CoA → fatty acid synthesis → triacylglycerol storage

### C. Ketone bodies — the "backup fuel" branch

- Fasting/low insulin/high glucagon → lots of beta-oxidation-derived acetyl-CoA but **Krebs cycle intermediates (oxaloacetate) are being diverted to gluconeogenesis** → acetyl-CoA backs up → liver mitochondria shunt it into **[[ketogenesis]]** (HMG-CoA synthase, rate-limiting) → [[ketone body]] (acetoacetate, β-hydroxybutyrate, acetone)
- Ketone bodies travel in blood to peripheral tissues (brain, muscle, heart — **not liver**, which lacks the enzyme SCOT) → **[[ketolysis]]** regenerates acetyl-CoA → Krebs cycle
- Clinical: uncontrolled diabetes → unrestrained lipolysis/ketogenesis → diabetic ketoacidosis

### D. Cholesterol — a separate isoprenoid branch off acetyl-CoA

- [[cholesterol metabolism]] → acetyl-CoA → HMG-CoA → **HMG-CoA reductase** (rate-limiting, target of [[statin]]) → mevalonate → cholesterol
- Feeds into [[bile acid]]/[[bile salt]] synthesis, [[steroid hormone]]s, and membrane cholesterol
- Transported via **[[lipoprotein]]**: chylomicron (dietary fat) → VLDL (liver-exported fat) → IDL → LDL ("delivers" cholesterol) → HDL ("reverse transport," returns cholesterol to liver)

### E. Eicosanoids — a signaling branch off membrane fatty acids

- Membrane [[phospholipid]] → phospholipase A2 releases [[arachidonic acid]] → **[[eicosanoid synthesis]]** via COX (prostaglandins, thromboxane) or LOX (leukotrienes) pathways → local inflammatory/vascular signaling (not an energy pathway, but shares the fatty-acid origin)

---

## 3. Amino Acid Metabolism — the nitrogen-carrying fuel

From [[amino acid metabolism]] / [[amino metabolism path]]:

1. **Transamination**: amino acid + α-ketoglutarate ⇌ new keto acid + glutamate (ALT/AST enzymes, need **PLP = [[pyridoxine (B6)]]**)
2. **Deamination**: glutamate → α-ketoglutarate + **NH3** (glutamate dehydrogenase) — this is how the amino group is released for disposal
3. **NH3 disposal**: → **[[urea cycle]]** (liver) → [[urea]] → excreted by kidney. (This is the essential partner pathway to amino acid catabolism — every amino acid that's broken down for energy dumps its nitrogen here.)
4. **Carbon skeleton (keto acid) fate** — this is where amino acids plug into the hub:
    - **Glucogenic** amino acids → pyruvate or Krebs cycle intermediates (α-ketoglutarate, succinyl-CoA, fumarate, oxaloacetate) → **can** go to gluconeogenesis (because they enter _before_ the acetyl-CoA "point of no return")
    - **Ketogenic** amino acids (leucine, lysine) → acetyl-CoA / acetoacetyl-CoA directly → **cannot** become glucose, same rule as fat
    - Some amino acids (e.g., isoleucine, valine) are **both**

This is why amino acid metabolism is drawn feeding into _multiple_ points around the Krebs cycle rather than one single entry, unlike glucose (always via pyruvate/acetyl-CoA) or fat (always via acetyl-CoA).

---

## 4. The Central Hub — Krebs Cycle & Electron Transport Chain

- **[[Krebs Cycle]]** (mitochondrial matrix): acetyl-CoA + oxaloacetate → citrate → ... → oxaloacetate regenerated. Per turn: 3 NADH, 1 FADH2, 1 GTP/ATP, 2 CO2
    - Oxaloacetate is the "revolving door" — it's also the first gluconeogenesis intermediate, which is why **heavy gluconeogenesis (fasting) depletes oxaloacetate and forces acetyl-CoA into ketogenesis instead** (the mechanistic link between sections 1, 2, and 3 above)
- **[[electron transport chain]]** (inner mitochondrial membrane / cristae): NADH and FADH2 from glycolysis, beta-oxidation, and Krebs cycle all converge here → electrons passed through Complexes I–IV → proton gradient → ATP synthase (Complex V) makes ATP
    - This is the **true final common pathway** — no matter which fuel you started with (carb, fat, or protein), the payoff in ATP happens here

---

## 5. Hormonal Switch — What Decides the Direction of Flow

|State|Hormone|Carb|Lipid|Protein|
|---|---|---|---|---|
|**[[fed state]]**|↑ insulin|glycolysis, glycogenesis|fatty acid synthesis, TG storage|protein synthesis|
|**Fasting (early)**|↑ glucagon|glycogenolysis|lipolysis begins|—|
|**Fasting (prolonged)**|↑↑ glucagon, cortisol|gluconeogenesis (from lactate, alanine, glycerol)|beta-oxidation, ketogenesis|muscle protein broken down for glucogenic AAs|
|**Diabetic ketoacidosis**|↓↓ insulin|can't use glucose|unrestrained lipolysis/ketogenesis|—|

This table is the "why" behind every arrow above — insulin pushes carbon _into_ storage (glycogen, fat), glucagon/cortisol pull it back _out_ toward the Krebs cycle/ETC for ATP or toward gluconeogenesis to protect blood glucose (especially for the brain and RBCs, which need glucose or ketones — never fatty acids, since FA can't cross the blood-brain barrier and RBCs lack mitochondria).

---

## 6. One-Paragraph Summary (exam-ready)

All three macronutrients converge on **acetyl-CoA**, which enters the **Krebs cycle** to generate NADH/FADH2 for the **electron transport chain** — the shared final pathway for ATP production. Glucose gets there via glycolysis → pyruvate → acetyl-CoA (or is stored as glycogen, or diverted through the pentose phosphate pathway for NADPH/ribose). Fat gets there via beta-oxidation → acetyl-CoA (or is stored as triacylglycerol, or — in fasting, when oxaloacetate is diverted to gluconeogenesis — shunted into ketone bodies as a backup fuel for the brain/heart/muscle). Amino acids are transaminated/deaminated (nitrogen exits via the urea cycle), and their carbon skeletons enter as pyruvate or Krebs cycle intermediates (glucogenic, so gluconeogenesis is possible) or as acetyl-CoA (ketogenic, so it is not). Crucially, **acetyl-CoA can never be converted back to glucose** — this single rule explains why fasting burns fat and protein but the brain still needs gluconeogenesis or ketones to survive, and why carbohydrate excess (not just fat excess) still ends up stored as body fat.

---

## Your related Excalidraw diagrams (for the visual version)

- [[glucose metabolism path]] — glycolysis + fates of pyruvate + shuttles
- [[gluconeogenesis path]] / [[glucose cycle path]] — Cori cycle, glucose-alanine cycle, glycogen cycling
- [[fatty acid metabolism path]] — synthesis + beta-oxidation + regulation of ACC
- [[amino metabolism path]] — transamination, urea cycle, entry points into Krebs cycle
- [[cholesterol synthesis path]] — HMG-CoA reductase pathway
- [[lipoprotein metabolism path]] — chylomicron/VLDL/LDL/HDL trafficking
- [[eicosanoid metabolism path]] — arachidonic acid signaling branch
- [[carb digest pathway]] — digestion to absorption
- **[[all metabolism pathway]]** — your existing master diagram; this document is its narrative companion