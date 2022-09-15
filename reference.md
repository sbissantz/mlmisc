# My little reference list

* What does machine learning (ML) mean?

    Train an $\underbrace{\text{algorithm}}_{\text{aka. learner}}$  with a
    given set of features

* 2 forms of Machine Learning?
    1. Supervised learning
    1. Unsupervised learning

* What is supervised learning? 

    $T$: $L$ should use $\mathcal{D}=\{(X_i, y_i)\}_{i=1}^n$ to learn
    $f_\Theta: X \mapsto y$ so that it can accurately predict $y^{new} \in
    \mathcal{D}^{new}$.

e.g. using home attributes to predict the sales price

* Why is supervised learning "supervised"?

$\mathcal{D}:\{y,x\}$ you feed  Mathjax  includes the target values ($y$).

I.e.:  $y$ can help to supervise the training process to find optimal algorithm
$\thetas$'s.

* What is predictive modeling?

    Develop a mathematical $M$ to generate accurate predictions

* 2 "problems" in supervised learning 

    1. Regression problems 
    2. Classification problems

* What is a classification problem?
    $\underset{\text{learning}}{\overset{\text{supervised}}{\oplus}}$: predict
    a *categorical outcome*

* What is a regression problem?
    $\underset{\text{learning}}{\overset{\text{supervised}}{\oplus}}$: predict
    a *numeric outcome*

* Regression problem $\overset{?}{=}$ Classification problem

    $\overset{Regression}{f: \mathbb{R} \rightarrow \mathbb{R}}  \quad
    \quad\overset{Classification}{f: \mathbb{R} \rightarrow [0,1]_{\in
    \mathbb{R}^+}}$
    I.e.: when we predict the probability of a class

