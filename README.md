There are four Python programs here (`-h` for usage):

 - `./mert_rerank` chooses the best candidate translations using implemented Minimal Error Rate Training (MERT) model
 - `./rerank` chooses the best candidate translations from a k-best list using a linear model.
 - `./oracle` computes a lower bound of BLEU on the development data.
 - `./compute-bleu` computes the BLEU score of a set of translations.

The `data/` directory contains training, devlopment, and test data. (NOT COMMITTED)

 - `train.src`: Russian source sentences.
 - `train.ref`: English reference sentences.
 - `train.100best`: Candidate translations of `train.src` from a machine translation system.
 - `dev+test.src`: Russian source sentences.
 - `dev.ref`: English references sentences for the first half of `dev+test.src`.
 - `dev+test.100best`: Candidate translations of `dev+test.src`.


