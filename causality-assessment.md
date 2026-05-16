# Causality Assessment Guide

## WHO-UMC Causality Assessment System

This project uses the World Health Organization Uppsala Monitoring Centre (WHO-UMC) causality assessment system to evaluate the relationship between Cyperidone exposure and reported adverse events. This system is the most widely used standardised causality assessment methodology in global pharmacovigilance.

## Assessment Categories

### Certain

All of the following criteria must be met:
- Event occurred in a plausible time relationship to drug administration
- Event cannot be explained by disease or other drugs
- Response to withdrawal is clinically plausible (positive dechallenge)
- Event is definitive pharmacologically or phenomenologically, using a satisfactory rechallenge procedure if necessary

### Probable / Likely

All of the following criteria must be met:
- Event occurred in a reasonable time relationship to drug administration
- Event is unlikely to be attributed to disease or other drugs
- Response to withdrawal is clinically reasonable (positive dechallenge)
- Rechallenge is not required

### Possible

All of the following criteria must be met:
- Event occurred in a reasonable time relationship to drug administration
- Event could also be explained by disease or other drugs
- Information on drug withdrawal may be lacking or unclear

### Unlikely

All of the following criteria must be met:
- Temporal relationship to drug administration makes a causal relationship improbable
- Other drugs, chemicals, or underlying disease provide plausible explanations

### Conditional / Unclassifiable

- Event reported as an adverse reaction
- More data are needed for proper assessment
- Additional data are being examined or requested

### Unassessable / Unclassifiable

- Report suggests an adverse reaction
- Cannot be judged because information is insufficient or contradictory
- Data cannot be supplemented or verified

## Application to Cyperidone Cases

### Case 001: Agranulocytosis

| Criterion | Assessment |
|-----------|-----------|
| Temporal relationship | Yes, onset Day 96, reasonable for haematological toxicity |
| Consistent with known pharmacology | Yes, agranulocytosis is a listed rare adverse reaction for the atypical antipsychotic class |
| Alternative explanation | None identified: no concomitant haematotoxic drugs, no prior haematological disorders, negative blood cultures |
| Dechallenge | Positive: ANC recovery commenced following drug withdrawal |
| Rechallenge | Not attempted |
| **Causality Assessment** | **Probable / Likely** |

Rationale for "Probable" rather than "Certain": Rechallenge was not performed (appropriately, given the severity of the event). Without rechallenge, "Certain" cannot be assigned. All other criteria for "Probable" are fully satisfied.

### Case 002: QTc Prolongation

| Criterion | Assessment |
|-----------|-----------|
| Temporal relationship | Yes, onset Day 72, reasonable for cardiac conduction effects |
| Consistent with known pharmacology | Yes, QTc prolongation is a listed common adverse reaction for the atypical antipsychotic class |
| Alternative explanation | Possible: family history of sudden cardiac death raises the possibility of subclinical genetic QTc predisposition |
| Dechallenge | Partial: dose reduction (not full withdrawal) resulted in QTc decrease from 478 to 452 ms |
| Rechallenge | Not applicable |
| **Causality Assessment** | **Possible** |

Rationale for "Possible" rather than "Probable": The confounding family history of sudden cardiac death introduces a plausible alternative or contributing factor that cannot be excluded without genetic testing. The partial dechallenge (dose reduction rather than full withdrawal) supports a drug-related component but does not definitively establish it.

## Complementary Assessment Frameworks

### Naranjo Algorithm (Reference)

The Naranjo Adverse Drug Reaction Probability Scale is another widely used tool. While this project uses the WHO-UMC system as primary, the Naranjo algorithm provides a numerical scoring approach that can complement the WHO-UMC categorical assessment.

| Question | Case 001 Score | Case 002 Score |
|----------|---------------|---------------|
| Are there previous conclusive reports on this reaction? | +1 | +1 |
| Did the adverse event appear after the suspected drug was administered? | +2 | +2 |
| Did the adverse reaction improve when the drug was discontinued? | +1 | 0 (dose reduced, not stopped) |
| Did the adverse reaction reappear when the drug was readministered? | 0 (not done) | 0 (not done) |
| Are there alternative causes? | -1 (none) | -1 (family history of sudden cardiac death) |
| Did the reaction reappear when a placebo was given? | 0 (not done) | 0 (not done) |
| Was the drug detected in the blood in concentrations known to be toxic? | 0 (not tested) | 0 (not tested) |
| Was the reaction more severe when the dose was increased? | 0 (single dose) | +1 (dose-response suggested) |
| Did the patient have a similar reaction to the same or similar drugs previously? | 0 (no prior exposure) | 0 (no prior exposure) |
| Was the adverse event confirmed by any objective evidence? | +1 (lab confirmed) | +1 (ECG confirmed) |
| **Total Score** | **4 (Possible)** | **4 (Possible)** |

Note: After correction, the Naranjo score for Case 002 yields "Possible" (score 4), which aligns with the WHO-UMC assessment of "Possible". Both systems converge on the same conclusion when the confounding cardiac family history is properly accounted for in the Naranjo scoring. This convergence strengthens confidence in the overall causality determination.

## Disclaimer

All assessments are fictional and performed for educational demonstration purposes. Cyperidone is not a real drug and no real adverse event data is used.
