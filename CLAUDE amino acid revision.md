# Amino Acid Metabolism — Lecture Study Guide

_Source: Pornchai Kaewsapsak, Ph.D., Dept. of Biochemistry, Chula (2026 Fall)_

This note walks through the lecture in its original nine-part sequence: the amino acid pool → α-amino group removal → ammonia/urea cycle → the four carbon-skeleton "entry point" families → non-essential amino acid synthesis → intertissue relationships → and the specialty molecules built from amino acids. Treat it as the narrative companion to [[amino acid]], [[amino acid metabolism]], and [[protein]] — the individual entry-point pages can hold the mechanistic detail while this page holds the overall logic and the exam-style clinical correlates.

---

## 1. The amino acid pool and protein turnover

Every [[amino acid]] in the body sits in a single shared **metabolic pool**, fed by dietary protein (~100 g/day), de novo synthesis of non-essential amino acids, and the constant breakdown of body [[protein]] (~400 g/day of turnover in a 70 kg adult). The pool feeds back out into new body protein, non-protein derivatives (nucleotides, hormones, neurotransmitters, porphyrins, polyamines), and — when amino acids are catabolized — carbon skeletons (glucose, fatty acids, ketone bodies, CO₂) plus nitrogen that is excreted as urea. Under steady state, pool size is essentially constant, especially for essential amino acids, which is why dietary insufficiency of even one essential amino acid (e.g., low methionine or low protein diets low in the essential set) can drive net muscle wasting.

**Nitrogen balance** is the clinical bookkeeping tool for this pool:

- _Positive_ balance (intake > output): growth states — children, pregnancy, recovery from illness.
- _Negative_ balance (output > intake): catabolic states — fasting/starvation, elderly, high fever, post-surgery, poor nutrient proportion.

### Protein degradation pathways

Two systems dismantle proteins back into the pool, and this connects directly to [[protein degradation]], [[ubiquitin]], and [[proteasome]]:

- **Non-selective (lysosomal) pathway** — intracellular proteins/organelles via autophagy, or extracellular proteins via endocytosis, are delivered to the [[lysosome]], where **cathepsin** (a cysteine protease that favors acidic pH) degrades them. **Cystatin** in the cytoplasm protects other cellular proteins from stray cathepsin activity.
- **Selective (ubiquitin–proteasome) pathway** — the dominant route for cytosolic/nuclear proteins, and it is ATP-dependent. **Ubiquitin**, a 76-residue polypeptide, is attached to a lysine side chain on the target protein by a three-enzyme cascade: **E1 (activating)** → **E2 (conjugating)** → **E3 (ligase)**. Additional ubiquitins are chained onto **Lys-48** of the previous ubiquitin to build a **polyubiquitin chain**, which is the signal recognized by the multisubunit **proteasome**. (This E1/E2/E3 logic is also the basis of PROTAC drug design — targeted protein degradation therapeutics.)

**Rate of degradation — the N-end rule and PEST sequences:**

|Feature|Effect on half-life|
|---|---|
|N-terminal Gly, Ser, Thr, Ala, Met, Val|Slow degradation, t½ > 20 h|
|N-terminal Arg, Asp, Leu, Lys, Phe|Fast degradation|
|Oxidized lysine residue|Fast degradation|
|PEST sequence (Pro-Glu-Ser-Thr rich)|Fast degradation via ubiquitin–proteasome|

---

## 2. Removal of the α-amino group

Before an amino acid's carbon skeleton can be oxidized or diverted to gluconeogenesis, its α-amino group must come off. There are three routes, and [[transamination]] is by far the dominant one:

1. **Transamination** — an aminotransferase (PLP-dependent, so it needs [[pyridoxine (B6)]]) transfers the amino group from a donor amino acid onto an acceptor α-keto acid. The reaction's equilibrium constant is near 1, so it is freely reversible.
2. **Oxidative deamination** — releases the amino group as free ammonia; **glutamate dehydrogenase (GDH)** is the key liver enzyme, converting glutamate → α-ketoglutarate + NH₃ using NAD(P)⁺.
3. **Amino acid oxidase / non-oxidative deamination** — minor routes for select substrates (e.g., serine dehydratase, discussed under the pyruvate family below).

**Key transaminase reactions (know these three pairs cold):**

- General: amino acid + α-ketoglutarate ⇌ α-keto acid + **glutamate**
- **AST/GOT** (aspartate transaminase): aspartate + α-KG ⇌ oxaloacetate + glutamate — liver, heart, muscle
- **ALT/GPT** (alanine transaminase): alanine + α-KG ⇌ pyruvate + glutamate — mainly liver

