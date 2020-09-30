# eacl-reproducibility


We used Python3 for our experiments. We oftenly use `f-strings` and `typing` in our code. Some basic familiarity is required. 

```
conda create -n repro python=3.7 -y
eval "$(conda shell.bash hook)"
conda activate repro
pip install matplotlib numpy==1.19.0 pandas nltk wordcloud
conda install jupyter
```
