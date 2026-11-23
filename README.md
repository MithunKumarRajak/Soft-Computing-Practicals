# Soft Computing Practicals

A collection of college assignment notebooks for the course **Soft Computing (EL1)**.

**Course Code:** STEL3101

**Program:** B.Tech. Computer Science and Engineering

## Assignment Structure

| Assignment | Module | Notebook | Practical Topics |
|---|---|---|---|
| Assignment 1 | Module 1 | [SC_Assignment_1.ipynb](Assignment%201_module%201/SC_Assignment_1.ipynb) | Fuzzy sets, membership functions, fuzzy relations, fuzzy rules, Mamdani and Sugeno inference, defuzzification, and fuzzy logic control |
| Assignment 2 | Module 2 | [SC_Assignment_2.ipynb](Assignment%202_Module%202/SC_Assignment_2.ipynb) | Artificial neurons, weighted sums, activation functions, neural network layers, gradient descent, backpropagation, and neural network classification |
| Assignment 2 | Module 3 | [SC_Assignment_2.ipynb](Assignment%202_Module%203/SC_Assignment_2.ipynb) | Population encoding, fitness evaluation, selection, crossover, mutation, Genetic Algorithms, Particle Swarm Optimization, Differential Evolution, and DEAP |

## Module 1: Fuzzy Logic

1. Create and visualize simple fuzzy sets.
2. Plot triangular, trapezoidal, and Gaussian membership functions.
3. Perform fuzzy union, intersection, and complement operations.
4. Create fuzzy relations.
5. Create linguistic variables for Low, Medium, and High states.
6. Define fuzzy IF-THEN rules.
7. Implement a Mamdani fuzzy inference system.
8. Implement a Sugeno fuzzy inference system.
9. Compare centroid, bisector, and mean-of-max defuzzification.
10. Design a fuzzy logic controller.

## Module 2: Neural Networks

1. Implement the working of an artificial neuron.
2. Calculate weighted sums and bias values.
3. Visualize sigmoid, tanh, and ReLU activation functions.
4. Create a single-layer neural network.
5. Create a multilayer perceptron using Keras/TensorFlow.
6. Apply gradient descent for weight updates.
7. Implement basic backpropagation.
8. Train a neural network on a dataset.
9. Evaluate a trained neural network.
10. Build a complete neural network classification system.

## Module 3: Evolutionary and Swarm Optimization

1. Represent populations using binary, integer, and real-valued encoding.
2. Define a fitness function.
3. Implement tournament and roulette-wheel selection.
4. Perform single-point crossover.
5. Implement bit-flip mutation.
6. Combine GA operators in a simple Genetic Algorithm.
7. Study fitness convergence across generations.
8. Implement Particle Swarm Optimization.
9. Implement Differential Evolution.
10. Build a complete DEAP-based Genetic Algorithm.

## Technologies Used

- Python 3
- Jupyter Notebook / VS Code Notebook
- NumPy
- Matplotlib
- scikit-fuzzy
- scikit-learn
- TensorFlow and Keras
- DEAP

## Setup

Clone the repository and change into the project directory:

```bash
git clone https://github.com/MithunKumarRajak/Soft-Computing-Practicals.git
cd Soft-Computing-Practicals
```

Create and activate a virtual environment:

```bash
python -m venv .venv
.venv\Scripts\activate
```

Install the required packages:

```bash
python -m pip install jupyter numpy matplotlib scikit-fuzzy scikit-learn tensorflow deap
```

Launch Jupyter:

```bash
jupyter notebook
```

Open the required notebook and run all cells from top to bottom.

## Notes

- TensorFlow may require a compatible Python version and environment.
- DEAP can also be installed from inside a notebook with:

```python
%pip install deap
```

- Visualizations are generated with Matplotlib.
- Randomized algorithms use fixed random seeds or NumPy random generators where reproducible output is required.
