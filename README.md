This repository contains four core files detailing the *Narrascope Data Transformation Language* (NARDAT):

* `grammar.ohmjs` contains the parsing expression grammar (PEG) for NARDAT. The grammar file is written in the Ohm language (see https://ohmjs.org/docs/syntax-reference).
* `prelude.txt` contains the low-level prelude for the NARDAT interpreter, which are mostly type and operator predence definitions for fundamental library functions such as `map` and `sort`. Most functions are stubs that refer to native implementations. The file is written in NARDAT.
* `schema.txt` contains the domain-specific data schema used to import video corpus data for querying. The file is written in NARDAT.
* `query.txt` contains implementations of utility functions that are used in the queries. The file is written in NARDAT.
