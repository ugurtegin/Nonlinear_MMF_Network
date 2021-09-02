# Scalable Optical Learning Operator 

This repository contains code used for the manuscript title as Scalable Optical Learning Operator by Tegin et al. (2020). https://arxiv.org/abs/2012.12404 

In the experiments, SLM control is performed with the Matlab Code provided by Rosales-Guzmán, C., & Forbes, A. (2017). How to shape light with spatial light modulators. SPIE Press and the camera control is obtained via Thorlabs SDK and Doc. for Scientific Cameras example code. 

## Code
Code/Simulations folder contains a time-dependent beam propagation simulation for graded-index multimode fiber. The code is written in Python with the CuPy library to perform GPU parallelized simulations. 

Code/Experiments folder contains the numerical decision layer used in the manuscript. Regression and categorization tasks for the studied datasets in the manuscript are performed with these codes written in Python with Tensorflow library and Keras API. Experimentally recorded data is required to run the decision layer code.

## Data
Data folder contains the experimentally recorded, downsampled, flattenned and normalized fiber output patterns and data labels for machine learning taks.

## How to:

Use the shared notebooks containing the example code in Code/Experiments folder

* To obtain Figure 2 in the figure, please run the corresponding code under Code/Experiments directory with Sinc.zip file.
* To obtain Figure 3 in the figure, please run the corresponding code under Code/Experiments directory with Abalone.zip, Face.zip, Audio Digit.zip and Audio Speaker.zip files.
* To obtain Figure 4 in the figure, please run the corresponding code under Code/Experiments directory with Covid-19.zip file.
* To obtain Figure 6 in the figure, please run the corresponding code under Code/Simulations directory.

## Related Work
[Scalable Optical Learning Operator](https://www.nature.com/articles/s43588-021-00112-0)

Teğin, U., Yıldırım, M., Oğuz, İ., Moser, C., & Psaltis, D. (2021). Scalable optical learning operator. Nature Computational Science, 1(8), 542-549.	

```
@article{teugin2021scalable,
  title={Scalable optical learning operator},
  author={Te{\u{g}}in, U{\u{g}}ur and Y{\i}ld{\i}r{\i}m, Mustafa and O{\u{g}}uz, {\.I}lker and Moser, Christophe and Psaltis, Demetri},
  journal={Nature Computational Science},
  volume={1},
  number={8},
  pages={542--549},
  year={2021},
  publisher={Nature Publishing Group}
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
