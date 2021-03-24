# A Systematic Review of Reproducibility Research in Natural Language Processing

Anya Belz, Shubham Agarwal, Anastasia Shimorina, Ehud Reiter, "A Systematic Review of Reproducibility Research in Natural Language Processing", EACL 2020. [[arXiv](https://arxiv.org/abs/2103.07929)] [ACL Anthology]

## Annotated List of Papers

See [this README](./resources#list-of-annotated-papers) for the list of papers with annotation.

## Requirements

We used Python3 for our experiments. We oftenly use `f-strings` and `typing` in our code. Some basic familiarity is required. 

```
conda create -n repro python=3.7 -y
eval "$(conda shell.bash hook)"
conda activate repro
pip install matplotlib numpy==1.19.0 pandas nltk wordcloud
conda install jupyter
```

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
