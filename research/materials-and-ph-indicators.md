# Dermasense — Materials and pH-Indicator Research

**Project:** Dermasense — proposed pH-responsive hydrogel wound dressing  
**Document type:** Working research note for an academic product-design project  
**Research status:** Literature-informed design exploration; not a validated product specification  
**Last reviewed:** 19 October 2026

## 1. Purpose of This Document

This document records the material and sensing options worth investigating for Dermasense. It focuses on hydrogel matrices, colour-changing pH indicators, methods of keeping the indicator contained, possible layer architecture, and the testing needed before the concept could be considered for any real wound-care use.

The research supports a cautious starting direction, not a claim that one material has already been proved best. The final choice will depend on the intended wound type, the required pH response range, fluid-handling performance, colour visibility, dye release, mechanical properties, manufacturability, and biocompatibility. Hydrogel-dressing reviews emphasize that these properties depend strongly on the composition and cross-linking method of the particular material system [1].

## 2. What the Sensing System Is Intended to Measure

The proposed measurable signal is **local wound-fluid pH**. A pH indicator changes its colour as the acidity or alkalinity of its immediate environment changes. The intention is to make that change visible through a dressing without using a battery or electronic sensor.

Wound pH is relevant to research on healing, but it is not a stand-alone infection test. The pH of a wound can vary with the stage of healing, wound type, exudate, local tissue conditions, treatments, and other factors. A review of wound-monitoring research notes that non-infected wounds can also show pH fluctuations; therefore, pH changes are not specific to bacterial infection [2]. A systematic review of human wound studies also found that the available evidence was not strong enough to confidently recommend pH, exudate composition, or temperature as reliable predictors of healing outcomes [3].

For that reason, Dermasense should currently be described as a **proposed pH-responsive visual wound-monitoring concept**. A colour change could eventually be investigated as a reason to seek professional advice, but it must not be presented as a diagnosis. No colour change must not be interpreted as proof that a wound is healthy.

## 3. Candidate pH Indicators

Two indicators have been identified in the Dermasense design notes: bromothymol blue (BTB) and phenol red. Their standard solution colours provide a starting point for laboratory comparison, but the exact colour response can change after a dye is incorporated into a polymer matrix. The final hydrogel must therefore be calibrated as a material of its own, rather than relying only on a colour chart for the free chemical.

### 3.1 Bromothymol Blue (BTB)

Bromothymol blue is an acid–base indicator that is yellow in acidic conditions, green near neutral pH, and blue in more alkaline conditions. Its commonly reported transition interval is approximately pH 6.0–7.6; some chemical references give a lower boundary around pH 5.8, so the precise interval should be confirmed for the selected grade and test method [4].

**Why it is worth studying for Dermasense**

- Its transition is close to the near-neutral range, making it a reasonable candidate to screen for a visual pH-response concept.
- The colour change is visible, so it fits the electronics-free design objective.
- A 2025 study investigated BTB in an electrospun nanofibrous hydrogel system based on PVA and a specialised phosphine-oxide-based cationic hydrogel. The authors reported that a cationic complexing agent reduced BTB release to below 10% under their test conditions, and their keratinocyte cytotoxicity assessment did not show toxic effects for the tested material [5].

**Limitations and cautions**

- The published result belongs to the formulation and test conditions used by those authors; it does not establish that BTB is safe in an untested Dermasense formulation.
- A free dye may migrate out of a wet dressing. Containment and leaching need to be measured, not assumed.
- A colour change indicates pH change, not the identity of a microorganism or a confirmed infection.
- A colour that is easy to distinguish in a clear buffer may be harder to interpret in the presence of proteins, blood, salts, coloured medicines, or varied lighting.

**Assessment:** BTB is a sensible first candidate for comparative bench research, but it is not yet a final selection for Dermasense.

### 3.2 Phenol Red

Phenol red is a commonly used acid–base indicator. PubChem describes a colour transition from yellow below approximately pH 6.8 to bright pink above pH 8.2, with intermediate colours across the transition interval [6]. In wound-dressing research, Liu and colleagues modified phenol red with a methacrylate group so it could be incorporated into an alginate/polyacrylamide hydrogel network. They removed unattached dye during preparation and reported matrix-specific colour changes from yellow at pH 5–7, to orange at pH 7.4–8, and red at pH 9 [7].

**Why it is worth studying**

