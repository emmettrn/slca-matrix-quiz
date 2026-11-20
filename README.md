# SLCA Product Matrix Quiz

An interactive worksheet for scoring a product with the **Environmentally Responsible Product Matrix**, the 5 × 5 streamlined life-cycle assessment (SLCA) matrix from T. E. Graedel's *Streamlined Life-Cycle Assessment* (Prentice Hall, 1998), Chapter 7 and Appendix A.

**Use it here:** https://emmettrn.github.io/slca-matrix-quiz/

The page walks you through all 25 matrix elements, scores each one from your answers, and downloads an Excel file with your results.

## How scoring works

The matrix crosses five life stages with five environmental stressors:

| | Materials Choice | Energy Use | Solid Residues | Liquid Residues | Gaseous Residues |
|---|---|---|---|---|---|
| **1. Premanufacture** | 1,1 | 1,2 | 1,3 | 1,4 | 1,5 |
| **2. Product Manufacture** | 2,1 | 2,2 | 2,3 | 2,4 | 2,5 |
| **3. Packaging & Transport** | 3,1 | 3,2 | 3,3 | 3,4 | 3,5 |
| **4. Product Use** | 4,1 | 4,2 | 4,3 | 4,4 | 4,5 |
| **5. Recycling & Disposal** | 5,1 | 5,2 | 5,3 | 5,4 | 5,5 |

For each element the quiz asks:

1. **Does the "score 0" condition apply?** If yes, the element scores 0.
2. **If not, does the "score 4" condition apply?** If yes, it scores 4.
3. **If neither applies**, you check off the checklist items your product meets. The guidelines say to assign 1, 2 or 3 by how well the product meets the checklist but give no exact rule, so the quiz uses: more than ⅔ met = 3, more than ⅓ met = 2, otherwise 1. You can override any score.

The total is the sum of all 25 elements, out of 100. Higher is better.

## The Excel file

The download has two sheets:

- **Worksheet:** each element with its score, how it was scored, your reasoning, the checklist items met, and the 0 and 4 conditions.
- **Matrix:** the 5 × 5 grid with life-stage and stressor subtotals, linked to the Worksheet by formulas, so edits in Excel update the totals.

## Notes

- Answers are saved only in your own browser (localStorage). Nothing is sent anywhere.
- The scoring criteria are condensed and paraphrased from the textbook. Check the original appendix for exact wording.
- The page is a single `index.html` file. It loads [SheetJS](https://sheetjs.com/) 0.18.5 from cdnjs to build the Excel file and IBM Plex fonts from Google Fonts.

## Running it locally

Open `index.html` in a browser. An internet connection is needed for the spreadsheet library.

## Reference

Graedel, T. E. (1998). *Streamlined Life-Cycle Assessment*. Prentice Hall.
