# Meta learning MAML

Model Agnostic Meta-Learning
Model Agnostic Meta-Learning (MAML) is one of the recently introduced and most popularly used meta-learning algorithms and It has created a breakthrough in meta-learning research. Learning to learn is the key focus of meta-learning and we know that in meta-learning, we learn from a various number of related tasks containing only a small number of data points and the meta-learner produces a quick learner that can generalize well on a new related task even with a lesser number of training samples.

The basic idea of MAML is to find the better initial parameters so that with good initial parameters the model can learn quickly on new tasks with a lesser gradient steps. So, what do we mean by that? Let us say we are performing a classification task using a neural network. How do we train the network? We will start with initializing random weights and train the network by minimizing the loss. How do we reduce the loss? We minimize the loss using gradient descent. Okay, but how do we use gradient descent to minimize the loss? We use gradient descent to find the optimal weights that will reduce loss. We take multiple gradient steps to find the optimal weights so that we can reach convergence. In MAML we try to find these optimal weights by learning from the distribution of similar tasks. So for a new task, we don't have to start with randomly initialized weights instead, we can start with optimal weights which will take lesser gradient steps to reach convergence and also it doesn't require more data points for training.

How to understand learn to learn?
You bring a kid to the zoo. He’s excited to see the fluffy animal in the water which he has never seen before. He asked you, what’s this? Although he has never seen this animal before, he is a smart lid and can learn by himself. Now, you give the kid a set of cards. On every card, there is an animal and its name. The kid has never seen an animal in the water. He has never seen the animals on the cards, either. But the kid is so smart that by taking a look at all the cards, he knows the animal in the water. The animal in the water is most similar to the animal on the card. Teaching the kid to learn by himself is called meta-learning.

Before going to the zoo, the kid was already able to learn by himself. He knew the similarity and differences between animals. In meta-learning, the unknown animal is called a query. You give him a card and let him learn by himself. The set of cards is the support set. Learning to learn by
himself is called meta-learning. If there is only one card for every species, the kid learns to recognize using only one card. This is called one-shot
learning.

Few-shot learning
Few-shot learning is the problem of making predictions based on a limited number of samples. Few-shot learning is different from standard supervised learning. The goal of few-shot learning is not to let the model recognize the images in the training set and then generalize to the test set. Instead, the goal is to learn. “Learn to learn” sounds hard to understand. You can think of it in this way.
![image](https://github.com/VasuTammisetti/Meta-learning-MAML-/assets/59999074/687e031f-785c-41c4-b202-15ace852eaa9)
