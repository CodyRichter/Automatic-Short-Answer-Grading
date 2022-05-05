## Dataset

SemEval-2013 SciEntsBank Dataset

All of the original XML files have been parsed into .json files which are much easier to
load and handle for our team's models.


Original Source of Dataset Files: [This Github Repo](https://github.com/leocomelli/score-freetext-answer/tree/master/src/main/resources/corpus/semeval2013-task7)

### Notebooks

The notebook `Dataset_Transformation_+_Augmentation.ipynb` fetches the original SciEntsBank dataset XML files, parses them, and performs the process of backtranslation to generate the training set. The files that this notebook generates are stored in this folder in the Github repo.

The notebook `Dataset_Loader.ipynb` provides a template for loading in the the dataset, and is used in the start of many of our other project notebooks. This *must* be run after the original dataset is loaded, or the files will not exist.
