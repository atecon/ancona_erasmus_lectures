# Forecasting Lecture: Exercise Sheet

**Course:** Big Data Econometrics

**Instructor:** Prof. Dr. Artur Tarassow

## Context
This sheet prepares you for the next computer-lab session after Day 1 (naive and simple forecasting methods).

Your goal is to review selected forecasting examples, replicate them in Gretl, and document your experience so we can discuss results and difficulties in the lab.

## Learning Goals
- Practice replication of forecasting examples from core course resources.
- Strengthen understanding of naive and simple forecasting workflows.
- Identify practical implementation issues in Gretl and learn from peer experiences.

## Required Resources
1. Hyndman and Athanasopoulos, *Forecasting: Principles and Practice (3rd ed.)*: https://otexts.com/fpp3/
2. Gretl replication files for selected FPP chapters: https://github.com/gretl-project/forecasting_principles

## Main Task (Required)
1. Visit both resources above.
2. Select one or two forecasting examples that are feasible for replication in Gretl.
3. Run the corresponding code and try to reproduce the main result(s).
4. Record your process and outcome in short notes.

## What To Document
Please keep brief notes on the following points:
- Which chapter/section and example you selected.
- Which files/scripts you used.
- Whether replication was successful (fully, partially, or not successful).
- Difficulties encountered (for example: package dependencies, data access, path/workdir issues, syntax adjustments, interpretation issues).
- How you tried to solve these issues.
- Final result and your confidence in it.

## Optional Extension: AWM Dataset
If time permits, run a simple forecasting exercise using one macroeconomic variable from the AWM dataset in Gretl.

Use:

```hansl
open AWM_update.gdt
```

Then:
1. Choose one time series.
2. Apply one or two simple forecasting methods comparable to Day 1 examples.
3. Briefly compare forecast behavior and note any differences from textbook/replication examples.

## Bring to the Lab Session
Come prepared to share:
- Which example(s) you attempted.
- What worked well.
- What did not work and why.
- What you changed to make progress.
- One short takeaway or question for class discussion.

## Submission Format (for in-class use)
No formal report is required.
Bring your notes (bullet points are sufficient) and, if possible, the script/output files you produced.
