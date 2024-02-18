# Montreal Forced Aligner for Cantonese
Trained on the train set of Common Voice 16.1.
Works in progress. Needs to be improved by training on more audios with a larger vocab.

## Run alignment:

```
mfa align test_wavs lexicon.dict yue_acoustic_model.zip test_alignment/
```