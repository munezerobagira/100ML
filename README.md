# Machine Learning

## Types
1. Supervised  Learning
2. Unsupervised Learning
3. Semi -supervised Learning
4. Reinforcement Learning


### Supervised  Learning
he dataset is a collection of labeled examples is
i=1.{(xi, yi)}N
i=1
X is feature vector while Y is Label, each feature vector has one or more  feature.  Label can be element belonging to set of Feature.
``` 
The goal of a supervised learning algorithm is to use the dataset to produce a model
that takes a feature vector x as input and outputs information that allows deducing the label
for this feature vector.
```
For instance, the model created using the dataset of people could
take as input a feature vector describing a person and output a probability that the person
has cancer.
### Unsupervised Learning 
he dataset is a collection of unlabeled examples {xi}N
i=1.
```
the goal of an unsupervised learning algorithm is
to create a model that takes a feature vector x as input and either transforms it into
another vector or into a value that can be used to solve a practical problem
```
### Semi-Supervised Learning
In semi-supervised learning, the dataset contains both labeled and unlabeled examples.
Usually, the quantity of unlabeled examples is much higher than the number of labeled
examples.
```
The goal of a semi-supervised learning algorithm is the same as the goal of
the supervised learning algorithm.
```
### Reinforcement Learning
it is capable of perceiving the state of that environment as a vector of
features. The machine can execute actions in every state. Different actions bring different
rewards and could also move the machine to another state of the environment.
```
The goal
of a reinforcement learning algorithm is to learn a policy. A policy is a function f (similar
to the model in supervised learning) that takes the feature vector of a state as input and
outputs an optimal action to execute in that state. The action is optimal if it maximizes the
expected average reward.
```
