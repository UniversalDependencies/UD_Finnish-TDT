# Summary

UD_Finnish-TDT is based on the Turku Dependency Treebank (TDT), a broad-coverage dependency treebank of general Finnish covering numerous genres. The conversion to UD was followed by extensive manual checks and corrections, and the treebank closely adheres to the UD guidelines.

# Introduction

The treebank contains texts from Wikipedia articles, Wikinews articles, University online news, Blog entries, Student magazine articles, Grammar examples, Europarl speeches, JRC-Acquis legislation, Financial news, and Fiction sourced from 674 individual documents. The original annotation of the treebank was in Stanford Dependencies, including secondary dependencies, and fully manually checked morphological annotation. The treebank is also accompanied by a PropBank annotation (http://turkunlp.github.io/Finnish_PropBank/) and a dependency parser pipeline substantially outperforming the baseline UDPipe model (http://turkunlp.github.io/Finnish-dep-parser/).


# Acknowledgments

The team behind the Turku Dependency Treebank: Katri Haverinen, Jenna Kanerva (Nyblom), Timo Viljanen, Veronika Laippala, Samuel Kohonen, Anna Missilä, Stina Ojala, Filip Ginter.

We are grateful for the funding received from:

* University of Turku
* Turku Centre for Computer Science
* Finnish Academy
* Turku University Foundation

We thank all the authors who kindly allowed us to include their texts into the treebank, either by explicit permission, or by releasing their text under an open license in the first place.

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
