# A Systematic Review of Reproducibility Research in Natural Language Processing

Anya Belz, Shubham Agarwal, Anastasia Shimorina, Ehud Reiter, "A Systematic Review of Reproducibility Research in Natural Language Processing", EACL 2021. [[arXiv](https://arxiv.org/abs/2103.07929)] [ACL Anthology]

## List of Papers Reviewed

See [this spreadsheet](https://docs.google.com/spreadsheets/d/1sq9rEQBxlqBSsb4_vwSpS75JiY4EcI_o8RAWb2p_zrE/edit?usp=sharing).

See [this README](./resources#list-of-annotated-papers) also for the list of papers with annotation (equivalent to the tab "Annotated papers" in the spreadsheet above).

## Requirements

We used Python3 for our experiments. We oftenly use `f-strings` and `typing` in our code. Some basic familiarity is required. 

```
conda create -n repro python=3.7 -y
eval "$(conda shell.bash hook)"
conda activate repro
pip install matplotlib numpy==1.19.0 pandas nltk wordcloud seaborn
conda install jupyter
```

## Running code

```
conda activate repro
jupyter notebook
```

All code resides in the `analysis.ipynb` notebook in the [notebook](./notebooks/analysis.ipynb) folder to reproduce Figure 1.  

## Citing

```
@inproceedings{belz-etal-2021-systematic,
    title = {A Systematic Review of Reproducibility Research in Natural Language Processing},
    author = {Anya Belz and Shubham Agarwal and Anastasia Shimorina and Ehud Reiter},
    booktitle = "Proceedings of the 16th Conference of the European Chapter of the Association for Computational Linguistics",
    month = apr,
    year = "2021",
    address = "Online",
    publisher = "Association for Computational Linguistics"
}
```
