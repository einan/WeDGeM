# WeDGeM

WeDGeM is a multilingual evaluation set generator for specific domains using Wikipedia and DBpedia. Wikipedia category pages and DBpedia taxonomy are used for adjusting domain-specific annotated text generation. Wikipedia disambiguation pages are applied to determine the ambiguity level of the generated texts. Based on these texts, a use case for well-known Entity Linking systems supporting English and Turkish texts are evaluated in the movie domain.

The generated datasets are added to well-known evaluation framework called GERBIL to observe the performance of popular Entity Linking systems integrated to [GERBIL](http://aksw.org/Projects/GERBIL.html). In this study, [Babelfy](http://babelfy.org/) and [DBpedia Spotlight](http://demo.dbpedia-spotlight.org/) are selected as integrated systems from GERBIL supporting both English and Turkish texts.

## If you want to use WeDGeM in your studies, please cite the following paper:

```
@inproceedings{DBLP:conf/wise/InanD17,
  author    = {Emrah Inan and
               Oguz Dikenelli},
  title     = {WeDGeM: {A} Domain-Specific Evaluation Dataset Generator for Multilingual
               Entity Linking Systems},
  booktitle = {Web Information Systems Engineering - {WISE} 2017 - 18th International
               Conference, Puschino, Russia, October 7-11, 2017, Proceedings, Part
               {II}},
  pages     = {221--228},
  year      = {2017},
  crossref  = {DBLP:conf/wise/2017-2},
  url       = {https://doi.org/10.1007/978-3-319-68786-5_18},
  doi       = {10.1007/978-3-319-68786-5_18},
  timestamp = {Thu, 05 Oct 2017 16:48:39 +0200},
  biburl    = {http://dblp.uni-trier.de/rec/bib/conf/wise/InanD17},
  bibsource = {dblp computer science bibliography, http://dblp.org}
}
```

```
@proceedings{DBLP:conf/wise/2017-2,
  editor    = {Athman Bouguettaya and
               Yunjun Gao and
               Andrey Klimenko and
               Lu Chen and
               Xiangliang Zhang and
               Fedor Dzerzhinskiy and
               Weijia Jia and
               Stanislav V. Klimenko and
               Qing Li},
  title     = {Web Information Systems Engineering - {WISE} 2017 - 18th International
               Conference, Puschino, Russia, October 7-11, 2017, Proceedings, Part
               {II}},
  series    = {Lecture Notes in Computer Science},
  volume    = {10570},
  publisher = {Springer},
  year      = {2017},
  url       = {https://doi.org/10.1007/978-3-319-68786-5},
  doi       = {10.1007/978-3-319-68786-5},
  isbn      = {978-3-319-68785-8},
  timestamp = {Thu, 05 Oct 2017 16:48:39 +0200},
  biburl    = {http://dblp.uni-trier.de/rec/bib/conf/wise/2017-2},
  bibsource = {dblp computer science bibliography, http://dblp.org}
}
```
