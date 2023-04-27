# About the code
This code was made by Anthony Pham (part of Group 27) for Apply AI's Spring 2023 project. It is a very primitive attempt at implementing a RNN in order to label data files as one of five signs. Although the entire dataset from Google has 94,447 files across 250 signs, I only used five signs worth of data due to computing restrictions and my lack of ability at the time to create a more memory efficient model.

Graphical outputs are saved as images in the `cumulative-model-graphs` and the `single-model-graphs` folders respectively. The GPU used for this is a GeForce RTX 2070 Super. The code was ran in Visual Studio Code with a conda environment. The Python version is 3.10.10, and the `tensorflow` version is 2.10.1 (the highest version that allows for gpu usage on Native Windows without any sort of workaround). All outputs can be viewed in `final_notebook.ipynb`.

# About the challenge
More information of the contest can be found here: https://www.kaggle.com/competitions/asl-signs/overview

The model uses data from this challenge and the purpose of the model is the same as the purpose of models submitted to that content. The difference is that this project is mainly for personal learning and will not be submitted to the contest.

# Acknoledgement of the data and its license
The dataset is provided by Deaf Professional Arts Network and the Georgia Institute of Technology is licensed under CC-BY 4.0. A copy of the license can be found here: https://creativecommons.org/licenses/by/4.0/
