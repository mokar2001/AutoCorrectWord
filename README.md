# AutoCorrectWord
AutoCorrect words with Minimum Edit Distacne Algorithm and Shakespear dataset

### What is `lru_cache`?
It is a caching decorator that we have used it to act `min_edit_dist` like a momization recursive function.

Memoization is as fast as dynamic programming algorithms.

### Create a python file near `auto_correct.py`
### Example 
```python
from auto_correct import autoCorrect
print(autoCorrect('flw')) # flow
print(autoCorrect('fater')) # father
```
