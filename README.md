#  Pet Food Label Decoder

## Objective

Design a simplified AI-based system that explains pet food labels in a clear, safe, and human-friendly way using rule-based logic.

---

##  Workflow

1. Accept ingredient list from user  
2. Clean and split the input text  
3. Classify each ingredient using predefined rules  
4. Generate simple explanations  
5. Display suitability note and safety disclaimer  

---

## Ingredient Classification Logic

### Beneficial Ingredients
Protein sources commonly used in pet foods such as chicken, fish, lamb, and egg.

### Common Fillers
Plant-based ingredients such as corn, wheat, soy, rice, and barley that provide energy and bulk.

### Additives or Vague Terms
Ingredients such as artificial flavor, natural flavor, color, and preservatives used mainly for taste, color, or shelf life.

### Unclear Ingredients
Any ingredient not found in the predefined lists is labeled as “Unclear”.

---

## Example Input
Enter pet species (dog/cat): cat
Enter ingredient list (comma separated): Chicken meal, corn

