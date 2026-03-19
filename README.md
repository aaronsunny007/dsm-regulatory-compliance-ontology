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

## Project Structure
- ontology/ → OWL file
- screenshots/ → output and reasoning proof