# ASL-ML-Model
This code was made by Anthony Pham (part of Group 27) for Apply AI's Spring 2023 project. It is a very primitive attempt at implementing a RNN in order to label data files as one of five signs. Although the entire dataset from Google has 94,447 files across 250 signs, I only used five signs worth of data due to computing restrictions and my lack of ability at the time to create a more memory efficient model.

Graphical outputs are saved as images in the `accuracy_graphs` and the `loss_graphs` folders respectively. The GPU used for this is a GeForce RTX 2070 Super. The code was ran in Visual Studio Code with a conda environment. The Python version is 3.10.10, and the `tensorflow` version is 2.10.1 (the highest version that allows for gpu usage on Native Windows without any sort of workaround). All outputs can be viewed in `final_notebook.ipynb`.

More information of the contest can be found here: https://www.kaggle.com/competitions/asl-signs/overview


