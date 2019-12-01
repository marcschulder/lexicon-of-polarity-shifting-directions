# Enhancing a Lexicon of Polarity Shifters through the Automatic Addition of Shifting Directions

This repository contains the data presented in:

[Schulder, Marc](http://marc.schulder.info) and [Wiegand, Michael](http://www.coli.uni-saarland.de/~miwieg/) and [Ruppenhofer, Josef](http://ruppenhofer.de/) (under review). **"Enhancing a Lexicon of Polarity Shifters through the Supervised Classification of Shifting Directions"**.

## Content
We provide information on the shifting direction of polarity shifters.
Shifting directions specify whether a polarity shifter can affect __only positive__ polar expressions, __only negative__ ones or shift in __both__ directions.

We cover all shifters found in the shifter lexicon of [Schulder et al. (under review B)](https://github.com/uds-lsv/bootstrapped-lexicon-of-english-polarity-shifters), which contains verbs, noun and adjectives.

### Resources
- **Paper:** Under review
- **Data:** See content of this repository

## Data
A list of 2521 polarity shifters, labeled for their shifting direction. Contains 863 shifters that affect only positive polar expressions, 288 shifters that affect only negative polar expressions and 1370 shifters that can shift in both directions.

- File: `shifting_directions.txt`
- The lexicon is a comma-separated value (CSV) table
- Each line follows the format `POS,LEMMA,DIRECTION_LABEL,SOURCE`.
  - `POS`: The part of speech of the word (`verb`, `noun`, `adj`)
  - `LEMMA`: The lemma representation of the word in question. Multiword expressions are separated by an underscore (`WORD_WORD`).
  - `DIRECTION_LABEL`: Whether the shifter affects only positive polarities (`AFFECTS_POSITIVE`), only negative polarities (`AFFECTS_NEGATIVE`) or can shift in both directions (`AFFECTS_BOTH`).
  - `SOURCE`: Whether the word was part of the gold standard (`GOLD_STANDARD`) or was labeled automatically (`AUTOMATIC`).

## Attribution
This data set is published under [Creative Commons Attribution 4.0](https://github.com/uds-lsv/lexicon-of-english-verbal-polarity-shifters/blob/master/LICENSE).

If you use it in your research or work, please cite the publication (see above).

### BibTex
```
@unpublished{schulder2020shiftingdirections,
  author = {Schulder, Marc and Wiegand, Michael and Ruppenhofer, Josef},
  title = {Enhancing a Lexicon of Polarity Shifters through the Supervised Classification of Shifting Directions},
}
```

## Acknowledgements
This work was partially supported by the German Research Foundation (DFG) under grants RU 1873/2-1 and WI4204/2-1.
