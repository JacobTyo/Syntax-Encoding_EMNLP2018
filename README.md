# Syntax-CNN_EMNLP2018

you can get the datasets used in the paper at [here](https://drive.google.com/drive/folders/1hlIWVSt0dfy8fz8d4wRzZItl-LCo5BH1?usp=sharing).

### execute

```
python main.py --dataset <dataset_name> --num_authors <num_of_authors>
```

* the parameter *dataset* will choose from [blogs, CCAT, imdb]

* the parameter *num_authors* will depend on the dataset you choose. when you choose *blogs* or *CCAT*, the parameter *num_authors* wil be 10 or 50, but the max authors num of *imdb* is 62.