α-ketoglutarate/glutamate is the universal transamination pair in essentially every tissue. Pyruvate/alanine matters especially in muscle, which has high glycolytic flux.

**Tissue distribution matters clinically.** Humans lack (or nearly lack) transaminases for lysine, threonine, proline, and histidine. **Branched-chain amino acid (BCAA) transaminase is essentially absent from liver** but highly expressed in muscle, brain, kidney, and intestine — so BCAA catabolism happens in extrahepatic tissue, not liver (brain specifically can use valine and isoleucine as fuel). In muscle, amino groups stripped from BCAA are handed to α-ketoglutarate and pyruvate, generating **glutamate → glutamine** and **alanine** — the two least toxic circulating carriers of nitrogen, and the basis of the glucose-alanine cycle discussed in section 9.

**Direction of GDH flux is state-dependent:** in energy-deficient states (high ADP/GDP, active protein catabolism), the reaction runs glutamate → α-KG to feed gluconeogenesis/TCA. In energy-rich states (active TCA cycle, high ATP/GTP/NADPH), flux favors the reverse, sparing amino acids from catabolism.

---

## 3. Ammonia metabolism and the urea cycle

Free ammonia is neurotoxic, which is why the body invests heavily in [[urea cycle]] machinery to package nitrogen for excretion.

### Ammonia intoxication (hyperammonemia → encephalopathy)

Rising NH₃ in astrocytes drives glutamate → glutamine (via glutamine synthetase), depleting glutamate and pulling the Krebs cycle intermediate α-ketoglutarate down with it. This slows the malate–aspartate shuttle and the [[electron transport chain]], dropping ATP synthesis. Simultaneously, glutamine accumulation causes astrocyte swelling (osmotic imbalance → brain edema), and increased GABA synthesis raises GABAergic tone. The net result is cell death and hepatic/uremic-type **encephalopathy** — this is the mechanistic chain worth memorizing for hyperammonemia questions.

### The urea cycle (ornithine cycle)

Discovered by Hans Krebs (1932, also of [[Krebs Cycle]] fame — Nobel Prize 1953). It spans mitochondria and cytosol:

- **CPS-I** (carbamoyl phosphate synthetase I, mitochondrial) — the committed, rate-limiting step, condensing NH₃ + HCO₃⁻ + 2 ATP → carbamoyl phosphate. (Contrast with **CPS-II**, the cytosolic enzyme for pyrimidine biosynthesis — a classic exam distractor.)
- Carbamoyl phosphate + ornithine → **citrulline** (mitochondrial, via OTC)
- Citrulline + aspartate → **argininosuccinate** (cytosolic)
- Argininosuccinate → **arginine** + **fumarate** (this fumarate is the direct link back into the [[Krebs Cycle]] — a favorite "which molecule bridges the TCA cycle and urea cycle" question, answer: fumarate)
- Arginine → **urea** + **ornithine** (via arginase, which has a high Km for arginine, so basal arginine levels are not rapidly converted)

**Regulation:** N-acetylglutamate (NAG), synthesized by NAGS from glutamate + acetyl-CoA (itself activated by arginine), is an essential allosteric activator of CPS-I. Glutamine, aspartate, and acetyl-CoA levels tune NAG synthesis up or down. Glucagon and glucocorticoids upregulate urea cycle enzyme expression; high-protein diets, starvation, and energy depletion all increase urea cycle flux.

**Why arginine is conditionally essential:** the urea cycle is fully active in adults, so arginine synthesis suffices — but it is less active in newborns, making arginine essential in infancy.

**Summary stoichiometry:** NH₄⁺ + CO₂ + 3 ATP + aspartate + 2 H₂O → urea + fumarate + 2 ADP + 2 Pi + AMP + PPi (net cost = 4 high-energy phosphate bonds). Two amino groups are disposed of per urea molecule — one from free NH₃/CO₂, one from aspartate's amino group. Fumarate re-enters the TCA cycle, is converted to malate then oxaloacetate; two-thirds of that OAA is shunted to PEP for gluconeogenesis (or recycled back to aspartate for another turn of the cycle), one-third continues through the TCA cycle proper.

> **Clinical correlate:** Urea cycle enzyme deficiencies cause hyperammonemia of graded severity. **CPS-I deficiency** (the first, most upstream step) tends to be the most severe. OTC deficiency is the most common overall (X-linked). Argininosuccinate synthetase deficiency causes citrullinemia; argininosuccinate lyase deficiency causes argininosuccinic aciduria.

