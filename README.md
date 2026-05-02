# neural_network_course_SS26
This repository is the basis for the course "Neural Networks: An application-oriented introduction" at the University of Regensburg, Germany, taught by Sven Weinzierl in the summer semester 2026.

The recommended way to work with this repository is to clone it and then update the code base throughout the course.

### Colab & Kaggle
When using Colab or Kaggle, you should upload the Jupyter Notebook and run the following commands in a code block:

```
!git clone https://github.com/SvenWeinzierl/neural_network_course_SS26
```

and

```
!pip install lightning
```

Additionally, you should change the imports as follows:

```
from data import CatDogDataModule, MNISTDataModule
```

to 

```
from neural_network_course_SS26.data import CatDogDataModule, MNISTDataModule
```

The same needs to be done for the other Python files (model, helper).
