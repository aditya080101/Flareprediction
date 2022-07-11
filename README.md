# machine-learning-with-solar-data
predicting solar eruptions using machine-learning methods

Of all the activity observed on the Sun, two of the most energetic events are flares and
Coronal Mass Ejections (CMEs). Coronal Mass Ejections (CMEs) are large blasts of energy that eject plasma from the Sun into interplanetary space; flares are more localized blasts that don't eject as much plasma into space. Usually, solar active regions that produce large flares will also produce a CME, but this is not always true.

We use machine-learning algorithms from [scikit-learn](http://scikit-learn.org/stable/) to [1] determine which features distinguish flares associated with CMEs from flares that are not, and [2] forecast whether an active region that produces a flare will also produce a CME. To do so, we use features derived from the photospheric vector magnetic field data taken by the Helioseismic and Magnetic Imager instrument aboard the Solar Dynamics Observatory, which takes the most data of any NASA satellite in history. We find that [1] we only need about 6 features to distinguish between the two populations, and [2] our True Skill Statistic, a forecast verification metric, is a relatively high value of approximately 0.8 plus or minus 0.2. 

### What is in this repository?

* The Jupyter notebook `cme_svm.ipynb` contains the original code we used to conduct this study.

* The Jupyter notebook `cme_svm_updated_for_pyastro.ipynb` contains updated code, using Python 3.7 and the most recent versions of the imported packages. 

```
