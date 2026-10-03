These notebooks reproduce the paper's statistical analysis and findings.
Run `1_data_preparation.ipynb` first; the other four can then run in any order.

| Notebook | Contents |
|---|---|
| `1_data_preparation.ipynb` | builds [`data/prefectures.csv`](../data/prefectures.csv), which combines each prefecture's Search Interest, host status, border status and distance from Fukushima |
| `2_maps.ipynb` | maps of Japan showing each prefecture's Search Interest on the topic of "nuclear power plant" in each period; maps showing each prefecture's relative Search Interest in selected pairs of auxiliary terms in March 2011 |
| `3_plots.ipynb` | box plots of Search Interest by group of prefectures, such as those with and without an operable reactor, and scatter plots of Search Interest against distance from Fukushima |
| `4_statistics.ipynb` | Mann–Whitney U tests of whether Search Interest differs between groups of prefectures, such as those with and without an operable reactor, and Spearman correlations between Search Interest and distance from Fukushima |
| `5_decay.ipynb` | decay curves showing how fast Search Interest fell after the accident in 2011, among prefectures grouped by distance from Fukushima |
