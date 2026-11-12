# 2026aj05405_DNN_Assignment

BITS Pilani WILP – Deep Neural Networks Programming Assignment-2  
RNN, LSTM, GRU and Transformer

**Student ID:** 2026aj05405  
**Deadline:** Friday 14 November 2026, 11:59 PM IST

## Chosen hyperparameters (per professor clarification)

- Problem 1 hidden size `h`: 64 (same for RNN, LSTM, GRU)
- Problem 2 model width `d`: 128 (divisible by 4 heads)
- Seeds: 42, 123, 456

(Change these if you prefer different values and update the report title page + this README.)

## Folder structure

```
2026aj05405_DNN_Assignment/
├── README.md
├── requirements.txt
├── results.csv
├── report.pdf                  # ≤ 6 pages (create this yourself)
├── problem1/
│   ├── problem1.ipynb
│   └── figures/
└── problem2/
    ├── problem2.ipynb
    ├── generated_samples.txt
    └── figures/
```

## Environment

```bash
pip install -r requirements.txt
```

- Python 3.10+
- PyTorch 2.x
- Google Colab T4 GPU recommended
- Fix all seeds (random, numpy, torch)

## How to run

1. Open `problem1/problem1.ipynb` in Colab (Runtime → Change runtime type → T4 GPU).
2. Run all cells top to bottom. Save outputs.
3. Open `problem2/problem2.ipynb` and run all cells.
4. Download figures into the respective `figures/` folders.
5. Fill `results.csv` and write `report.pdf` (≤6 pages).
6. Zip the whole folder as `2026aj05405_DNN_Assignment.zip` and submit.

## Important rules (from assignment)

- From-scratch parts (MyRNNCell, MyLSTMCell, MyGRUCell, scaled dot-product attention, multi-head attention, encoder block) must be your own code.
- `nn.LSTM` / `nn.GRU` / `nn.RNN` allowed only for Problem 1 tasks 3–5 and for verification.
- No `nn.MultiheadAttention` or `nn.Transformer*` in Problem 2.
- Declare all AI tool use in the report’s AI-use statement.

## Notes

- HAR dataset and Tiny Shakespeare are downloaded inside the notebooks.
- Adding problem is generated in code.
- Total estimated run time on T4: Problem 1 a few minutes per model; Problem 2 language model ~10–15 min.
