# Spelling Recommender
_Take a list of misspelled words and recommends a correctly spelled word for every word in the list_

<p align="center">
<img src="https://predictivehacks.com/wp-content/uploads/2020/09/similarity_text.jpg" height="300px">
</p>

## Methods
- [Jupyter Notebook](https://github.com/vanessaaleung/spelling-recommender/blob/main/Spelling_Recommender.ipynb)

### 1. [Jaccard distance](https://en.wikipedia.org/wiki/Jaccard_index) - Trigrams
_Provide recommendations using the Jaccard distance on the trigrams of the two words metric_

Jaccard distance is obtained by dividing the difference of the sizes of the union and the intersection of two sets by the size of the union

<img src="https://wikimedia.org/api/rest_v1/media/math/render/svg/3d17a48a5fb6cea57b076200de6edbccbc1c38f9">

### 2. Jaccard distance - 4-grams
_Provide recommendations using the Jaccard distance on the 4-grams of the two words metric_

### 3. [Edit Distance](https://en.wikipedia.org/wiki/Damerau%E2%80%93Levenshtein_distance)
_Provide recommendations using the Edit distance on the two words with transpositions metric_

The edit distance between two words is the minimum number of operations (insertions / deletions / substitutions of a single character, or transposition of two adjacent characters) required to change one word into the other
