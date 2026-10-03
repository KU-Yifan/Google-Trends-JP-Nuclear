This folder contains files as downloaded from Google Trends, before any processing.
The processed data used in the paper's analysis are in [`data/`](../data/).

| Folder | Contents |
|---|---|
| [`search_interest/`](search_interest/) | weekly Search Interest in 2011, one file per prefecture; the files are renamed by prefecture, with their contents unchanged |
| [`queries/comparison/`](queries/comparison/) | Google Trends comparison-mode results for the two pairs of auxiliary terms, March 2011; each row gives a prefecture and the relative share (%) of searches containing each of the two terms; the files are renamed by pair and time window, with their contents unchanged |
| [`queries/related_queries/`](queries/related_queries/) | Google Trends related queries for each of the four auxiliary terms, 11–31 March 2011, one folder per auxiliary term and one file per day; the file contents are unchanged |

The related-queries files contain the top queries and the rising queries.
The top queries are those searched most often together with the term, scaled so that the most searched query has a value of 100.
The rising queries are those whose searches increased most compared with the previous period, but they were not necessarily searched most often.
The paper used only the top queries.
