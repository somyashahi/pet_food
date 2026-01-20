# Objective: Design a simple, safe, and explainable system that helps pet parents understand pet food ingredient labels using rule-based classification and friendly explanations.

## Workflow
1.Input Parsing

Accept ingredient list text

Optional pet species (dog or cat)

Preprocessing

Clean text

Split ingredients by commas

Normalize words (lowercase, trim spaces)

Rule-Based Classification Each ingredient is matched against predefined lists:

Beneficial proteins

Common fillers

Additives / vague terms

Unknown → labeled as unclear

Explanation Generator

Uses a simple text generator function (mock LLM style)

Produces short, human‑friendly explanations

Output Builder Produces:

Ingredient categorization

Simple explanations

General suitability note

Safety disclaimer