- It has a documented response over a more alkaline range than BTB.
- There is a published example of phenol red being chemically modified and incorporated into a hydrogel to reduce dye leaching [7].
- The published patch study measured material properties including swelling, mechanical behaviour, and water-vapour transmission, which are relevant categories for future Dermasense testing.

**Limitations and cautions**

- Its transition may be less useful if the intended target is a smaller change closer to neutral pH; suitability must be decided experimentally rather than from the nominal interval alone.
- Phenol red has been reported to show weak estrogen-like activity in certain cell-culture experiments. That finding does not by itself establish harm from a wound dressing, but it reinforces why exposure, dye release, and biological safety cannot be ignored [8].
- Chemically modifying phenol red and producing a controlled hydrogel requires appropriate chemistry expertise, equipment, purification, and testing. The published procedure should not be treated as an informal student-level recipe.

**Assessment:** Phenol red is a useful comparison candidate. It should not be assumed safer or less safe than BTB without formulation-specific evidence.

### 3.3 Indicator Comparison

| Factor | Bromothymol blue (BTB) | Phenol red | What Dermasense needs to establish |
| --- | --- | --- | --- |
| Approximate standard transition interval | About pH 6.0–7.6; some sources start near 5.8 [4] | About pH 6.8–8.2 [6] | The actual response interval in the finished matrix |
| Typical colour progression in solution | Yellow → green → blue [4] | Yellow → orange/red, with bright pink at strongly alkaline end [6] | Readable, repeatable colours after incorporation into the material |
| Related wound-dressing research | BTB studied in a PVA/specialised cationic-hydrogel nanofibre system [5] | Modified phenol red studied in alginate/polyacrylamide hydrogel [7] | Whether a suitably safe and practical material system can be developed for this project |
| Main issue to assess | Dye containment, leaching, and matrix-specific response | Dye containment, leaching, and biological safety assessment | Exposure and performance in the intended configuration |
| Current Dermasense status | Candidate only | Candidate only | No final selection or validated formulation |

The candidate with the most convenient nominal pH interval is not automatically the best indicator. Colour contrast, leaching, stability, matrix compatibility, test repeatability, and the intended use all matter.

### 3.4 Other Indicators

Other synthetic or naturally derived pH-responsive dyes appear in the wound-sensing literature [9]. They may be considered later if BTB and phenol red do not meet the required performance or safety criteria. Plant-derived pigments can be affected by source variability, light, temperature, oxidation, and matrix chemistry. A mixed "universal indicator" approach would also make calibration, containment, and safety evaluation more complicated.

For the first comparison, it is more practical to study BTB and phenol red individually instead of adding several indicators at once.

## 4. Candidate Hydrogel Matrices

Hydrogels are three-dimensional polymer networks that can retain water. Depending on their formulation, they can help manage wound fluid and maintain a moist environment. They are not all interchangeable: their absorption, strength, adhesion, permeability, degradation, and biological interaction depend on polymer selection and cross-linking [1].

### 4.1 Polyvinyl Alcohol (PVA)

PVA is a synthetic, water-compatible polymer used in hydrogel research. Physical methods such as freeze–thaw processing and chemical cross-linking can produce networks with different mechanical and swelling properties [1]. PVA is a candidate for a film or hydrogel matrix because it can be formed into continuous structures and blended with other polymers.

**Potential advantages to investigate**

- Ability to form films or hydrogel structures.
- Adjustable swelling and mechanical properties through formulation and processing.
- Use in published hydrogel and pH-responsive dressing research, including the BTB system discussed in Section 3.1 [1, 5].

**Questions and limitations**

- The properties of pure PVA may not meet all requirements for a wound dressing without modification.
- Cross-linking, residual processing chemicals, swelling, flexibility, and sterilization compatibility need evaluation.
- PVA should not be assumed to be antimicrobial or clinically suitable simply because it is used in biomaterials research.

**Dermasense direction:** Keep PVA as one of the candidate matrices for comparison. No exact concentration, cross-linking process, or production recipe has been selected.

### 4.2 Alginate

Alginate is a polysaccharide commonly studied for hydrogel and wound-dressing applications. It can form a gel through ionic cross-linking, commonly involving calcium ions [1]. A 2017 pH-indicating hydrogel study used an alginate/polyacrylamide double network with chemically modified phenol red [7]. This provides a published example of a pH-responsive alginate-containing matrix, but it is not the same formulation proposed for Dermasense.

**Potential advantages to investigate**

