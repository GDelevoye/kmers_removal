# kmers_removal

Small example of how a list of kmers can be removed from a genome assembly

# Requirements

- python
- pip
- Jupyter notebook

# Advice on requirements

If you don't have jupyter notebook (a software that allows enhanced and interactive data analysis in python) , the best is probably that you download it directly from https://www.anaconda.com/products/individual

# How to launch the notebook

```console
user@computer:~$ pip install tqdm pandas 
user@comàputer:~$ https://github.com/GDelevoye/kmers_removal.git
user@computer:~$ cd kmers_removal
user@computer:~$ jupyter notebook 25mers.ipynb
```

# What does the notebook show ?

The notebook shows how kmers can be retrieved from a human or mouse assembly, how we can make a summary report of the kmers localization in both genomes, and how we can remove a given list of kmers to create a new .fasta reference
