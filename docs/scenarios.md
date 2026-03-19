# Scenarios

This ontology includes example scenarios to demonstrate reasoning.

## Scenario 1: Benthic Habitat Loss

- Individual: Benthic_Habitat_Loss1
- Type: BenthicHabitatLoss
- isForeseen: true

Expected Result:
- Classified as EnvironmentalHarm
- NOT classified as CompensableHarm

---

## Scenario 2: Plume Toxicity

- Individual: Plume_Toxicity1
- Type: PlumeToxicity
- isForeseen: false
- isCompensatedBy: ECF1

Expected Result:
- Classified as EnvironmentalHarm
- Automatically inferred as CompensableHarm

---

## Scenario 3: Mining Activity

- Individual: MiningActivity1
- performedBy: Contractor1
- causes: Plume_Toxicity1

Expected Result:
- Demonstrates causal relationship between activity and harm
- Supports compliance and liability modelling