- Suitability for forming a hydrated gel.
- Potential use in a wound-fluid-interacting layer.
- Availability of published wound-dressing and sensing research for comparison [1, 7].

**Questions and limitations**

- Ionic composition and fluid exposure can affect gel structure and mechanical performance.
- Absorption, gel integrity, and indicator response must be measured using relevant test fluids.
- A formulation containing another polymer, a dye derivative, or residual processing chemicals needs its own safety assessment.

**Dermasense direction:** Compare alginate as a candidate fluid-interacting matrix or layer. Its role should be selected only after absorbency, stability, and compatibility have been evaluated.

### 4.3 Gelatin

Gelatin is a protein-derived material studied in hydrogel and wound-dressing systems [1]. It can be combined with other polymers to adjust material properties. However, the source, purification, formulation consistency, processing conditions, and stability of the final material need consideration.

Gelatin is a possible blend component for future screening, but a particular PVA/gelatin recipe has not been validated for Dermasense.

**Important literature distinction:** The 2025 BTB nanofibre paper cited here describes its PVA/Gel-A system as PVA combined with a specialised phosphine-oxide-based cationic hydrogel. The abbreviation "Gel-A" should not be interpreted as proof that the study used ordinary gelatin. Its performance results should not be cited as direct evidence for a PVA/gelatin formulation [5].

### 4.4 Chitosan and Collagen

Chitosan and collagen are discussed in the broader wound-dressing literature [1, 10]. They may offer useful properties in particular formulations, but adding them can introduce further variables, such as material-source consistency, processing, mechanical performance, and biological response.

They are not required for the initial indicator comparison. They should be considered only if a clear design requirement or comparative evidence justifies their inclusion.

### 4.5 Initial Matrix-Screening View

| Material | Possible role to investigate | Important checks | Current status |
| --- | --- | --- | --- |
| PVA | Film-forming or hydrogel matrix | Swelling, flexibility, cross-linking, extractables, sterilization compatibility | Candidate |
| Alginate | Fluid-interacting hydrogel layer or blend component | Gel stability, fluid uptake, ion sensitivity, mechanical properties | Candidate |
| Gelatin | Blend component for adjusting material properties | Source consistency, stability, processing, biological assessment | Optional candidate |
| Chitosan or collagen | Later formulation options if needed | Added complexity and formulation-specific performance/safety | Not needed for first comparison |

These are material-screening options, not a finalized stack. A final construction might use a single composite layer or multiple separate layers; the decision should follow test results.

## 5. Indicator Immobilization and Dye-Leaching Control

An indicator can be placed in a material by several approaches. The central requirement for Dermasense is that the dye must respond to the local pH while remaining contained to an acceptable level. Simply soaking a dressing in free dye would not demonstrate that the indicator is safely retained.

Possible approaches discussed in published smart-dressing research include:

1. **Physical entrapment:** Hold the dye inside a polymer network. This is conceptually simple, but retention depends on the network, dye chemistry, fluid exposure, and swelling.
2. **Ionic association or complexation:** Use interactions between charged components to retain the dye. The 2025 BTB research reported reduced dye release after using a cationic complexing agent in its specific PVA/Gel-A nanofibrous system [5].
3. **Covalent attachment:** Chemically modify the indicator so it can attach to the polymer network. The 2017 phenol-red hydrogel study used methacrylate modification and copolymerization to limit dye leaching [7].
4. **Encapsulation:** Place the indicator in a carrier or particle that is incorporated into the dressing. The carrier itself would require compatibility, stability, and release assessment.

These approaches are not interchangeable. Covalent attachment requires suitable chemistry and verification that the modified indicator still gives a useful response. Physical entrapment may be easier to explore conceptually but can permit migration out of the material. The selected method must be evaluated in the final formulation.

### Why Leaching Matters

If the indicator or processing chemicals enter the wound fluid, the potential exposure could affect safety and may also change the amount of dye left in the sensing layer. Therefore, leaching is both a performance issue and a safety question. The amount released should be measured under defined conditions using a suitable analytical method; a visual observation alone is insufficient.

A reported result of "less than 10% release" in another research formulation must not be adopted as a Dermasense target without a scientific and safety-based justification. Dermasense has no established allowable leaching threshold at this stage.

## 6. Proposed Functional Architecture

The initial design concept separates fluid interaction, colour sensing, outer protection, and attachment. One possible arrangement to assess is:

