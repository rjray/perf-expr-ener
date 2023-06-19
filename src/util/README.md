# Utility Code

The Python programs in this directory are utilities that were used for various
steps in the research process.

## random_data.py

This utility generates the random data designed to resemble DNA sequences and
findable patterns. Almost all parameters are tunable; run the command with the
`--help` option for a list of parameters that can be passed.

The goal for the data generation was to generate pseudo-random data that could
be replicated for research purposes. It is written to generate a given number
of "sequences" and an accompanying number of patterns taken directly from the
sequences. Each pattern must be findable in at least 0.1% of all sequences in
order to be added to the list.

Running this tool will generate files of:

* Sequences
* Patterns
* Answers

The answers-file provides a count for each pattern/sequence combination that
indicates how many times it should be found. This was used in the per-language
frameworks to verify that the algorithms were actually returning correct
answers.
