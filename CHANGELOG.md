#📌 Changelog – v2.0 Update
🔹 Symptom Checker

Expanded database with more common symptoms:

Headache → Migraine, Tension Headache, Flu, Dehydration

Stomach pain → Gastritis, Food Poisoning, Appendicitis

Diarrhea → Food Poisoning, Cholera, Stomach Infection

Vomiting → Food Poisoning, Gastritis, Migraine

Fatigue → Anemia, Depression, Hypothyroidism, Diabetes

Added keyword mapping:

"high temperature" → fever

"sadness", "blue mood" → depression

"tired" → fatigue

Improved matching logic:

Fuzzy matching (handles typos like “caughing” → coughing)

Substring matching (partial words still recognized)

Keyword replacement for common phrases

Updated analysis logic:

Uses intersection of symptoms to suggest the most likely diseases.

If no exact overlap found → shows all possible conditions.
