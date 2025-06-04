# Performance-evaluation-model




### Overview 
This is a deep learning model designed to predict performance scores of concept map type questions based on pre-scored concept map question answers. It leverages features derived from logical or graph-based transformations of the input data.


### Model architecture
The model is based on the Transformer architecture, which is well-suited for learning from structured and sequential data such as concept maps.


### Prerequisite
- Python 3.10


### Installation
To install the required dependencies, run:
```
pip install -r requirements.txt
```


## Training Data Format
The training dataset consists of:

Answer: A list of node identifiers from the concept map.

Block relation: Directed edges representing logical or semantic relationships between the nodes.

Expected score: A score representing the correctness or relevance of each relation.

| Answer               | Block relation | Expected score |
|----------------------|----------------|----------------|
| [1, 2, 3, 4, 6, 104] | [1, '->', 2]   | 5              |
|                      | [2, '->', 3]   | 5              |
|                      | [3, '->', 4]   | 5              |
|                      | [4, '->', 6]   | 1              |
|                      | [6, '->', 104] | -5             |
| [1, 2, 3, 4, 6, 106] | [1, '->', 2]   | 5              |
|                      | [2, '->', 3]   | 5              |
|                      | [3, '->', 4]   | 5              |
|                      | [4, '->', 6]   | 1              |
|                      | [6, '->', 106] | -5             |

## AUTHORS
[Ian-Tseng](https://github.com/Ian-Tseng/)
