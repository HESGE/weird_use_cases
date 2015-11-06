# weird_use_cases

WeIRD: Web Intelligence for Rare Disease

http://bitem.hesge.ch/project/weird

The WeIRD project aims to provide the informational instruments needed to navigate, search and ultimately question the web evidence space of Rare Diseases by providing access to high-quality contents helpful to support diagnosing RD. The system will use advanced information retrieval and text mining methods to holistically crawl, index and finally analyze all the explicit and implicit knowledge available on Rare Diseases.

This research project is supported by RCSO/ISNET a scientific program of the University of Applied Sciences Western Switzerland.

Here are listed the use cases (diagnostic queries) needed to evaluate the system. They are given in computable format and are (hopefully) self explanatory. These data came from [Dragusin 2013] and [Tang and Ng 2006].

* `findzebra_use_cases.csv` is the extracted from [Dragusin 2013]
* `bmj_use_case.csv` is the extracted from [Tang and Ng 2006]
* `findzebra_with_full_bmj_query.csv` is the combination of the two datasets where the original BMJ queries are used instead of the simplified 'google' version of the queries.


If you see some errors, please send me a pull request to indicate the error.

* Dragusin, R., Petcu, P., Lioma, C., Larsen, B., Jørgensen, H. L., Cox, I. J., ... & Winther, O. (2013). FindZebra: a search engine for rare diseases. International journal of medical informatics, 82(6), 528-538. (see also http://findzebra.compute.dtu.dk, the FindZebra search engine for rare diseases)
* Tang, H., & Ng, J. H. K. (2006). Googling for a diagnosis—use of Google as a diagnostic aid: internet based study. Bmj, 333(7579), 1143-1145.
