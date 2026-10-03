This folder contains the yearly status of 56 commercial nuclear reactors in Japan and each prefecture's distance from Fukushima.

| File | Contents |
|---|---|
| `reactor_status.csv` | 56 reactors, 2004–2024; each row gives the reactor name, the prefecture where it is located, and for each year `Y` if the reactor was operable (not yet retired) and `N` if not |
| `jaif_japan_nuclear_reactors_2025-09-08.pdf` | the source of `reactor_status.csv`: the Japan Atomic Industrial Forum's (JAIF) table of Japan's reactors in operation, under construction, planned and decommissioned, with restart dates, as of 8 September 2025 (in Japanese) |
| `atomica_japan_nuclear_power_plants_2010.pdf` | ATOMICA's overview of Japan's nuclear power plants as of 31 March 2010 (in Japanese); its Table 2-3 lists the reactors under construction and planned at that time |
| `distance_from_fukushima.csv` | distance (km) from Fukushima to each prefecture, measured between the prefectural government offices (Fukushima = 0) |
| `gsi_distances_between_prefectural_offices_2016.pdf` | the source of `distance_from_fukushima.csv`: the Geospatial Information Authority of Japan's (GSI) table of the shortest distances between prefectural government offices ([archived copy](https://web.archive.org/web/20160509062429/http://www.gsi.go.jp/common/000137532.pdf)) |

The 56 reactors are the 54 in operation on 11 March 2011 and Hamaoka-1 and -2, which were retired in January 2009.
The JAIF table does not list three reactors in Fukushima that were planned before the accident and canceled after it (Fukushima Daiichi-7 and -8, and Namie-Odaka); they are listed as planned in Table 2-3 of the ATOMICA overview.
