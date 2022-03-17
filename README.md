# dgl-benchmark-datasets

This project has the code to implement node classification on some benchmark datasets using DGL.

## To run the code

`python dgl-nc.py --data "cora" --h_feats 16 --lr 0.01 --epochs 100`

data = datasets (`"cora", "citeseer", "pubmed"`)  
h_feats = number of neurons in the hidden layer  
lr = learning rate (Adam optimizer is used)  
epochs = number of epochs

## Datasets 
1. Cora dataset

    Nodes: 2708  
    Edges: 10556  
    Number of Classes: 7  
    Label split:

            Train: 140
            Valid: 500
            Test: 1000

2. Citeseer dataset

    Nodes: 3327  
    Edges: 9228  
    Number of Classes: 6  
    Label Split:

            Train: 120
            Valid: 500
            Test: 1000

3. Pubmed citation network dataset

    Nodes: 19717  
    Edges: 88651  
    Number of Classes: 3  
    Label Split:

            Train: 60
            Valid: 500
            Test: 1000



