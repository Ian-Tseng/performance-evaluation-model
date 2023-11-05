# Performance-evaluation-model




### Idea 
1. This is a deep learning model that learn from the pre-scored answer data sets to predict performance score.
2. The basic idea is the model learn the logical pattern of pre-scored answer data sets from teacher.
3. Use the model to predict and evaluation the answers from students which can replace the teacher.


### Model architecture
The ANN model architecture using transformer.


### Prerequisite
- Python 3.10


### Install Dependency
```
requirements.txt
```


## Training data

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
