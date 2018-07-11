# Siamese Neural Networks for Few Shot Learning
<img src="https://camo.githubusercontent.com/b27757e11d8687dc846b016e0fac80a544e7b645/68747470733a2f2f736f72656e626f756d612e6769746875622e696f2f696d616765732f5369616d6573655f6469616772616d5f322e706e67"></img>

## The problem has been inspired by [Fellowship.AI, demo challenge](https://fellowship.ai/challenge/)
- The model has been trained using tensforflow backend in Keras.
- It tries to solve the problem of image verification when the quantity of data available for training Deep Learning models is less.
- The model has been implemented to solve the problem based on the paper by **Gregory et. al** [Siamese Neural Networks for One-Shot Image Recognition](https://www.cs.cmu.edu/~rsalakhu/papers/oneshot1.pdf).
  -  The ideas from the paper have been used to extend the model for few shot learning.

- [Omniglot](https://github.com/brendenlake/omniglot), dataset has been used for training the model 
  - The dataset has 1623 character classes, each with 20 examples.
  - The model tries to build a few shot classifier using the ides presented in the paper by **Gregory et. al** for the dataset.
  
### Reading
  - [Siamese Neural Networks for One-Shot Image Recognition](https://www.cs.cmu.edu/~rsalakhu/papers/oneshot1.pdf)
