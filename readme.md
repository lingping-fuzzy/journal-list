# Supplementary Material — Venue List and Search Scope

**Manuscript:** *under submission*

**Why this file exists:** the report list the literature search of section 1.5 but cannot print
the complete list of journal and conference names inline — the full names alone occupy more than a
page. The complete venue list is therefore hosted here as supplementary material.

--

## 1. Search period and scope

- **Period:** 2020–2026 (the 2026 window is partial; closing date: `<Aug. 1>`).
- **Sources:** peer-reviewed journal articles and top-tier conference papers.
- **Record types:** titles, abstracts, and author keywords, screened against controlled
  vocabularies (section 1.5 of the manuscript).

## 2. Venues searched and venues contributing papers

**56 venues were searched: 50 journals and 6 conferences** (period 2020–2026).
Of these, **46 venues contributed papers to the fusion-related screening pool**
(828 papers): 40 journals (404 papers) and 6 conferences (424 papers); a further
10 searched journals returned no paper that passed fusion-relevance screening
(see the record-level tables released with the code).

### 2.1 Journals contributing to the pool (40)

| # | Abbreviation | Full name | Papers in pool |
|---|--------------|-----------|----------------|
| 1 | TGRS | IEEE Transactions on Geoscience and Remote Sensing | 38 |
| 2 | TPAMI | IEEE Transactions on Pattern Analysis and Machine Intelligence | 34 |
| 3 | TNNLS | IEEE Transactions on Neural Networks and Learning Systems | 33 |
| 4 | TIP | IEEE Transactions on Image Processing | 30 |
| 5 | InfoFusion | Information Fusion | 27 |
| 6 | JSTARS | IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing | 22 |
| 7 | JBHI | IEEE Journal of Biomedical and Health Informatics | 21 |
| 8 | TSP | IEEE Transactions on Signal Processing | 19 |
| 9 | TCYB | IEEE Transactions on Cybernetics | 18 |
| 10 | TMI | IEEE Transactions on Medical Imaging | 17 |
| 11 | GRSL | IEEE Geoscience and Remote Sensing Letters | 16 |
| 12 | TITS | IEEE Transactions on Intelligent Transportation Systems | 14 |
| 13 | TKDE | IEEE Transactions on Knowledge and Data Engineering | 14 |
| 14 | TRO | IEEE Transactions on Robotics | 10 |
| 15 | TOG | ACM Transactions on Graphics | 8 |
| 16 | TOMM | ACM Transactions on Multimedia Computing, Communications, and Applications | 8 |
| 17 | CEA | Computers and Electronics in Agriculture | 7 |
| 18 | MedIA | Medical Image Analysis | 6 |
| 19 | TASLP | IEEE/ACM Transactions on Audio, Speech, and Language Processing | 6 |
| 20 | TAC | IEEE Transactions on Automatic Control | 6 |
| 21 | TVCG | IEEE Transactions on Visualization and Computer Graphics | 5 |
| 22 | IJCV | International Journal of Computer Vision | 5 |
| 23 | TAI | IEEE Transactions on Artificial Intelligence | 5 |
| 24 | TFS | IEEE Transactions on Fuzzy Systems | 5 |
| 25 | TBME | IEEE Transactions on Biomedical Engineering | 5 |
| 26 | SPM | IEEE Signal Processing Magazine | 4 |
| 27 | TPWRS | IEEE Transactions on Power Systems | 3 |
| 28 | TBIOM | IEEE Transactions on Biometrics, Behavior, and Identity Science | 3 |
| 29 | AIReview | Artificial Intelligence Review | 2 |
| 30 | TIST | ACM Transactions on Intelligent Systems and Technology | 2 |
| 31 | CL | Computational Linguistics | 2 |
| 32 | AI | Artificial Intelligence (Elsevier) | 1 |
| 33 | IJRR | The International Journal of Robotics Research | 1 |
| 34 | Automatica | Automatica (Elsevier) | 1 |
| 35 | ProcIEEE | Proceedings of the IEEE | 1 |
| 36 | NatMI | Nature Machine Intelligence | 1 |
| 37 | JMLR | Journal of Machine Learning Research | 1 |
| 38 | JFR | Journal of Field Robotics | 1 |
| 39 | MLJ | Machine Learning (Springer) | 1 |
| 40 | TKDD | ACM Transactions on Knowledge Discovery from Data | 1 |
| | **Total** | | **404** |

### 2.2 Conferences (6)

| # | Abbreviation | Full name | Papers in pool |
|---|--------------|-----------|----------------|
| 1 | NeurIPS | Conference on Neural Information Processing Systems | 159 |
| 2 | ICLR | International Conference on Learning Representations | 91 |
| 3 | ICML | International Conference on Machine Learning | 89 |
| 4 | CVPR | IEEE/CVF Conference on Computer Vision and Pattern Recognition | 51 |
| 5 | IJCAI | International Joint Conference on Artificial Intelligence | 30 |
| 6 | ICCV | IEEE/CVF International Conference on Computer Vision | 4 |
| | **Total** | | **424** |

## 3. Venues excluded before the search

| Venue | Type | Reason |
|-------|------|--------|
| Scientific Reports | Journal | Broad multidisciplinary scope; excluded for scale |
| Nature Communications | Journal | Broad multidisciplinary scope; excluded for scale |
| ECCV (European Conference on Computer Vision) | Conference | No usable metadata for the target period |
| AAAI (Conference on Artificial Intelligence) | Conference | No usable metadata for the target period |

These four venues never contributed to any count reported in the manuscript.

## 4. Screening stages (mirrors Fig. 1 of the manuscript)

| Stage | Result |
|-------|--------|
| 1. Venue and period selection | 56 venues searched (50 journals + 6 conferences); 46 contributed to the pool (40 journals + 6 conferences, see §2) |
| 2. Geometry-relevance screening | 7,006 records → 6,434 unique papers (3,383 journal / 3,051 conference) |
| 3. Fusion-relevance screening | 828 fusion-related papers (12.9%; 404 journal / 424 conference) |
| 4. Scope filter (dimensionality-reduction-only papers removed) | 765 core manifold×fusion papers (345 journal / 420 conference) |
| 5. Three-axis labelling | one primary label per axis (representation × mechanism × application) |
| 6. Representative selection | 731 subsection assignments → **432 unique representative works**, of which 200+ are cited in the bibliography |

## 5. Data and code availability

The screening pipeline is implemented in Python: controlled-vocabulary keyword extraction over
titles, abstracts, and keywords; de-duplication; scope filtering; three-axis labelling; citation
and venue scoring; and generation of the corpus figures. The complete code, together with the
record-level screening tables needed to reproduce every count in the manuscript, will be
publicly released in this repository upon acceptance of the manuscript. A copy can be provided to
the editors and reviewers on request before publication.


