Opinion holder detection comprises two steps: the presence of opinion holders
in the text and the identification of opinion holders. For the first step, we propose a novel
binary classification, namely INSIDE, and OUTSIDE. In the dataset, 1 indicates INSIDE and 0 indicates OUTSIDE class.

The second step of opinion holder detection is handled as sequence labeling task through BIO tagging. In the dataset, we utilized 3 tags: B-OH, I-OH, and O.
We prepared the column format dataset similar to the most named entity recognition (NER) datasets. The first column is the token itself and the second column is BIO-annotated tags. Each empty line separates each instance/review.

Both the datasets contain a total of 1,453 instances/review.

If you use thsese datasets, please refer the follwoing paper:
@article{Al-Mahmud2023OHD,
author    = {Al-Mahmud and Shimada, Kazutaka},
title     = {Dataset Construction and Opinion Holder Detection Using Pre-trained Models},
publisher = {IIAI Publications},
journal   = {IJSKM},
volume    = {7},
NUMBER = {2},
pages={1-17},
doi       = {https://doi.org/10.52731/ijskm.v7.i2.779},
year      = {2023},
}
