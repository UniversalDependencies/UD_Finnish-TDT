# Summary

UD_Finnish is based on the Turku Dependency Treebank (TDT), a broad-coverage dependency treebank of general Finnish. The treebank covers numerous genres. The conversion to UD was followed by extensive manual checks and corrections, and the treebank closely adheres to the UD guidelines.

# Acknowledgments

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


--- Machine readable metadata ---
Documentation status: complete
Data source: semi-automatic
Data available since: UD v1.0
License: CC BY-SA 4.0
Genre: news wiki blog legal fiction grammar-examples
Contributors: Ginter, Filip; Kanerva, Jenna; Laippala, Veronika; Missilä, Anna; Ojala, Stina; Pyysalo, Sampo
Contact: figint@utu.fi, jmnybl@utu.fi
