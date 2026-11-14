# DNN Programming Assignment-2: RNN, LSTM, GRU and Transformer

**Name:** Mayur Dubey  
**Student ID:** 2026aj05405  
**Course:** Deep Neural Networks (BITS Pilani WILP)

## Chosen hyperparameters
- Problem 1 hidden size: **h = 64** (same for RNN, LSTM and GRU)
- Problem 2 model width: **d = 128** (divisible by 4 heads)
- Seeds: **42, 123, 456**

## How to run

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

2. Open and run the notebooks in order:
   - `problem1/problem1.ipynb`
   - `problem2/problem2.ipynb`

   The HAR dataset is downloaded automatically on first run.  
   Tiny Shakespeare is also downloaded automatically for the language-model task.

3. Results and figures are written to:
   - `problem1/figures/`
   - `problem2/figures/`
   - `problem2/generated_samples.txt`
   - `results.csv`

## Notes
- All recurrent cells (RNN, LSTM, GRU) and the Transformer attention / encoder blocks were implemented from scratch using matrix operations.
- Library cells (`nn.RNN`, `nn.LSTM`, `nn.GRU`) were used only for weight-copy verification and for the final training runs (as permitted).
- Subject-wise validation splits were used for the HAR experiments.
- Training was performed on CPU.

## Report
The full write-up with tables, figures and analysis is in `report.pdf`.
