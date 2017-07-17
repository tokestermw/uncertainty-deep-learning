# Uncertainty in Deep Learning

Example to get uncertainty intervals from Deep Learning models.

This example runs a linear regression in TensorFlow but it should be 
straightforward to extend it to deep learning models.

Install the requirements.

```
pip install -r requirements.txt
```

Run the script.

```
    python main.py simple_linear  # point estimate
    python main.py simple_linear .9  # Monte Carlo uncertainty interval
    python main.py bayesian_simple_linear  # Bayesian uncertainty interval
```

Medium blog post: https://medium.com/towards-data-science/adding-uncertainty-to-deep-learning-ecc2401f2013