---

## 4. Metabolism of pyruvate-family amino acids

Amino acids whose carbon skeleton collapses to a 3-carbon unit (like [[pyruvate]]) — **alanine, serine, cysteine, glycine, and tryptophan** — feed in at the pyruvate entry point. First, the master classification:

### Glucogenic vs. ketogenic amino acids

||Glucogenic|Glucogenic & Ketogenic|Ketogenic only|
|---|---|---|---|
|Non-essential|Ala, Gly, Ser, Pro, Asn, Asp, Gln, Glu, Arg, Cys|Tyr|—|
|Essential|Met, His, Val|Trp, Ile, Phe, Thr|**Lys, Leu**|

Mnemonic for the purely/partly ketogenic essential amino acids: **WIFTY** = **W**-Trp, **I**-Ile, **F**-Phe, **T**-Thr, plus pure ketogenic **Lys** and **Leu**. Only lysine and leucine are _exclusively_ ketogenic — their keto-acid counterparts cannot enter gluconeogenesis or help lower blood ammonia via the usual carbon-skeleton routes, which is a recurring board-style distractor.

### Individual pathways worth knowing

- **Cysteine** → pyruvate + sulfite (further oxidized to sulfate, then activated as PAPS for sulfonation reactions) or converted to **taurine**.
- **Serine** → pyruvate via **serine dehydratase** (PLP-dependent, non-oxidative deamination), releasing NH₄⁺.
- **Glycine–serine interconversion** runs through **SHMT** (serine hydroxymethyltransferase), which requires [[folate (B9)]] and feeds the **thymidylate synthase (TS)** cycle for dTMP/DNA synthesis. A defect anywhere in this folate cycle impairs DNA synthesis and produces **megaloblastic anemia** (see [[megaloblastic anemia]]). This is also the pharmacology link: **5-fluorouracil inhibits TS**, and **methotrexate inhibits DHFR** — both exploited in cancer and antimalarial chemotherapy.
- **Glycine** can also be cleaved to CO₂ by the glycine cleavage enzyme (THF-dependent) or transaminated to **glyoxylate**. A low-Km transaminase normally keeps glyoxylate low; if defective, glyoxylate accumulates and can crystallize as **kidney stones** (oxalate stones).
- **Tryptophan** → alanine + acetoacetyl-CoA (ketogenic branch), via **tryptophan dioxygenase** (needs O₂ and Fe²⁺) as the first step. Tryptophan is also the precursor for **[[niacin (B3)]]** (NAD⁺/NADP⁺) and for serotonin/melatonin (section 10); its degradation requires [[pyridoxine (B6)]] and [[riboflavin (B2)]]. The **tryptophan loading test** measures downstream metabolites (e.g., xanthurenate) to distinguish true niacin deficiency from a B6-dependent block in the kynurenine pathway.

---

## 5. Metabolism of α-ketoglutarate-family (TCA-family) amino acids, part 1

Five-carbon amino acids — **glutamate, glutamine, proline, arginine, histidine** — funnel into the TCA cycle at α-ketoglutarate.

