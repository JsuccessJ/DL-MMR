# Considering Length Diversity in Retrieval-Augmented Summarization

* Authors: Juseon-Do, Jaesung Hwang, Jingun Kwon, Hidetaka Kamigaito, Manabu Okumura
* Paper Link: [Considering Length Diversity in Retrieval-Augmented Summarization](https://arxiv.org/abs/2406.11097)


## Structure
```
DL-MMR
|
├── dataset
│   ├── Google
│   ├── Broadcast
│   └── BNC
|   
├── scripts
|
└── src
    └── faiss_utils
    └── inference_utils
    └── rag_utils


```

## Run
```
$ cd DL-MMR
$ bash scripts/save_metadata.sh
$ bash scripts/calcuate_distance.sh
$ bash scripts/retrieve.sh
$ bash scripts/inference.sh
```


# Evaluation
The metrics used in this work are listed in [evaluation_metrics](https://github.com/JuseonDo/InstructCMP/blob/main/src/evaluate_utils/evaluate_functions.py). For each metric, we have steps.txt which presents the steps to setup and run the metric.

# Contact
**jsuccessj@gmail.com**

