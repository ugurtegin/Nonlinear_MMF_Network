# Scalable Optical Learning Operator 

This repository contains code used for the manuscript title as Scalable Optical Learning Operator by Tegin et al. (2020). https://arxiv.org/abs/2012.12404 

In the experiments, SLM control is performed with the Matlab Code provided by Rosales-Guzmán, C., & Forbes, A. (2017). How to shape light with spatial light modulators. SPIE Press and the camera control is obtained via Thorlabs SDK and Doc. for Scientific Cameras example code. 

## Code
Code/Simulations folder contains a time-dependent beam propagation simulation for graded-index multimode fiber. The code is written in Python with the CuPy library to perform GPU parallelized simulations. 

Code/Experiments folder contains the numerical decision layer used in the manuscript. Regression and categorization tasks for the studied datasets in the manuscript are performed with these codes written in Python with Tensorflow library and Keras API. Experimentally recorded data is required to run the decision layer code.

## Data
Data folder contains the experimentally recorded, downsampled, flattenned and normalized fiber output patterns and data labels for machine learning taks.

## How to:

Use the shared notebooks containing the example code in Experiments folder

* To obtain Figure 2 in the figure, please run the corresponding code under Code/Experiments directory with Sinc.zip file.
* To obtain Figure 3 in the figure, please run the corresponding code under Code/Experiments directory with Abalone.zip, Face.zip, Audio Digit.zip and Audio Speaker.zip files.
* To obtain Figure 4 in the figure, please run the corresponding code under Code/Experiments directory with Covid-19.zip file.
* To obtain Figure 6 in the figure, please run the corresponding code under Code/Simulations directory.

## Related Work
[Scalable Optical Learning Operator](https://arxiv.org/abs/2012.12404)

Uğur Teğin, Mustafa Yıldırım, İlker Oğuz, Christophe Moser, and Demetri Psaltis 2020. Scalable Optical Learning Operator. arXiv.

```
@article{teğin2020scalable,
      title={Scalable Optical Learning Operator}, 
      author={Uğur Teğin and Mustafa Yıldırım and İlker Oğuz and Christophe Moser and Demetri Psaltis},
      year={2020},
      eprint={2012.12404},
      journal={arXiv},
      primaryClass={physics.optics}
}
```

## System Requirements
Google Colab services

CuPy based on Cuda 11.0

Tensorflow 2.4.0

Python 3

## DOI & Zenodo
https://doi.org/10.5281/zenodo.5090719

## Contact
Please contact [Uğur Teğin](http://www.ugurtegin.com/) for questions.

## License
This project is covered under the Creative Common (CC BY NC) License. The data and code are avaiable for non-commercial research purposes only with proper citation to aforementioned manuscript.
