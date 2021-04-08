# kmers_removal

Small example of how a list of kmers can be removed from a genome assembly

# Requirements

- python 3
- pip
- Jupyter notebook


- > 8GB RAM

# Advice on requirements

If you don't have jupyter notebook (a software that allows enhanced and interactive data analysis in python) , the best is probably that you download it directly from https://www.anaconda.com/products/individual

# How to launch the notebook

```console
user@computer:~$ pip install tqdm pandas 
user@comàputer:~$ git clone https://github.com/GDelevoye/kmers_removal.git
user@computer:~$ cd kmers_removal
user@computer:~$ jupyter notebook 25mers.ipynb
```

# What does the notebook show ?

The notebook downloads a human and a mouse assembly. Then, it shows how kmers can be retrieved from a human or mouse assembly, how to make a small summary report of the kmers localization in both genomes (see example in .csv files given in the repo), and how we can remove a given list of kmers to create a new .fasta reference
