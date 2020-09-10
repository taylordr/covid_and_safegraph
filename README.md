# covid_and_safegraph

The jupyter notebook automatically downls the latest county-level covid confirmed case and death datas from the Johns Hopkins Dataest.

It has a few functions to downsize the data into a numpy array for a given state or county, or for all states.

The data is for each day, so it would need to be combined into weekly data.

The data is cumulative meaning that a count undicates the number of cases up to (and including) a given  day.
