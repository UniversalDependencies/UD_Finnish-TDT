The gold annotation for the TDT official test set is not publicly
distributed. Instead, you can submit your parser output on the file
fi_ud_test-official.conllu to the evaluation service at the
address below. The service will compare your parser output against the
gold standard and will give you the scores for a number of standard
metrics. These are to be considered the "official" test set results.

The files fi_ud_devel.conllu and fi_ud_test.conllu are obtained by
splitting the original development set of TDT into two equally-sized
parts.

TDT evaluation service address: http://bionlp-www.utu.fi/tdteval/

* CHANGELOG 1.0 -> 1.1

The data has only seen small changes between the original 1.0 release
and the current 1.1 release. These changes fix a small number of
annotation problems noticed after the 1.0 release.

* CHANGELOG 1.1 -> 1.2

- Names now follow the official UD style, i.e. are left-headed
- Where appropriate, `foreign` relation is used
- `SpaceAfter=No` feature added
- Various fixes of individual annotation errors


--- Machine readable metadata ---
Documentation status: complete
Data source: semi-automatic
Data available since: UD v1.0
License: CC BY-SA 4.0
Genre: news wiki blog legal fiction grammar-examples
Contributors: Ginter, Filip; Kanerva, Jenna; Laippala, Veronika; Missilä, Anna; Pyysalo, Sampo
Contact: ginter@cs.utu.fi, jmnybl@utu.fi
