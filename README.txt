# Summary

UD_Finnish-TDT is based on the Turku Dependency Treebank (TDT), a broad-coverage dependency treebank of general Finnish covering numerous genres. The conversion to UD was followed by extensive manual checks and corrections, and the treebank closely adheres to the UD guidelines.

# Introduction

The treebank contains texts from Wikipedia articles, Wikinews articles, University online news, Blog entries, Student magazine articles, Grammar examples, Europarl speeches, JRC-Acquis legislation, Financial news, and Fiction sourced from 674 individual documents. The original annotation of the treebank was in Stanford Dependencies, including secondary dependencies, and fully manually checked morphological annotation. The treebank is also accompanied by a PropBank annotation (http://turkunlp.github.io/Finnish_PropBank/) and a dependency parser pipeline substantially outperforming the baseline UDPipe model (https://turkunlp.org/Turku-neural-parser-pipeline/).


# Acknowledgments

The team behind the Turku Dependency Treebank: Katri Haverinen, Jenna Kanerva (Nyblom), Timo Viljanen, Veronika Laippala, Samuel Kohonen, Anna Missilä, Stina Ojala, Filip Ginter.

We are grateful for the funding received from:

* University of Turku
* Turku Centre for Computer Science
* Finnish Academy
* Turku University Foundation

We thank all the authors who kindly allowed us to include their texts into the treebank, either by explicit permission, or by releasing their text under an open license in the first place.

# Cite

```
{% raw %}

@Article{haverinen2013tdt,
  Title                    = {Building the essential resources for {Finnish}: the {Turku Dependency Treebank}},
  Author                   = {Haverinen, Katri and Nyblom, Jenna and Viljanen, Timo and Laippala, Veronika and Kohonen, Samuel and Missil{\"a}, Anna and Ojala, Stina and Salakoski, Tapio and Ginter, Filip},
  Journal                  = {Language Resources and Evaluation},
  Year                     = {2014},
  Note                     = {Open access},
  Pages                    = {493-531},
  Volume                   = {48},

  Doi                      = {10.1007/s10579-013-9244-1},
  ISSN                     = {1574-020X},
  Issue                    = {3},
  Keywords                 = {Treebank; Finnish; Parsing; Morphology},
  Language                 = {English},
  Owner                    = {ginter},
  Publisher                = {Springer Netherlands},
  Timestamp                = {2013.08.15},
  Url                      = {http://dx.doi.org/10.1007/s10579-013-9244-1}
}

@InProceedings{pyysalo2015udfinnish,
  Title                    = {Universal {D}ependencies for {F}innish},
  Author                   = {Pyysalo, Sampo and Kanerva, Jenna and Missil{\"a}, Anna and Laippala, Veronika and Ginter, Filip},
  Booktitle                = {Proceedings of NoDaLiDa 2015},
  Year                     = {2015},
  Pages                    = {163--172},
  Publisher                = {NEALT},

  Url                      = {https://aclweb.org/anthology/W/W15/W15-1821.pdf}
}

{% endraw %}
```

# Changelogs

* CHANGELOG 1.0 -> 1.1

The data has only seen small changes between the original 1.0 release
and the current 1.1 release. These changes fix a small number of
annotation problems noticed after the 1.0 release.

* CHANGELOG 1.1 -> 1.2

- Names now follow the official UD style, i.e. are left-headed
- Where appropriate, `foreign` relation is used
- `SpaceAfter=No` feature added
- Various fixes of individual annotation errors

* CHANGELOG 1.2 -> 1.3

- No changes

* CHANGELOG 1.3 -> 1.4

- No changes

* CHANGELOG 1.4 -> 2.0

- Conversion to the 2.0 scheme
  - empty nodes re-inserted from TDT sources
  - olla verbs follow copula analysis
  - numbers with space "6 000" now a single token
  - goeswith used for things like "EU: n"
- A number of small fixes
- The former secret test set now part of the release, what used to be dev+test is now dev. New sizes:
  - train size =  12217 sentences
  - dev size   =  716+648 sentences
  - test size  =  1555 sentences

* CHANGELOG 2.0 -> 2.1

- Better features for foreign proper names
- Derivation features are now consistently annotated
- Various fixes of individual annotation errors

* CHANGELOG 2.1 -> 2.2

- Repository renamed from UD_Finnish to UD_Finnish-TDT.

* CHANGELOG 2.2 -> 2.3

- No changes

* CHANGELOG 2.3 -> 2.4

- Parataxis punctuation now follow the official UD style
- Basic dependencies are repeated in the enhanced graph
- Multiword token annotation for tokens like "ettei"
- More consistent lemma annotation
- Various validation errors fixed
- Various fixes of individual annotation errors


--- Machine readable metadata ---
Data available since: UD v1.0
License: CC BY-SA 4.0
Includes text: yes
Genre: news wiki blog legal fiction grammar-examples
Lemmas: manual native
UPOS: converted from manual
XPOS: converted from manual
Features: converted from manual
Relations: manual native
Contributors: Ginter, Filip; Kanerva, Jenna; Laippala, Veronika; Miekka, Niko; Missilä, Anna; Ojala, Stina; Pyysalo, Sampo
Contact: figint@utu.fi, jmnybl@utu.fi
Contributing: elsewhere
