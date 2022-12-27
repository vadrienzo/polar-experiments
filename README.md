# polar-experiments

While installing polar on my conda enviroment I noticed that there is an import error from `sckit-learn`.
Apparently, `polar` is trying to import `plot_confusion_matrix` which is no in scikit-learn.
```
from sklearn.metrics import plot_confusion_matrix
```
At the moment I commented that line of code on the site-packages but I do not know how to fix it.

 

