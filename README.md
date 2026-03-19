# Ontological Modelling of Regulatory Compliance for Deep-Sea Mining

This project models regulatory compliance in deep-sea mining using ontology-based reasoning.

## Tools Used
- Protégé
- OWL (Web Ontology Language)
- HermiT Reasoner

## Features
- Models environmental harm and compensation logic
- Automatically classifies compensable harm
- Uses reasoning for compliance decisions

## Core Logic
CompensableHarm ≡ EnvironmentalHarm AND (isForeseen = false)

## Example
- Plume_Toxicity1 → not foreseen → classified as CompensableHarm
- Benthic_Habitat_Loss1 → foreseen → not compensable
- 
## Example Scenarios

### Scenario 1: Benthic Habitat Loss
- isForeseen = true
- Result: Not compensable

### Scenario 2: Plume Toxicity
- isForeseen = false
- Result: Automatically classified as CompensableHarm

### Scenario 3: Mining Activity
- Causes environmental harm
- Performed by contractor

## Project Structure
- ontology/ → OWL file
- screenshots/ → output and reasoning proof

## Key Outcome

The ontology successfully performs automated classification of environmental harm, demonstrating how semantic technologies can support regulatory compliance analysis.

## Screenshots

### Class Hierarchy
![Class](screenshots)

### Reasoning Result
![Reasoning](screenshots)

## Future Work
- Integration with AI/LLM-based compliance assistants
