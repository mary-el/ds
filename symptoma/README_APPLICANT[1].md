# Symptoma DS Take-Home Assessment

At Symptoma, we often compare the results produced by our symptom checker to those of our competitors. 
In this assessment, we have recreated that task with artificial data.

## Background

- Using 100 reference clinical vignettes, for which the "Actual Diagnosis" is known, we entered the symptoms (not given), into three symptom checkers. 
- We recorded the "Suggested Diagnoses" from each of the checkers alongside the "Actual Diagnosis".
- Symptom checkers do not all use the same terminology, e.g., "Ingrown Toe Nail" vs "Onychocryptosis"
- To evaluate correctness, we, therefore, use our ontology. This tells us all the alternative names for a given diagnosis.

## Task

- Evaluate the suggested diagnoses from each symptom checker for correctness.
- Produce a single visualisation (one plot) to show the relative performance. No subfigures.
- Use Python (additional libraries allowed) 
- Please spend only 2 hours maximum.

## Files

The following files should be included alongside this document.

- checker_1.csv: Output from checker 1
- checker_2.csv: Output from checker 2
- checker_3.csv: Output from checker 3
- synonyms.json: Ontology map for alternative names

## Output

Please provide the visualisation and your code. You will be evaluated on both.
