# Acknowledgments per SNIC center in Nature Journals between 2003-2022

### Date
2023-05-14

### Author: Linus Nilsson
Linus Nilsson <linus.nilsson@uppmax.uu.se>

### Conflict of interest
The author is employed at UPPMAX (previously a SNIC center).

### Purpose
The Swedish National Infrastructure of Computing (SNIC) provided HPC resources
through six different SNIC centers for academics and researchers in Sweden from
2003 to 2022. As part of the terms of use, researchers were encouraged to
acknowledge SNIC in their research, including all published articles. The
purpose of this study is to quantify the number of acknowledgments per SNIC
center in all Nature journals since SNIC's establishment in 2003.

### Method
Perform an advanced search [1] on nature.com for articles that contains the
term "SNIC" and publication date between 2003 and 2022. Group by year and
manually read the acknowledgments section of each article. Each acknowledged
SNIC center receives a count of +1. If an article acknowledges multiple SNIC
centers, each acknowledged center receives a count of +1. If the
acknowledgments only mention SNIC without specifying a center, +1 is added to a
placeholder "SNIC" center.

[1] https://www.nature.com/search/advanced

### Results

Year   2006  2007 2008 2009   2010   2011   2012  2013  2014 2015   2016   2017   2018   2019  2020  2021   2022

C3SE   0     0    0     0      0     0       1     0    1     1    4       4      1      4     3     7      5    C3SE
LUNARC 0     0    0     0      0     0       0     0    0     1    1       4      2      4     3     2      2    LUNARC
SNIC   1     1    0     1      0     0       2     6    3     6    7       13     9      7     8     7      10   SNIC
PDC    0     0    0     0      0     0       0     2    0     4    3       5      9      4     2     7      11   PDC
HPC2N  0     0    0     0      0     0       0     3    2     2    4       7      4      1     8     10     15   HPC2N
NSC    0     0    0     0      0     0       0     4    2     11   6       15     8      8     12    13     21   NSC
UPPMAX 0     0    0     0      0     0       2     8    6     7    22      18     20     31    31    44     69   UPPMAX
SSC    0     0    0     0      0     0       0     0    0     0    0       0      0      2     0     0      0    SSC

### Discussion
* Most, but not all, articles had an open/free acknowledgment section. For
  locked or paywalled articles the online Uppsala University library at
  https://ub.uu.se was used to read the article.

* The number of acknowledgments per year is generally higher than the number of
  articles, as multiple SNIC centers are sometimes acknowledged in a single
  article.

* Acknowledgments that do not explicitly mention a center by name but can be
  identified through descriptions, such as "We acknowledge SNIC and used the
  Uppsala server" or "We used the Linköping computers," are counted as "UPPMAX"
  and "NSC," respectively. Cases like these make it non-trivial to develop a
  machine parser for this type of study.

* The results should not be interpreted as "Center X received N acknowledgments
  in all Nature journals in year YYYY." This interpretation is incorrect
  because only articles specifically mentioning "SNIC" in the acknowledgments
  were counted. For example, if an article acknowledges "We acknowledge LUNARC
  for generously providing us with computational resources," it would not be
  included in the search since it does not contain the word "SNIC." Similarly,
  if the acknowledgment is "We acknowledge the Swedish National Infrastructure
  of Computing and LUNARC for providing us with computational resources," it
  would also not be included as it does not contain the word "SNIC."

* Articles that acknowledge SNIC without mentioning any specific center
  increment the count for the "SNIC" center. The results could be improved by
  considering that some articles only acknowledge "SNIC" but provide a project
  name, such as "snic2022-1-23." The resources used for each project are
  visible on https://supr.snic.se, but this study did not perform a lookup.

* Finally, the results was obtained through a manual process and should be
  independently verified for accuracy.
