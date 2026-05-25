# Mantis Score Calculator

A simple browser-based calculator for evaluating Mantis criteria scores from JSON evaluation data.

## Usage

1. In Mantis, go to:

   ```text
   Preview Eval Responses
   ```

2. Click the three dots (`...`) and copy the response JSON.

3. Paste the JSON into the top text box of the calculator.

4. Press:

   ```text
   Load Criteria
   ```

5. The calculator will:
   - list all criteria
   - display weights and scores
   - compute:
     - total score
     - maximum possible score
     - normalized percentage score

## Editing Scores

You can manually modify any criterion score by editing the value in the corresponding **Score** box.

Examples:

```text
0 → 1
1 → 0
```

After changing scores, press:

```text
Recalculate Total
```

to update the results.

## Color Coding

- Green rows → score = `1`
- Red rows → score = `0`

## Notes

- Only **positive weights** contribute to the maximum possible score.
- Negative weights act as penalties only.
- Everything runs locally in the browser; no installation is required.
