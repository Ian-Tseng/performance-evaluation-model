# Performance-evaluation-model




### Idea 
1. This is a deep learning model that learn from the pre-scored concept map question's answer dataset to predict performance score.
2. It learns the feature that data transformed into logical feature or graph feature.


### Model architecture
The model architecture is transformer.


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
