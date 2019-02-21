# 2. Use GIZA++V2 for generating phrase table

Date: 2019-02-18

## Status

Accepted

## Context

PhraseTables are required for both SMT and NMT approaches.

## Decision
We will be using [GIZA++V2](https://github.com/moses-smt/giza-pp/tree/master/GIZA%2B%2B-v2) to generate phrasetables.

## Consequences

Should create a pipeline including GIZA++V2 to generate phrasetables for future text corpora addition. 