- **Glutamine ⇌ glutamate ⇌ α-ketoglutarate**, via **glutaminase** and **glutamate dehydrogenase**. **Glutaminolysis** is a major energy/nitrogen source for rapidly dividing cells — enterocytes, colonocytes, lymphocytes, thymocytes, wound-healing tissue, and tumor cells — and it is strongly upregulated in **acidosis** as part of renal acid-base control (see section 9).
- **Proline and arginine** both funnel to glutamate via **glutamate semialdehyde** (proline's conversion is spontaneous once the ring opens); arginine is also degraded through **arginase** as part of the urea cycle itself.
- **Histidine** — major pathway via **histidase** → ultimately glutamate, passing through the intermediate **N-formiminoglutamate (FIGLU)**, which is the classic **biomarker for folate deficiency** (the histidine-loading test). A minor transamination route yields imidazole pyruvate.

---

## 6 & 7. Oxaloacetate- and fumarate-family amino acids

- **Aspartate/asparagine → oxaloacetate.** Asparaginase converts asparagine to aspartate, and aspartate transaminase converts aspartate to OAA.
- **Phenylalanine/tyrosine → fumarate** (plus acetoacetate — making this pathway both glucogenic and ketogenic).
    - **Phenylalanine hydroxylase** (requires the **biopterin (BH₄)** cofactor, itself synthesized from GTP) converts phenylalanine → tyrosine.
    - Tyrosine is transaminated (PLP) to a keto acid; downstream, **homogentisate oxidase** normally clears homogentisate. A defect causes **alkaptonuria** — dark urine on air exposure, later connective-tissue pigmentation and arthritis from oxidized homogentisate polymers.
    - Final products: **fumarate + acetoacetate**.

> **Clinical correlate — PKU:** phenylalanine hydroxylase deficiency → **phenylketonuria**. Features: fair skin/hair/eyes (reduced melanin, since tyrosine synthesis is starved), a musty odor to breath/skin/urine (phenylacetate), and neurological impairment/seizures if untreated. Management is a low-phenylalanine diet with **tyrosine supplementation** (since tyrosine becomes conditionally essential) and avoidance of **aspartame** (a phenylalanine-containing sweetener). Biopterin itself is not a vitamin, but supports tyrosine, dopamine, and 5-hydroxytryptophan synthesis, ether-lipid conversion, and NO production from arginine — so biopterin-recycling defects mimic PKU biochemically even with normal PAH.

---

## 8. Succinyl-CoA family amino acids: methionine and the BCAAs

**Methionine metabolism and the methionine (SAM) cycle:**

1. Methionine adenosyltransferase converts methionine → **S-adenosylmethionine (SAM)**, the universal methyl donor.
2. SAM donates its methyl group (via methyltransferases) → **S-adenosylhomocysteine (SAH)** → **homocysteine**.
3. Homocysteine has two fates:
    - **Remethylation** back to methionine via **methionine synthase**, which requires both [[folate (B9)]] and [[cobalamin (B12)]]. Because this cycle only _recycles_ methionine and never creates it net, methionine remains an essential amino acid.
    - **Transsulfuration**: homocysteine + serine → **cystathionine** (cystathionine β-synthase, PLP-dependent) → cysteine + α-ketobutyrate (cystathionine γ-lyase, PLP-dependent). This is the elegant summary point: _the carbon skeleton of cysteine comes from serine, while the sulfur comes from methionine._ Cysteine feeds back to inhibit cystathionine β-synthase.
4. α-ketobutyrate → **propionyl-CoA** → **succinyl-CoA**, a step requiring both **biotin** ([[biotin (B7)]]) and **vitamin B12**.

**Homocysteine toxicity:** elevated homocysteine is oxidizing and damages vascular endothelium, contributing to **atherosclerosis**; **hyperhomocysteinemia** is lowered by supplementing B6, B12, and folate — directly relevant to the earlier pre-question about lowering cardiovascular risk metabolites.

**Thymidylate synthase (TMP) cycle** ties together folate, B12, methionine, glycine, and serine to convert dUMP → dTMP for DNA synthesis; deficiency of folate or B12 here again produces **megaloblastic anemia**.

**Branched-chain amino acids (Val, Leu, Ile):**

1. **Branched-chain aminotransferase** (extrahepatic — muscle, not liver) removes the amino group.
2. **Branched-chain keto acid dehydrogenase** then oxidatively decarboxylates the resulting keto acids. Deficiency of this enzyme causes **maple syrup urine disease (MSUD)** — accumulated branched-chain keto acids give urine a sweet, "maple syrup" smell.
3. Final products: leucine → acetyl-CoA + acetoacetyl-CoA (purely ketogenic); isoleucine → acetyl-CoA + succinyl-CoA; valine → succinyl-CoA (both glucogenic, or glucogenic+ketogenic for Ile).

---

## 9. Non-essential amino acid biosynthesis (brief review)

- **Glutamate/glutamine:** α-ketoglutarate → glutamate (glutamate dehydrogenase or transamination) → glutamine (glutamine synthetase). Upregulated in liver during acidosis to supply the kidney with glutamine for ammonia handling.
- **Aspartate/asparagine:** oxaloacetate → aspartate (transamination) → asparagine (asparagine synthetase), with the side-chain amide nitrogen donated from glutamine's side chain.
- **Serine/glycine:** glucose → 3-phosphoglycerate → serine → glycine (via SHMT, looping back to the folate cycle above).

---

## 10. Intertissue relationships in amino acid metabolism

This section is really the "systems integration" layer that ties [[amino acid metabolism]] to whole-body physiology across post-prandial, fasting, and acid-base states — worth cross-linking with [[Krebs Cycle]] and [[gluconeogenesis]].

**Baseline tissue rules:**

- α-KG/glutamate is the universal transamination pair everywhere; OAA/aspartate and pyruvate/alanine dominate specifically in liver and muscle, respectively.
- BCAA transaminase is absent from liver, abundant in muscle, brain, kidney, intestine — so BCAA catabolism is extrahepatic. The brain specifically can burn valine and isoleucine as fuel.
- **Glutamine and alanine are the least toxic circulating nitrogen carriers.** Glutamine is the primary fuel for the kidney and for rapidly dividing cells; its carbon skeleton (α-KG) can be oxidized for energy or converted to PEP → glucose, alanine, or serine.

**Post-prandial state:** after a high-protein meal, gut-derived amino acids (glutamine, aspartate, glutamate — heavily extracted by the intestine, whose primary fuel is glutamine) and alanine flow to the liver, which handles catabolism/biosynthesis and gluconeogenesis as needed; BCAAs largely bypass the liver (only ~20% is extracted there vs. ~65% reaching peripheral tissue) to be used by muscle, brain, and other tissues.

**Fasting/starvation state:** muscle proteolysis releases amino acids, especially BCAA, which are transaminated locally to generate alanine and glutamine for export. Alanine travels to the liver as a **gluconeogenic** substrate (glucose-alanine cycle, below); glutamine travels to the kidney (ammoniagenesis) and to the intestine/immune cells as fuel. The brain relies on glucose but can also directly oxidize valine and isoleucine.

**Glucose-alanine cycle (Cahill cycle):** muscle transaminates pyruvate (from glycolysis) using amino groups stripped off catabolized amino acids, generating **alanine**, which travels to the liver; the liver deaminates alanine back to pyruvate (feeding gluconeogenesis) and disposes of the amino group via the urea cycle. This is distinct from the **Cori cycle** (glucose–lactate), which is about anaerobic energy production rather than nitrogen transport — a classic exam pairing/contrast.

**Acidosis:** the kidney needs ammonia (NH₃) to buffer excess H⁺ in the urine. Perivenous liver tissue upregulates **glutamine synthetase** to supply glutamine; the kidney then runs **glutaminolysis** (glutaminase + glutamate dehydrogenase) to liberate NH₃ for buffering, while the resulting α-KG carbon skeleton supports renal gluconeogenesis.

**Glutamate–GABA–glutamine cycling in brain:** neuronal glutamate can be decarboxylated by **glutamate decarboxylase (GAD)** to form the inhibitory neurotransmitter **GABA**. Both glutamate and GABA released synaptically are taken up by astrocytes and converted to glutamine (via glutamine synthetase) for recycling back to neurons — the same enzyme and logic that goes awry in the hyperammonemia cascade described in section 3.

---

## 11. Other macromolecules built from amino acids

A useful "amino acids as precursors" table for rapid recall:

| Product                   | Amino acid precursor(s)                                                               | Key notes                                                                                                                                                                                                                                                                    |
| ------------------------- | ------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Nitric oxide (NO)**     | Arginine                                                                              | Via **NO synthase** (nNOS-neurons, eNOS-endothelium, iNOS-immune/infection-inducible); short-lived radical signal, vasodilator                                                                                                                                               |
| **Creatine / creatinine** | Arginine + glycine + methionine (SAM as methyl donor)                                 | Synthesized kidney→liver→transported to muscle; creatine is a phosphagen for rapid ATP regeneration; creatinine output is roughly constant and reflects muscle mass — the basis of creatinine clearance as a kidney-function marker                                          |
| **Carnitine**             | Lysine (methylated by SAM-dependent lysine methyltransferase) + glycine cofactor step | Made mainly in liver/kidney; poorly-absorbed oral carnitine can be converted by gut bacteria to **trimethylamine (TMA)** — fishy odor — then oxidized to **TMAO**, a pro-atherogenic compound                                                                                |
| **Niacin (B3)**           | Tryptophan                                                                            | De novo synthesis explains why isolated tryptophan deficiency (or B6/B2 cofactor deficiency in the pathway) can mimic niacin deficiency — see [[niacin(B3) deficiency]]                                                                                                      |
| **Serotonin & melatonin** | Tryptophan                                                                            | Serotonin = mood/appetite/GI neurotransmitter; melatonin = sleep-wake hormone. High-tryptophan meals promote sleepiness. **Carcinoid tumors** overproduce serotonin from tryptophan, which can secondarily cause niacin/B3 deficiency by diverting the shared precursor pool |
| **Catecholamines**        | Tyrosine                                                                              | → dopamine → norepinephrine → epinephrine, all BH₄-dependent steps; epinephrine synthesis additionally needs SAM as methyl donor                                                                                                                                             |
| **Melanin**               | Tyrosine                                                                              | Eumelanin (black/brown) vs. pheomelanin (red/yellow); glutathione inhibits tyrosinase (skin-lightening); arbutin and thiamidol are tyrosinase inhibitors (thiamidol chelates the enzyme's active-site Cu⁺); melasyl works differently, scavenging melanin-precursor quinones |
| **Glutathione (GSH)**     | Glutamate (via γ-amide linkage) + cysteine + glycine                                  | A tripeptide, not a standard peptide bond at the glutamate end; functions as a reducing agent, drug-conjugation handle (phase II metabolism), amino acid transport shuttle, enzyme cofactor, and a safe storage form of cysteine                                             |
| **Histamine**             | Histidine                                                                             | Via **histidine decarboxylase** (PLP-dependent); bacterial conversion of histidine-rich fish (scombroid species) that has not been properly refrigerated causes **scombroid poisoning**, a histamine-toxicity syndrome that mimics allergy                                   |

---

## Quick-reference tables for last-minute review

### Essential vs. non-essential amino acids

**Essential:** Trp, Phe, Met, Thr, Val, Leu, Ile, Lys, His, Arg Mnemonic: _"Try THis VIP MaLL"_ = Trp-Thr-His-Val-Ile-Phe-Met-Leu-Lys (His and Arg are the two "conditionally/semi-essential" outliers worth flagging separately — Arg because urea cycle activity is adult-sufficient but infant-insufficient; His because gut microbiota can supply it in adults).

**Non-essential and their carbon-skeleton origin:** Gly ← Ser · Ala ← Pyruvate · Ser ← 3-phosphoglycerate · Cys ← Ser + Met · Asp ← OAA · Asn ← Asp · Glu ← α-KG · Gln ← Glu · Pro ← α-KG · Tyr ← Phe

### Amino-acid-to-entry-point map

|Entry point|Amino acids|
|---|---|
|**Pyruvate**|Ala, Ser, Cys, Gly, Trp|
|**α-ketoglutarate**|Glu, Gln, Pro, Arg, His|
|**Oxaloacetate**|Asp, Asn|
|**Fumarate**|Phe, Tyr|
|**Succinyl-CoA**|Met, Val, Ile, Thr (minor)|
|**Acetyl-CoA / Acetoacetyl-CoA (purely ketogenic)**|Leu, Lys|

### High-yield disease list from this lecture

- **Hyperammonemia / urea cycle disorders** (CPS-I deficiency most severe; OTC deficiency most common)
- **Phenylketonuria (PKU)** — phenylalanine hydroxylase deficiency
- **Alkaptonuria** — homogentisate oxidase deficiency
- **Maple syrup urine disease (MSUD)** — branched-chain keto acid dehydrogenase deficiency
- **Megaloblastic anemia** — folate/B12 deficiency disrupting the glycine-serine-folate and methionine/TMP cycles (see [[megaloblastic anemia]])
- **Hyperhomocysteinemia / atherosclerosis risk** — impaired homocysteine remethylation or transsulfuration (B6/B12/folate-responsive)
- **Scombroid poisoning** — bacterial histidine → histamine in improperly refrigerated fish
- **Carcinoid syndrome** — tryptophan diverted to serotonin, causing secondary niacin deficiency
- **Kidney stones (oxalate)** — glyoxylate accumulation from defective glyoxylate transaminase

---

## Suggested next steps for the vault

- This page assumes stub pages exist or will exist for [[transamination]], [[urea cycle]], [[folate (B9)]], [[cobalamin (B12)]], [[niacin (B3)]], [[pyridoxine (B6)]], [[biotin (B7)]], [[ubiquitin]], [[proteasome]], and [[megaloblastic anemia]] — worth checking that each carries a short cross-reference back to this page under a "connects to amino acid metabolism" section.
- Consider a dedicated `PKU.md` and `MSUD.md` clinical-correlate note if you want disease-specific pages separate from this lecture summary (parallel to how [[Tay-Sachs disease]] and [[Gaucher disease]] are handled elsewhere in the vault).
- An Excalidraw diagram mapping the five carbon-skeleton entry points (pyruvate / α-KG / OAA / fumarate / succinyl-CoA) onto the [[Krebs Cycle]] would pair well with the existing "all metabolism pathway" master diagram, visually completing the macronutrient integration you've already built for carbohydrate and lipid metabolism.