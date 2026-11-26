# D3 — Do wealthier Estonian municipalities have better public services?

Rene Miller, Arthur Klettenberg and Oliver Proos

We examine whether residents’ work-related income is associated with public service levels in Estonia in 2024, identify departures from that relationship and group municipalities by their service profiles.

- `IDS2026_HW10_D3.ipynb` reads and validates the inputs, evaluates the regression and creates the figures.
- `Teenustasemed2024.xlsx` contains the 2024 service ratings. [Minuomavalitsus open data](https://www.minuomavalitsus.ee/avaandmed)
- `UA08_20261126-142152.csv` is the English UA08 export for 2024, with all locations, indicators and income types. [Statistics Estonia UA08](https://andmed.stat.ee/en/stat/eri-valdkondade-statistika__eksperimentaalstatistika__EUROMOD/UA08)

Place both inputs next to the notebook. With Python 3.11 or later, install the dependencies with `python -m pip install jupyter pandas numpy scipy matplotlib openpyxl`. Open the notebook in Jupyter and run **Restart Kernel and Run All Cells** from the notebook directory. If you regenerate the UA08 export, save it under the listed filename. The notebook uses a fixed seed for the cross-validation folds and for clustering.