```text
┌─────────────────────────────────────────────┐
│ Transparent protective top film             │
├─────────────────────────────────────────────┤
│ pH-indicator region                         │
│ Indicator contained/immobilized in matrix   │
├─────────────────────────────────────────────┤
│ Fluid-interacting hydrogel layer            │
│ Composition to be selected through testing  │
├─────────────────────────────────────────────┤
│ Adhesive border around the intended area    │
└─────────────────────────────────────────────┘
```

This is only a functional sketch. It does not establish that the layers must be arranged exactly this way or that a barrier between the indicator and the wound will always be appropriate. The fluid pathway must allow a measurable response, and the indicator must remain contained. The final design would require expert review and testing for the intended contact conditions.

The protective film should be assessed for transparency, flexibility, moisture-vapour transmission, and other properties relevant to its intended role. Do not claim that it is breathable or oxygen-permeable until those properties have been verified for the chosen material. The adhesive border should be assessed separately for adhesion, skin irritation, sensitization, residue, and removal behaviour.

## 7. Laboratory Evaluation Plan

Testing should proceed in stages, starting with material performance rather than clinical claims. Before choosing acceptance criteria, the team should define the intended use and the pH changes it actually needs to distinguish.

### 7.1 Define the Target Use

Record the intended wound type, expected fluid conditions, who would view the colour, how the information would be used, and what action a concerning result could prompt. These decisions affect indicator choice, dressing architecture, and the level of evidence needed.

### 7.2 Screen the pH Response

For each candidate matrix–indicator combination, investigate:

- The observed response range using calibrated buffer solutions.
- The colour and colour difference across the range.
- Time needed for the colour to reach a stable reading.
- Repeatability between samples and different preparation batches.
- Whether the colour change reverses when pH changes back, if reversibility matters to the intended use.
- Colour stability during storage and under different light conditions.
- Effects of temperature and matrix thickness.

Photographs should be taken under standardized lighting with consistent camera settings and a colour reference. Where available, quantitative colour analysis is preferable to relying only on human visual judgement. The pH scale and colour key must be calibrated for the final material, not drawn in advance as a clinical status chart.

### 7.3 Evaluate Fluid Interaction and Interference

Use controlled, non-clinical laboratory conditions and an appropriate simulated wound-fluid method. Examine whether the response changes in the presence of salts, proteins, blood-coloured components, or likely topical products. Record fluid uptake, swelling, fluid retention, and whether the sensing layer remains readable after exposure.

A buffer solution is a useful starting point, but success in buffer alone does not establish performance in a realistic wound-fluid environment.

### 7.4 Measure Leaching and Material Stability

Quantify dye release and, where relevant, assess residual chemicals or other extractables. Verify that the test method can detect the compounds at the relevant concentrations. Assess whether the indicator distribution, colour response, or mechanical properties change after soaking and during storage.

### 7.5 Assess Physical Properties

Depending on the proposed construction, relevant measurements may include:

- Swelling ratio and fluid absorption/retention.
- Tensile strength, elongation, flexibility, and layer uniformity.
- Integrity after exposure to simulated fluid.
- Water-vapour transmission and, if claimed, oxygen transmission.
- Transparency and colour readability through the outer film.
- Adhesive performance and removal behaviour on suitable test substrates.

The correct methods and acceptance limits should be selected with materials-science guidance. No numerical performance targets have been established for Dermasense yet.

### 7.6 Safety, Sterilization, and Shelf Life

Before any proposed real-wound use, qualified assessment would be required for relevant biological risks, including cytotoxicity, irritation, sensitization, and exposure to leachables. The exact test plan depends on the final materials, contact type, contact duration, intended use, and risk assessment. The US FDA's biocompatibility resource explains the role of ISO 10993-1 and emphasizes evaluation in the context of risk management; it is useful background, but the applicable requirements for a product marketed in India must also be checked with the relevant Indian authorities and specialists [11].

The development plan would also need to consider sterilization compatibility, package integrity, storage conditions, and shelf life. A laboratory prototype should not be put on a real wound or used by a person as a test subject.

### 7.7 Evidence Development

Only after controlled laboratory results and relevant safety work should the project assess whether further evaluation is justified. Any human or clinical study would require appropriate professional oversight, ethics approval where applicable, and compliance with regulatory requirements. Clinical performance cannot be inferred from buffer testing or a cell-culture cytotoxicity test alone.

## 8. Safety, Interpretation, and Regulatory Considerations

