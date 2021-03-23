# Automatic Delineation of Agricultural Fields from Sentinel-2 Images

This repository is dedicated to the results of a group assignment of one of the
minors at the University of Twente.
The aim of the assignment was to train a fully convolutional neural network to
precisely predict the boundaries of agricultural fields.


The implementation is split into three different Jupyter notebooks. The code is
designed to run on [Google Colab](https://colab.research.google.com/).

It is split into three different notebooks. All code files are well documented.


**network-training.ipynb**

This notebook is desinged to train a network with a given configuration.


**network-testing.ipynb**

Includes the accuracy assessment as well as sample outputs of the training data
set of a trained network.


**network-prediction.ipynb**

Used to predict the field boundaries with the help of a pretrained network.
The field boundaries are stored as TIF files. The predictions of the three FCNs
which are considered in the paper are all included in the related data set.

The data set is available online: [doi.org/10.17026/dans-za6-m8t7](https://doi.org/10.17026/dans-za6-m8t7)



## FCNs

Apart from the paper, the repository also contains the differently trained
networks.
Each network was trained with 600 epochs each.
The digit, behind the network's name defines the number of layers that were used
to train the network.
As one can derive from the folder names, the chosen networks of this assignment
are the [FCN-DK](https://ieeexplore.ieee.org/document/8094993) network as well
as [U-Net](https://arxiv.org/pdf/1505.04597.pdf).


## Data set

The data set is published under creative-common terms CC-BY-4.0.
Details can be found in the LICENSE file of the data set.
The link to the data set will be published soon.


## Group Members / Contributors

The group consists of the following members:

* Floor Stefess
* Lars van der Velde
* Laurens Laarhuis
* Matthijs Horst
* Max Resing
* Paula Janeka
* Simonas Budėjis

Also, we would like to acknowledge our supervisor [Claudio Persello](https://research.utwente.nl/en/persons/claudio-persello).


## Contact/Feedback

We will be happy to answer feedback, questions and bug reports.
Either contact [Max Resing](https://www.maxresing.de/contact.html) or [open an issue](https://github.com/resingm/field-boundary-delineation/issues/new).


# License

The code is published under the [GPL-3.0 license](https://www.gnu.org/licenses/gpl-3.0.en.html).
Details can be found in the LICENSE file.

