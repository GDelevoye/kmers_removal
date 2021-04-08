# kmers_removal

Small example of how a list of kmers (specified in a .txt file) can be removed from a genome assembly

# Requirements

- python 3
- pip

# Installation 

```console
git clone https://github.com/GDelevoye/kmers_removal.git
pip install -e ./kmers_removal
```

# Usage 

```console 
guillaume@A320MA:~$ kmers_removal --help
usage: kmers_removal [-h] --fastaFile FASTAFILE --kmerFile KMERFILE --output
                     OUTPUT
                     [--verbosity {NONE,DEBUG,INFO,WARNING,ERROR,CRITICAL}]
                     [--report REPORT]

Allows to remove a given list of kmers in a genome assembly

optional arguments:
  -h, --help            show this help message and exit
  --fastaFile FASTAFILE, -f FASTAFILE
                        Input .fasta file where kmers must be removed
  --kmerFile KMERFILE, -k KMERFILE
                        Path to a file with 1 kmer to remove per line (can be
                        list of files). Must contain onlyupper A, T, C or G
                        and \n
  --output OUTPUT, -o OUTPUT
                        output .fa file
  --verbosity {NONE,DEBUG,INFO,WARNING,ERROR,CRITICAL}, -v {NONE,DEBUG,INFO,WARNING,ERROR,CRITICAL}
                        Choose your verbosity on stdout. Default: INFO. If
                        verbosity < INFO, no progress_bar is displayed.
  --report REPORT, -r REPORT
                        [FACULTATIVE - DEFAULT is None] Path to a report of
                        the kmers encountered
```
