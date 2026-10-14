# CollScore — A Vocabulary for Collocation Scoring Measures

**CollScore** is a standalone OWL vocabulary for representing and documenting statistical measures used to assess lexical co-occurrence and extract collocation candidates from corpora. It provides a systematic description of **eleven measures**, including co-occurrence frequency, relative frequency, PMI and its variants, Dice, logDice, t-score, log-likelihood, chi-squared, and confidence.

Each measure is documented with its definition, calculation formula, statistical assumptions, relevant edge cases, and scientific references. CollScore distinguishes the measure itself (represented as a named individual) from the datatype property used to record its numerical value. Its measure-specific score properties are defined as subproperties of **`frac:cScore`** in OntoLex-FrAC, supporting the representation of scores associated with corpus-based collocation observations.

CollScore is an **independent, unofficial vocabulary**. It is neither an extension of LexInfo nor an official W3C OntoLex specification. It was developed in the context of research on connecting corpus evidence, statistical analysis, and lexical representation.

## Ontology

- **Download:** [collocation score.owl](collocation%20score.owl) (RDF/XML)
- **Ontology IRI:** `https://ilc.cnr.it/klab/ontology/cooccurrence-measures`
- **Namespace:** `https://ilc.cnr.it/klab/ontology/cooccurrence-measures#`
- **Preferred prefix:** `collscore:`
- **Version:** `1.1.0`

The OWL file is provided unchanged from the original ontology artifact.
