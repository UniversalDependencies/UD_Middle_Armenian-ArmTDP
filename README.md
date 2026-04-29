# Summary

A Universal Dependencies treebank for Middle Armenian developed for UD originally by the ArmTDP team led by Marat M. Yavrumyan at the Yerevan State University.

# Introduction

The UD_Middle_Armenian-ArmTDP treebank is based on the Middle Armenian section of the Հայերենի ծառադարան dataset (ArmTDP v3.0), a broad-coverage corpus of Standard Armenian covering numerous genres.

The annotation scheme was developed in accordance with the UD guidelines. The original data was manually annotated by the ArmTDP team. The tokenization and POS-tagging process was carried out through alternating steps of glossary-based automatic scripting and manual revision. The treebank is the only manually verified corpus of Middle Armenian, supplied with comprehensive morphological and syntactic annotation in the form of a complete dependency tree for every sentence.


# Acknowledgments

This treebank was supported by the Higher Education and Science Committee of MESCS RA (Research project № 27TARGET-6B173).


## References

This treebank can also be referenced:

```tex
@misc{UD_Middle_Armenian-ArmTDP,
  title={{UD_Middle_Armenian-ArmTDP}: Universal Dependencies for Middle Armenian},
  url={https://github.com/UniversalDependencies/UD_Middle_Armenian-ArmTDP},
  author={
    Anna S. Danielyan and Marat M. Yavrumyan
    },
  year={2026},
}
```

## Format

UD_Middle_Armenian-ArmTDP data conforms to [CoNLL-U](http://universaldependencies.org/format.html) format with the following specifics:
* Sentence-level comments:
  * Document titles are present as `# doc_title = Դատաստանագիրք.
  * Document boundaries are present as `# newdoc id = legal/medical-xxxx`.
  * Sentence-level paragraph boundaries are present as `# newpar id = newdoc-xxxx`.
  * Sentence boundaries are present as `# sent_id = newdoc-newparxxxx`.
* XPOSTAG column is currently unused.
* No enhanced dependencies or empty nodes present in DEPS column.
* MISC column:
  * `SpaceAfter=No` markers are present.
* Document, paragraph, sentence, and token ids are 4-character base-32 numbers. They survive treebank updates.



# Changelog

* 2026-05-15 v2.18
  * Initial release in Universal Dependencies.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.18
License: CC BY-SA 4.0
Includes text: yes
Parallel: no
Genre: legal medical
Lemmas: manual native
UPOS: manual native
XPOS: not available
Features: manual native
Relations: manual native
Contributors: Danielyan, Anna; Yavrumyan, Marat M.
Contributing: here
Contact: adanielyan@ysu.am
===============================================================================
</pre>
