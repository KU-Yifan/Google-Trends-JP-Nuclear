# Google Trends of JP Nuclear Queries

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.24393998.svg)](https://doi.org/10.5281/zenodo.24393998)

Data and code for the preprint

> **Geospatial Dynamics of Online Attention to Nuclear Power in Japan Before and After Fukushima**\
> Yifan Sun, Ken Kurosaki and Benjamin C. McLellan, Kyoto University

Preprint: [arXiv:2610.29924](https://arxiv.org/abs/2610.29924).
Archived version of this repository: [doi:10.5281/zenodo.24393998](https://doi.org/10.5281/zenodo.24393998).

## About the paper

Building public support for nuclear power requires understanding what citizens want to know, as reflected in their online searches.
The preprint uses Google Trends to map online searches about nuclear power in Japan's 47 prefectures from 2004 to 2024.

- In routine periods, search interest was significantly higher in prefectures hosting nuclear power plants, with little spillover to neighboring prefectures.
- Immediately after the Fukushima Daiichi accident of March 2011, search interest instead declined with distance from Fukushima.
- From 2012 on, the pattern centered on host prefectures returned.
- During March 2011, searches leaned toward general and live information rather than guidance on what to do, and their framing varied with distance from Fukushima.

## Contents

```text
data/                  data used in the paper's analysis
├── search_interest/
├── queries/
├── reference/         reactor status and distance from Fukushima
└── prefectures.csv    summary of each prefecture, made by notebooks/1_data_preparation.ipynb

collected_data/        files as downloaded from Google Trends
├── search_interest/
└── queries/

notebooks/             reproduce the paper's maps, statistical results and findings
├── 1_data_preparation.ipynb
├── 2_maps.ipynb
├── 3_plots.ipynb
├── 4_statistics.ipynb
└── 5_decay.ipynb
```

## Requirements

The notebooks were run with Python 3.14.6 and the following packages:
- NumPy 2.5.3
- pandas 3.0.5
- SciPy 1.18.1
- Matplotlib 3.11.1
- seaborn 0.13.2
- japanmap 0.6.0
- JupyterLab 4.6.3

## License

The code and tables in this repository are released under the [MIT License](LICENSE).
The three PDF files in `data/reference/` are copies of documents by other publishers and remain under their terms.
