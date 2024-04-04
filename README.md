
# Can Abnormality be Detected by Graph Neural Networks?

## Model Usage

### Dependencies 

Before running the code, install the dependency packages using:

```markdown
pip install -r requirements.txt
```

### Dataset 

The preprocessed `Elliptic` datasets is in the `/dataset`. Due to large file size, the preprocessed `Yelp` dataset is available [here](https://drive.google.com/file/d/18wFU_l1kHlAZwjsZH6bGhsx_QqujSW64/view?usp=drive_link). Note that the original `Elliptic` dataset (CSV version) is also needed for exploring the dataset. `Elliptic` is publicly available at [here](https://www.kaggle.com/datasets/ellipticco/elliptic-data-set).
```
"""
The dataset folder was processed in the following structure；
└─elliptic
    └─elliptic.bat
└─elliptic_csv
    ├─elliptic_txs_classes.csv
    ├─elliptic_txs_edgelist.csv
    └─elliptic_txs_features.csv
└─yelp
    └─yelp.bat
"""
```

### Running the model

All the code is in the `main.ipynb`. After installing the dependencies you can run the notebook.

## Reference

```
@inproceedings{chai2022can,
  title = "{Can Abnormality be Detected by Graph Neural Networks?}", 
  author = {Ziwei Chai and Siqi You and Yang Yang and Shiliang Pu and Jiarong Xu and Haoyang Cai and Weihao Jiang, 
  booktitle={Proceedings of the 31st International Joint Conference on Artificial Intelligence (IJCAI)},
  year = 2022, 
} 
```