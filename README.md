# HIV data downloaded from https://www.hiv.lanl.gov/

This repository collects HIV sequence data, which store separately according to sequence length.

## How to use data

All data in this repository has zipped by `gz` in one file. Use `gz` in unix system to decompress files.

## File in `merge` folder

The `merge` folder has all HIV sequences which store separately according to sequence length. The statistics of HIV is shown below:

|Sequence length $L$|Number of sequences|File name|
|:-:|:-:|:-:|
|$2000 \leq L \lt 5000$ |8787|`2000.fasta` |
|$5000 \leq L \lt 10000$|5250|`5000.fasta` |
|$L \geq 10000$         |47  |`10000.fasta`|

## Ciation

See https://www.hiv.lanl.gov/content/sequence/HIV/refer.html for more information.