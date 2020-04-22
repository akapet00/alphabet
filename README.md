# Alphabet

Alphabet is a short and simple CLI application for easy retrieval of the Greek alphabet while writing mathematical expressions in scientific papers.

## Installation

Clone the repo on your local machine

```bash
$ git clone https://github.com/antelk/alphabet.git
```

Access `alphabet` directory

```bash
$ cd alphabet
```

Make the script executable and add it to `$PATH`

```bash
$ bash run.sh
```

## Usage

```bash
$ alphabet -h
usage: alphabet [-h] [-p | -e  | -o ]

optional arguments:
  -h, --help       show this help message and exit
  -p, --printout   return full Greek alphabet
  -e , --english   return the Greek alphabet letter and name for given English
                   alphabet letter name
  -o , --ordinal   return the Greek alphabet letter and name for given ordinal
                   number of the letter
```

Short example

```bash
$ alphabet -e zeta
Ordinal number in alphabet: 	 6
Lower case alphabet symbol: 	 ζ 
Upper case alphabet symbol: 	 Ζ 
Greek alphabet letter name: 	 ζήτα

```

## Requirements

Python 3 on Linux operating system.

## License
[MIT](https://github.com/antelk/alphabet/blob/master/LICENSE)