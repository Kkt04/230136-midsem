Toy Dataset CSVs for Shapelets Reproduction (Task 2.1).
- train_dataset.csv: 100 univariate time series (50/class 0/1, length 50).
- test_dataset.csv: 40 univariate time series (20/class 0/1, length 50).
- Columns: time_0 to time_49 (continuous values), label (0: clean sine, 1: sine + spike).
- Generated: Synthetic via numpy (seed 42); mirrors paper Sec 5.1 Lightning.
- Load: pd.read_csv(); no preprocessing.