# Auto-performance-evaluation-with-LSTM


## Prerequisite
- Python 3.10

### Install Dependency
```
requirements.txt
```


### Idea 
```
1. This is a system that execute performace evaluation automatically.
2. Learn a evaluation pattern from teacher and train with LSTM.
3. Use the model to predict and evaluation the answer of students in same question.

```

## Training data
| Answer               | Block relation | Expected score | Block relation | Expected score | Block relation | Expected score | Block relation | Expected score Block relation | Expected score |
|----------------------|----------------|----------------|----------------|----------------|----------------|----------------|----------------|----------------|----------------|----------------|
| [1, 2, 3, 4, 6, 104] | [1, '->', 2]   | 5              | [2, '->', 3]   | 5              | [3, '->', 4]   | 5              | [4, '->', 6]   | 1              | [6, '->', 104] | -5             |
| [1, 2, 3, 4, 6, 106] | [1, '->', 2]   | 5              | [2, '->', 3]   | 5              | [3, '->', 4]   | 5              | [4, '->', 6]   | 1              | [6, '->', 106] | -5             |


## AUTHORS
[Ian-Tseng](https://github.com/Ian-Tseng/)
