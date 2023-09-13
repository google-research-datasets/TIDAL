# TIDAL: Textual Identity Detection and Augmentation Lexicon

This repository contains the TIDAL dataset for the paper "[TIDE: Textual
Identity Detection for Evaluating and Augmenting Classification and Language
Models](https://arxiv.org/abs/2309.04027)

Note: This dataset contains pejorative terms that may be offensive.

## Overview
TIDAL dataset has been created to aid annotation of textual datasets with identity tokens to help with fairness evaluation and remediation of datasets and models. It supports only the English language, but has broad coverage of identity terms and grammatical variants across three IdentityGroups: Race, Nationality or Ethnicity (RNE), Sexual Orientation, Gender Identity, Gender Expression and Sex Characteristics (SOGIESC) and Religion. Each head and related form is associated with grammatical properties (e.g. part-of-speech, grammatical gender) and context (or “sense”) entries (e.g. identity groups/subgroups, connotation).

## Dataset Description
The repo contains the data card for the TIDAL dataset, following the format
proposed by [Pushkarna et al.](https://arxiv.org/abs/2204.01075). The data card
includes details of the TIDAL dataset such as intended usage, field names and
meanings and crowdsourced annotators leveraged. The `dataset` folder contains
the TIDAL dataset in XML format based on an adapted
[UBY-LMF](http://www.lrec-conf.org/proceedings/lrec2012/pdf/475_Paper.pdf) schema which is
based on the [Lexical Markup Framework](https://www.iso.org/standard/82014.html) (LMF) standard for representating NLP
lexicons.

## Citation

```
@misc{klu2023tide,
      title={TIDE: Textual Identity Detection for Evaluating and Augmenting Classification and Language Models}, 
      author={Emmanuel Klu and Sameer Sethi},
      year={2023},
      eprint={2309.04027},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
```
