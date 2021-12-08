# Code for Toward Fine-Grained Sketch-Based 3D Shape Retrieval---Coming Soon

This repository is the official implementation of [Toward Fine-Grained Sketch-Based 3D Shape Retrieval](https://ieeexplore.ieee.org/document/9573376). 

<img width="703" alt="Screenshot 2021-12-08 at 11 50 00" src="https://user-images.githubusercontent.com/52857437/145203740-766f288a-c7ab-4271-b07d-2e624cd2a572.png">

## Requirements

To install requirements:

```setup
pip install -r requirements.txt
```
## Dataset

Please download the proposed dataset from the SketchX Lab [here](http://personal.ee.surrey.ac.uk/Personal/Y.Song/AmateurSketch-3DChair.zip). 


## Training

To train the model(s) in the paper, run this command:

```train
python train.py
```

## Evaluation

To evaluate my model on the proposed dataset, run:

```eval
python eval.py 
```

## Results

Our model achieves the following performance on :


| category           | Top 1 Accuracy  | Top 5 Accuracy |
| ------------------ |---------------- | -------------- |
| Chair              |     56.72%      |      87.06%    |
| Lamp               |     57.66%      |      87.39%    |



