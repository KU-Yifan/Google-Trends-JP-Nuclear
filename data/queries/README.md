This folder contains the query data behind the paper's content analysis.
To see what people searched for after the accident, the paper picked four Japanese auxiliary terms and examined Google Trends' top related queries containing each term, 11–31 March 2011.
The four terms form two pairs: an explanatory pair (とは and 情報) and an action-oriented pair (方法 and 対策).

| Auxiliary term | Meaning | Name in the paper | In file names |
|---|---|---|---|
| とは | "what is" | definition queries | `definition` |
| 情報 | "information" | update queries | `update` |
| 方法 | "method" | how-to queries | `howto` |
| 対策 | "countermeasure" | countermeasure queries | `countermeasure` |

| File | Contents |
|---|---|
| `related_<name>.csv` (4 files) | the top related queries containing each auxiliary term; one column per day (11–17 March for `howto` and `countermeasure`) |
| `shares_definition_update_<window>.csv` (4 files) | Google Trends comparison-mode results for the Search Interest of the explanatory pair, for 11–13, 14–17, 18–24 and 25–31 March; in each prefecture, the Search Interest of the two terms is normalized to add up to 100% |
| `shares_howto_countermeasure_03-11_03-17.csv` | the same comparison-mode result for the action-oriented pair, 11–17 March |

The related queries were screened by manual review, which kept only queries directly related to the disaster.
It removed everyday searches, such as "what is Facebook" and "diet methods," and queries in which the term is part of a compound noun, such as 災害対策本部 ("disaster countermeasures headquarters").
The full, unscreened lists of top related queries that Google Trends returned for the four auxiliary terms are in [`collected_data/queries/related_queries/`](../../collected_data/queries/related_queries/).
