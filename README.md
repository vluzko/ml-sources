# ML sources
Original papers for prominent ML algorithms.

I can never remember where a given ML algorithm actually came from, and I'm tired of googling "SGS algorithm paper". Papers are organized by topic (and duplicated when they span topics). The standard for notability is "the algorithm has a name and I've heard of it". I try to link to the citable version (i.e. conference publication), but ultimately I'm lazy and if arXiv comes up first on Google I'm linking that until someone corrects me. I also link to the Semantic Scholar page because that's what I use to organize my research.

## Reinforcement Learning
* DQN: [Playing Atari with Deep Reinforcement Learning](https://arxiv.org/abs/1312.5602)
    * [Semantic Scholar](https://www.semanticscholar.org/paper/Playing-Atari-with-Deep-Reinforcement-Learning-Mnih-Kavukcuoglu/2319a491378867c7049b3da055c5df60e1671158)
* DDQN: [Deep Reinforcement Learning with Double Q-learning](https://dl.acm.org/doi/10.5555/3016100.3016191)
    * [Semantic Scholar](https://www.semanticscholar.org/paper/Deep-Reinforcement-Learning-with-Double-Q-Learning-Hasselt-Guez/3b9732bb07dc99bde5e1f9f75251c6ea5039373e)
* Rainbow: [Rainbow: Combining Improvements in Deep Reinforcement Learning](https://arxiv.org/abs/1710.02298)
    * [Semantic Scholar](https://www.semanticscholar.org/paper/Rainbow%3A-Combining-Improvements-in-Deep-Learning-Hessel-Modayil/0ab3f7ecbdc5a33565a234215604a6ca9d155a33)
* A3C: [Asynchronous Methods for Deep Reinforcement Learning](http://proceedings.mlr.press/v48/mniha16.html)
    * [Semantic Scholar](https://www.semanticscholar.org/paper/Asynchronous-Methods-for-Deep-Reinforcement-Mnih-Badia/69e76e16740ed69f4dc55361a3d319ac2f1293dd)
* TRPO: [Trust Region Policy Optimization](http://proceedings.mlr.press/v37/schulman15.html)
    * [Semantic Scholar](https://www.semanticscholar.org/paper/Trust-Region-Policy-Optimization-Schulman-Levine/66cdc28dc084af6507e979767755e99fe0b46b39)
* PPO: [Proximal Policy Optimization Algorithms](https://arxiv.org/abs/1707.06347)
    * [Semantic Scholar](https://www.semanticscholar.org/paper/Proximal-Policy-Optimization-Algorithms-Schulman-Wolski/dce6f9d4017b1785979e7520fd0834ef8cf02f4b)

### Continuous Action Spaces
* DPG: [Deterministic Policy Gradient Algorithms](http://proceedings.mlr.press/v32/silver14.html)
    * [Semantic Scholar](https://www.semanticscholar.org/paper/Deterministic-Policy-Gradient-Algorithms-Silver-Lever/687d0e59d5c35f022ce4638b3e3a6142068efc94)
* DDPG: [Continuous control with deep reinforcement learning](https://arxiv.org/abs/1509.02971)
    * [Semantic Scholar](https://www.semanticscholar.org/paper/Continuous-control-with-deep-reinforcement-learning-Lillicrap-Hunt/024006d4c2a89f7acacc6e4438d156525b60a98f)
* TD3: [Addressing Function Approximation Error in Actor-Critic Methods](https://arxiv.org/abs/1802.09477)
    * [Semantic Scholar](https://www.semanticscholar.org/paper/Addressing-Function-Approximation-Error-in-Methods-Fujimoto-Hoof/4debb99c0c63bfaa97dd433bc2828e4dac81c48b)
* SAC: [Soft Actor-Critic: Off-Policy Maximum Entropy Deep Reinforcement Learning with a Stochastic Actor](http://proceedings.mlr.press/v80/haarnoja18b.html)
    * [Semantic Scholar](https://www.semanticscholar.org/paper/Soft-Actor-Critic%3A-Off-Policy-Maximum-Entropy-Deep-Haarnoja-Zhou/811df72e210e20de99719539505da54762a11c6d)

## Causality

### Causal Discovery

#### Constraint Based
* PC: [An Algorithm for Fast Recovery of Sparse Causal Graphs ](https://journals.sagepub.com/doi/10.1177/089443939100900106)
    * [Semantic Scholar](https://www.semanticscholar.org/paper/An-Algorithm-for-Fast-Recovery-of-Sparse-Causal-Spirtes-Glymour/ade157c4ddb211819914c17e4efde6d33489e3b5)
    * *Causation, Prediction, Search* often gets cited as well, even by the authors. Talk to your doctor about which reference is right for you.
* IC: [Equivalence and synthesis of causal models](https://dl.acm.org/doi/10.5555/647233.719736)
    * [Semantic Scholar](https://www.semanticscholar.org/paper/Equivalence-and-synthesis-of-causal-models-Verma-Pearl/17d451204a460a4739c7b1627a128a125f4af120)
* SGS: *Causation, Prediction, Search* usually gets cited (it's section 5.4.1).
    * The book itself cites SGS 1990c, which is not actually an entry in their bibliography. It *might* mean [Causality from Probability](https://www.semanticscholar.org/paper/Causality-From-Probability-Spirtes-Glymour/c85e4607650d78eabbd0715a443b2cd37a1f35fb), but honestly I would just cite the textbook.

#### Score Based
* GES:



## Deep Learning

### Architectures
* ResNets: [Deep Residual Learning for Image Recognition](https://ieeexplore.ieee.org/document/7780459)
    * [Semantic Scholar](https://www.semanticscholar.org/paper/Deep-Residual-Learning-for-Image-Recognition-He-Zhang/2c03df8b48bf3fa39054345bafabfeff15bfd11d)

### Training
* Adam: [Adam: A Method for Stochastic Optimization](https://arxiv.org/abs/1412.6980)
    * [Semantic Scholar](https://www.semanticscholar.org/paper/Adam%3A-A-Method-for-Stochastic-Optimization-Kingma-Ba/a6cb366736791bcccc5c8639de5a8f9636bf87e8)
* Dropout: [Dropout: A Simple Way to Prevent Neural Networks from Overfitting](https://jmlr.org/papers/v15/srivastava14a.html)
    * [Semantic Scholar](https://www.semanticscholar.org/paper/Dropout%3A-a-simple-way-to-prevent-neural-networks-Srivastava-Hinton/34f25a8704614163c4095b3ee2fc969b60de4698)
* BatchNorm: []()

## Image Recognition
* AlexNet: [ImageNet Classification with Deep Convolutional Neural Networks](https://papers.nips.cc/paper/2012/hash/c399862d3b9d6b76c8436e924a68c45b-Abstract.html)
    * [Semantic Scholar](https://www.semanticscholar.org/paper/ImageNet-classification-with-deep-convolutional-Krizhevsky-Sutskever/abd1c342495432171beb7ca8fd9551ef13cbd0ff)