### 8.1 Avoid Treating pH as an Infection Diagnosis

The association between wound pH and wound status is scientifically interesting, but evidence does not support using an unvalidated pH colour change by itself to diagnose infection [2, 3, 9]. Dermasense must not tell users that a specific colour proves a wound is healthy or infected. It must not be used to decide independently to stop medication, delay care, or change treatment.

### 8.2 Avoid Generalizing Safety Results

A published study's low leaching result or lack of observed toxicity in a particular cell test applies only to the tested material and conditions [5]. It does not prove that a different dye concentration, hydrogel, adhesive, manufacturing process, sterilization method, or final product is safe.

### 8.3 Regulatory Status Depends on the Intended Purpose

In India, medical devices are regulated under the Drugs and Cosmetics Act and the Medical Devices Rules, 2017. CDSCO describes a risk-based classification system and publishes classification materials for medical devices [12]. Because Dermasense has no finalized intended use or design, this document does not assign it a device class. The classification and applicable obligations should be checked against the final intended purpose and current CDSCO guidance before making commercial or clinical claims.

### 8.4 Claims That Should Not Be Used at This Stage

Do not state that Dermasense:

- Detects or diagnoses infection accurately.
- Prevents infection or sepsis.
- Improves healing or reduces hospital visits.
- Is clinically proven, sterile, biocompatible, or safe for wound contact.
- Has a validated response time, colour threshold, shelf life, or manufacturing cost.

Appropriate current wording is: **"Dermasense is an academic concept for a proposed hydrogel wound dressing with a pH-responsive colour-indicator layer. Its materials, performance, and safety remain to be evaluated."**

## 9. Recommended Next Research Steps

1. **Set the intended use:** Specify the target wound type and clarify what a colour change is supposed to indicate.
2. **Compare the indicators:** Study BTB and phenol red individually using reliable buffer calibration, then compare their behaviour after incorporation into candidate matrices.
3. **Compare candidate matrices:** Screen PVA and alginate systems first; consider gelatin as a blend component only if it serves a clear design purpose.
4. **Evaluate containment:** Compare a practical retention strategy and measure dye leaching quantitatively.
5. **Document the results:** Record formulation identifiers, conditions, photos, measured pH, response time, colour observations, and any deviations.
6. **Review risks and standards:** Seek guidance on material safety, test selection, intended contact conditions, sterilization, and relevant regulatory requirements before considering further development.

At this stage, the goal is not to claim a working medical product. It is to find out, through traceable literature and controlled tests, whether a safe and repeatable concept is technically plausible.

## 10. Evidence Summary

| Question | What the literature currently supports | What remains unknown for Dermasense |
| --- | --- | --- |
| Can hydrogel matrices be used in wound-dressing research? | Yes. Natural and synthetic polymer hydrogels are widely researched, but properties vary by formulation [1]. | Which matrix has the right balance of swelling, strength, visibility, and safety for this design. |
| Can BTB produce a visible pH response in a hydrogel? | A 2025 study reported a BTB-containing nanofibrous hydrogel system with reduced dye release under its tested conditions [5]. | Whether an affordable, reproducible Dermasense formulation can achieve an adequate response and containment. |
| Can phenol red be incorporated into a hydrogel for colour-based pH response? | A 2017 study reported a covalently incorporated, modified phenol-red system based on alginate/polyacrylamide [7]. | Whether this chemistry is practical, safe, and necessary for the project. |
| Does wound pH reliably diagnose infection? | No. pH may provide information about the wound environment, but evidence and specificity are limited [2, 3, 9]. | Whether pH could add useful information in a defined use case after appropriate validation. |
| Is Dermasense safe for wound contact? | Not established. Published studies of other formulations cannot prove its safety. | Formulation-specific leaching, biocompatibility, irritation, sensitization, sterilization, and other assessments. |
| Is the product ready for clinical use? | No evidence in the current project establishes this. | Design verification, safety evidence, clinical evaluation as appropriate, and regulatory review. |

## 11. References

Accessed 19 October 2026. The references below are starting points for the research record. Review the full paper, methods, and limitations before relying on a finding in a design decision.

