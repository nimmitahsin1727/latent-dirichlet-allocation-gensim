# latent-dirichlet-allocation-gensim

## About
Latent dirichlet allocation model from GENSIM library. 

Here, my main goal is to use my previously created preprocessed dataset [20-news-dataset-pre-processing](https://github.com/nimmitahsin1727/20-news-dataset-pre-processing) for GENSIM's LDA model [gensim.models.ldamulticore](https://radimrehurek.com/gensim/models/ldamulticore.html). And see the outcome.

**Outcome:**
```js
[(0,
  '0.009*"line" + 0.007*"write" + 0.006*"right" + 0.005*"use" + 0.004*"make" + '
  '0.004*"like" + 0.004*"say" + 0.004*"know" + 0.004*"point" + 0.004*"file"'),
 (1,
  '0.010*"line" + 0.008*"bike" + 0.007*"write" + 0.006*"like" + 0.005*"file" + '
  '0.004*"good" + 0.004*"use" + 0.004*"work" + 0.004*"know" + 0.004*"time"'),
 (2,
  '0.007*"file" + 0.007*"line" + 0.006*"image" + 0.006*"write" + 0.005*"use" + '
  '0.004*"know" + 0.004*"gun" + 0.004*"need" + 0.003*"just" + 0.003*"like"'),
 (3,
  '0.007*"line" + 0.006*"use" + 0.005*"image" + 0.005*"bike" + 0.005*"write" + '
  '0.004*"gun" + 0.004*"like" + 0.004*"file" + 0.004*"just" + 0.003*"make"'),
 (4,
  '0.008*"gun" + 0.007*"line" + 0.006*"use" + 0.006*"state" + 0.006*"write" + '
  '0.005*"right" + 0.005*"make" + 0.004*"like" + 0.004*"say" + 0.004*"good"'),
 (5,
  '0.008*"gun" + 0.007*"line" + 0.006*"write" + 0.005*"use" + 0.005*"good" + '
  '0.004*"point" + 0.004*"like" + 0.004*"make" + 0.003*"say" + 0.003*"state"'),
 (6,
  '0.008*"use" + 0.008*"line" + 0.007*"gun" + 0.006*"write" + 0.005*"just" + '
  '0.005*"like" + 0.005*"know" + 0.004*"make" + 0.004*"file" + 0.004*"image"'),
 (7,
  '0.012*"line" + 0.007*"write" + 0.006*"image" + 0.004*"use" + 0.004*"make" + '
  '0.004*"gun" + 0.004*"know" + 0.003*"just" + 0.003*"like" + 0.003*"file"'),
 (8,
  '0.009*"write" + 0.007*"line" + 0.006*"file" + 0.006*"use" + 0.005*"know" + '
  '0.005*"gun" + 0.004*"graphic" + 0.003*"state" + 0.003*"need" + '
  '0.003*"good"'),
 (9,
  '0.012*"line" + 0.007*"write" + 0.007*"gun" + 0.005*"use" + 0.005*"say" + '
  '0.005*"make" + 0.004*"file" + 0.004*"like" + 0.004*"thing" + 0.004*"know"')]
  ```

## Packages

- pandas
- nltk
- gensim

## Folder structure
```bash
├── lda-gensim.ipynb
├── training_df.csv
├── testing_df.csv
├── README.md
└── .gitignore
```
