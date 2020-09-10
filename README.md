# covid_and_safegraph

The jupyter notebook automatically downloads the latest county-level covid confirmed case and death datasets from the Johns Hopkins Dataset.

It has several functions to downsize the data into a 2D numpy array in which row i corresponds to state i or county i.

The data is for each day, so it would need to be combined into weekly data.

The data is cumulative meaning that a count undicates the number of cases up to (and including) a given  day.
