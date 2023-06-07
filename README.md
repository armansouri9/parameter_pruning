# Parameter Pruning Readme

This repository provides an implementation of parameter pruning for reducing the parameters of a neural network model. Three different pruning techniques are demonstrated: parameter pruning, significant pruning, and weight-based pruning. The code is implemented using PyTorch.

## Repository Specifications

- Repository Link: [https://github.com/armansouri9/parameter_pruning/](https://github.com/armansouri9/parameter_pruning/)
- Language: Python
- Dependencies: PyTorch

## Parameter Reduction using Parameter Pruning

The code in this section demonstrates parameter pruning to reduce the number of parameters in a neural network model. The model is trained on a simple training dataset and then pruned using L1 unstructured pruning. The pruned model is evaluated on a test dataset to measure its accuracy.

## Significant Pruning

In this section, significant pruning is applied to the neural network model. The model is trained on a training dataset, and then L2 structured pruning is applied to the first fully connected layer. The pruned model is evaluated on a test dataset to measure its accuracy.

## Weight-based Pruning

The code in this section demonstrates weight-based pruning. The neural network model is trained on a training dataset, and then L2 structured pruning is applied to the first fully connected layer. The pruned model is evaluated on a test dataset to measure its accuracy.

Please refer to the Jupyter Notebook files in the repository for the complete code implementation and further details.

## Usage

1. Clone the repository:

```
git clone https://github.com/armansouri9/parameter_pruning.git
```

2. Install the required dependencies (e.g., PyTorch).

3. Open the Jupyter Notebook files to view and execute the code.

Feel free to explore and modify the code to fit your needs. If you have any questions or suggestions, please open an issue in the repository.

## License

This project is licensed under a Free License.
