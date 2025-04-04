# Data Preparation Stage

- Convert my data in train & test.tsv into 70:30 ratio
```
data.xml
    |-train.tsv
    |-test.tsv

```
- We will be choosing only three tags in the xml data - 1. row Id, 2. title & body, 3. Tags (Stackoverflow tags)

|Tags|feature names|
|-|-|
|row Id|row ID|
|title and body|text|
|stackoverflow tags|Label - Python|