1. **Su, J. et al. (2021). "Hydrogel Preparation Methods and Biomaterials for Wound Dressing."** *Life*, 11(10), 1016. Review of hydrogel preparation methods and natural/synthetic materials for wound dressings. [Full text on PubMed Central](https://pmc.ncbi.nlm.nih.gov/articles/PMC8540918/). DOI: [10.3390/life11101016](https://doi.org/10.3390/life11101016).

2. **"Advances in non-invasive biosensing measures to monitor wound healing progression."** Review describing wound-monitoring approaches and limitations, including the lack of specificity of pH changes for bacterial infection. [Full text on PubMed Central](https://pmc.ncbi.nlm.nih.gov/articles/PMC9539744/).

3. **Power, G., Moore, Z. and O’Connor, T. (2017). "Measurement of pH, exudate composition and temperature in wound healing: a systematic review."** *Journal of Wound Care*, 26(7), 381–397. [PubMed record](https://pubmed.ncbi.nlm.nih.gov/28704150/). DOI: [10.12968/jowc.2017.26.7.381](https://doi.org/10.12968/jowc.2017.26.7.381).

4. **PubChem. "Bromothymol Blue."** Chemical identity and general indicator behaviour. [PubChem compound record](https://pubchem.ncbi.nlm.nih.gov/compound/bromothymol_blue).

5. **Banitorfi Hoveizavi, N. et al. (2025). "Colorimetric pH-responsive nanofibrous hydrogels for in vitro monitoring of wound infection."** *Journal of Materials Chemistry B*, 13, 11621–11639. Study of BTB in a PVA/specialised phosphine-oxide-based cationic hydrogel nanofibre system. The results are specific to the tested material and do not establish Dermasense performance. [Publisher article](https://pubs.rsc.org/en/content/articlehtml/2025/tb/d5tb01305d). DOI: [10.1039/D5TB01305D](https://doi.org/10.1039/D5TB01305D). [PubMed record](https://pubmed.ncbi.nlm.nih.gov/40878111/).

6. **PubChem. "Phenol Red."** Chemical identity and general pH-indicator behaviour. [PubChem compound record](https://pubchem.ncbi.nlm.nih.gov/compound/Phenol-red).

7. **Liu, L. et al. (2017). "A pH-Indicating Colorimetric Tough Hydrogel Patch towards Applications in a Substrate for Smart Wound Dressings."** *Polymers*, 9(11), 558. Reports a modified phenol-red/alginate/polyacrylamide hydrogel and its material-specific pH response. [Full text on PubMed Central](https://pmc.ncbi.nlm.nih.gov/articles/PMC6418891/). DOI: [10.3390/polym9110558](https://doi.org/10.3390/polym9110558).

8. **Berthois, Y., Katzenellenbogen, J.A. and Katzenellenbogen, B.S. (1986). "Phenol red in tissue culture media is a weak estrogen: implications concerning the study of estrogen-responsive cells in culture."** *Proceedings of the National Academy of Sciences*, 83(8), 2496–2500. Evidence about phenol red in particular cell-culture settings; it does not, by itself, quantify risk from a wound dressing. [Full text on PubMed Central](https://pmc.ncbi.nlm.nih.gov/articles/PMC323325/). DOI: [10.1073/pnas.83.8.2496](https://doi.org/10.1073/pnas.83.8.2496).

9. **"Optically pH-Sensing in smart wound dressings towards real-time monitoring of wound states: A review."** (2025). Review of optical pH-sensing agents in wound-dressing research. [PubMed record](https://pubmed.ncbi.nlm.nih.gov/40155158/).

10. **"Biomedical materials for wound dressing: recent advances and applications."** (2023). Review of materials and design considerations for modern wound dressings. [Full text on PubMed Central](https://pmc.ncbi.nlm.nih.gov/articles/PMC9924226/).

11. **U.S. Food and Drug Administration (FDA). "Biocompatibility Assessment Resource Center."** General information on biological evaluation of medical devices and risk-based use of ISO 10993-1. It is a US resource and does not replace applicable Indian requirements. [FDA resource](https://www.fda.gov/medical-devices/premarket-submissions-selecting-and-preparing-correct-submission/biocompatibility-assessment-resource-center).

12. **Central Drugs Standard Control Organisation (CDSCO), Government of India. "Medical Devices Rules."** Official Indian regulatory information. Check the current rules and device-specific classification against the final intended purpose. [CDSCO Medical Devices Rules page](https://cdsco.gov.in/opencms/opencms/en/Acts-and-rules/Medical-Devices-Rules) and [Medical Device & Diagnostics overview](https://www.cdsco.gov.in/opencms/opencms/en/Medical-Device-Diagnostics/Medical-Device-Diagnostics/).