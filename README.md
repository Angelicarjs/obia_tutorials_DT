# Open source OBIA

## Content


| notebook | link (exercise) | link (solution) | description |
| :-------- | -----  | ----- | --------- |
| `01_segmentation.ipynb` | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mariarodriguezn/obia_tutorials/blob/main/01_segmentation_exercise.ipynb) | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mariarodriguezn/obia_tutorials/blob/main/01_segmentation.ipynb) | Investigating different image segmentation methodologies | 
| `02_features_extraction.ipynb` | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mariarodriguezn/obia_tutorials/blob/main/02_features_extraction_exercise.ipynb) | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mariarodriguezn/obia_tutorials/blob/main/02_features_extraction.ipynb) | Calculating various feature descriptors (spectral, spatial, textural) |
| `03_classification.ipynb` | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mariarodriguezn/obia_tutorials/blob/main/03_classification_exercise.ipynb) | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mariarodriguezn/obia_tutorials/blob/main/03_classification.ipynb) | Exploring image classification using ruled based thresholds & Random Forest|


## Background

This repo is meant to be a small collection of notebooks to showcase how object-based image analyses (OBIA) can be performed with standard python libraries. Whereas Trimble eCognition offers the full suite of OBIA algorithms in a proprietary software environment, open source possibilities for OBIA are generally more limited. Still, basic workflows can be realized in python. Besides the obvious advantage of saving on royalties, they can be useful for the following reasons:
1. Easier integration into larger workflows -> when the focus isn't a complex OBIA workflow itself but a rather basic segmentation or some object features needed as interim products in a processing pipeline that otherwise can be realized in python (e.g. machine learning based land cover classification)
2. Automation -> The flexibility offered by the variety of libraries together along the option to create custom functions allows to automate basically any process, which may be difficult to automate in other, closed-source software environments   
3. Efficiency -> Although not always the case, the flexibility of multicore processing with thread parallelization can actually lead to a more performant workflow.
4. Enhanced reproducibility -> Whereas repeatability (i.e. obtaining the same results under same conditions by the same people) is also given for processing workflows realized with proprietary software, replicability and reproducibility (aiming at the cross-checking of results by others) is facilitated by relying on open source implementations.           

## Sample Data

For demonstration purposes a 4-channel orthophoto (R,G,B,NIR) with 10cm ground spacing acquired in North-Rhine Westphalia 2021. A smaller subset out of the original 10.000 x 10.000 pixels orthophoto was formed. The data license permits the re-use and distribution without restrictions and conditions.

<img src="assets/outputs_overview.png" width="100%">
