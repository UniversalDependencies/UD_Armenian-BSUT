# Summary

A Universal Dependencies treebank for Eastern Armenian developed for UD originally by the ArmTDP team led by Marat M. Yavrumyan at the V. Brusov State University in Yerevan.

# Introduction

The UD_Armenian-BSUT treebank is based on the Eastern Armenian section of the Հայերենի ծառադարան dataset (ArmTDP v2.0), a broad-coverage corpus of general Modern Standard Armenian covering numerous genres.

The annotation scheme was developed in accordance with the UD guidelines. The original data was manually annotated by the ArmTDP team. The tokenization and POS-tagging process was carried out through alternating steps of glossary-based automatic scripting and manual revision.

# Acknowledgments

This treebank is developed in the frame of the program "HayLingvoTech" excellency center implemented by the V. Brusov State University with the funding of the Competitive Innovation Fund of Armenia.

The treebank created by: Marat M. Yavrumyan, Rima R. Grigoryan, Anna S. Danielyan, Setrag H. M. Hovsepian.

## References

Yavrumyan M. M., Danielyan A. S., “Universal Dependencies and the Armenian Treebank.” Herald of the Social Sciences (2).231-244, 2020. (in Armenian)

## Format

UD_Armenian-BSUT data conforms to [CoNLL-U](http://universaldependencies.org/format.html) format with the following specifics:
* Sentence-level comments:
  * Document titles are present as `# doc_title = Ռետրո․ Վանո Սիրադեղյան.
  * Document boundaries are present as `# newdoc id = fiction/legal/news/nonfiction-xxxx`.
  * Sentence-level paragraph boundaries are present as `# newpar id = newdoc-xxxx`.
  * Sentence boundaries are present as `# sent_id = newdoc-newparxxxx`.
* XPOSTAG column is currently unused.
* No enhanced dependencies or empty nodes present in DEPS column.
* MISC column:
  * `SpaceAfter=No` markers are present.
  * Form (`Translit`) and lemma (`LTranslit`) transliterations are present (ISO 9985:1996).
* Document, paragraph, sentence, and token ids are 4-character base-32 numbers. They survive treebank updates.


# Changelog
* 2022-05-15 v2.10
  * Fixed various individual annotation errors and inconsistencies, added new texts: 3K→42K.
* 2021-11-15 v2.9
  * Initial release in Universal Dependencies.

<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.9
License: CC BY-SA 4.0
Includes text: yes
Genre: blog fiction government legal news nonfiction web wiki
Lemmas: manual native
UPOS: manual native
XPOS: not available
Features: manual native
Relations: manual native
Contributors: Yavrumyan, Marat M.
Contributing: here
Contact: myavrum@ysu.am
===============================================================================
Documentation contributors: Yavrumyan, Marat M.; Danielyan, Anna S.
https://github.com/armtreebank
</pre>
