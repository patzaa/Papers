Paper Summary
=============
_A list of papers I find interesting including a single sentece on main findings. On topics in NLP, ML and RL.
Specifically, Knowledge Graph Embeddings, Dialoge Systems, Reasoning using RL, and Transformer-based architectures._  

Content (2021)
========= 
  - [Graph Embeddings](#Graph-Embeddings) 
  - [Reasoning](#Reasoning)
  - [Deep Learning](#Computer-Vision)
  - [Reinforcement Learning](#Reinforcement-Learning)
  - [NLP](#Architectures) 

![](https://github.com/patzaa/Papers/blob/master/Title.png?raw=true)

2021
-------
### Graph Embeddings: 
### Reasoning:
### Deep Learning:

- [Transporter Networks: Rearranging the Visual World for Robotic Manipulation](https://arxiv.org/pdf/2010.14406.pdf): Transporter Network as a simple model architecture that rearranges deep features to infer spatial displacements from visual input for robotic manipulation
- [Perceiver: General Perception with Iterative Attention](https://arxiv.org/abs/2103.03206): Introducing the Perceiver, a model that builds upon Transformers and hence makes few architectural assumptions about the relationship between its inputs, such as grid like structure in pictures for example. 
- [Rethinking Spatial Dimensions of Vision Transformers](https://arxiv.org/abs/2103.16302): Empirically show that such a spatial dimension reduction is beneficial to a transformer architecture as well, and propose a novel Pooling-based Vision Transformer (PiT)
- [FNet: Mixing Tokens with Fourier Transforms](https://arxiv.org/pdf/2105.03824.pdf): Fourier transformations applied to tokens replaces the self-attention layer with an resuting accuracy of 92% compared to BERT. 
### Reinforcement Learning: 
 - [Asymmetric self-play for automatic goal discovery in robotic manipulation](https://arxiv.org/pdf/2101.04882.pdf): Trained a single, goal-conditioned policy that can solve many robotic manipulation tasks, including tasks with previously unseen goals and objects

### NLP:
- [Process for Adapting Language Models to Society (PALMS) with Values-Targeted Datasets](https://cdn.openai.com/palms.pdf): adjusting GPT-3 models with as little as 80 text samples to reduce toxicity, gender, race, and religious imbalances.   
- [Pangu-α: large-scale autoregressive pretrained chinese language models with auto-parallel computation](https://arxiv.org/pdf/2104.12369.pdf):100 billion parameter model trained on 1.1TB  Chinese data 
- [Switch Transformers: Scaling to Trillion Parameter Models with Simple and Efficient Sparsity](https://arxiv.org/abs/2101.03961): Hardrouting information simplifies the MoE routing algorithm and design intuitive improved models with reduced communication and computational costs 
- [DALL-E: Creating Images form Text](https://openai.com/blog/dall-e/): GPT-3 model trained to generate images from text description 
- [CLIP: Connecting Text and Images](https://openai.com/blog/clip/): Great zero-shot performance
- [VideoCLIP: Contrastive Pre-training for Zero-shot Video-Text Understanding](https://arxiv.org/pdf/2109.14084.pdf): Towards multi-modal video understanding

2020
--------
### Graph Embeddings: 


- [A survey on knowledge graphs: Representation, acquisition and applications](https://arxiv.org/abs/2002.00388): Comprehensive review on state-of-the-art knowledge graph embedding models.  
- [An overview of embedding models of entities and relationships for knowledge base completion](https://arxiv.org/abs/1703.08098): Summary of different types of scoring functions

### Reasoning: 
- [A survey on empathetic dialogue systems](https://ww.sentic.net/empathetic-dialogue-systems.pdf): Literature review of empathetic dialogue systems, whose goal is to enhance the perception and expression of emotional states, personal preference, and knowledge. 
- [LITE TRANSFORMER WITH LONG-SHORT RANGE ATTENTIONLITE TRANSFORMER WITH LONG-SHORT RANGE ATTENTION](https://openreview.net/pdf?id=ByeMPlHKPH):  The key primitive is the Long-Short Range Attention (LSRA), where one group of heads specializes in the local context modeling (by convolution) while another group specializes in the long-distance relationship modeling (by attention).



### Deep Learning: 
- [ReadNet: Towards Accurate ReID with Limited and Noisy Samples](https://arxiv.org/abs/2005.05740)
- [Bayesian Deep Learning and a Probabilistic Perspective of Generalization](https://arxiv.org/abs/2002.08791): The key distinguishing property of a bayesian approach is marginalization instead of optimization. Rather than use a single setting of parameters w, use all settings weighted by their posterior probabilities in a bayesian model average 
- [LambdaNetworks: Modeling long-range Interactions without Attention](https://openreview.net/forum?id=xTJEN-ggl1b): Transforming image context into linar layers (Lambdas). LambdaResNets reach state-of-the-art accuracies on ImageNet while being ∼4.5x faster than the popular EfficientNets on modern machine learning accelerators. 
- [Every Model Learned by Gradient Descent Is Approximately a Kernel Machine](https://arxiv.org/abs/2012.00152): This paper challenges this prevailing view and suggest that rather than representing the data, deep neural networks store superpositions of the training data in their weights and act as kernel machines at inference time. 
- [Big Self-Supervised Models are Strong Semi-Supervised Learners](https://arxiv.org/abs/2006.10029): Proposes SimCLRv2 and shows that semi-supervised learning benefits a lot from self-supervised pre-training.
- [An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale](https://arxiv.org/pdf/2010.11929.pdf): A pure transformer applied directly to sequences of image patches can perform very well on image classification task
- [Wifi-based human activity recognition using raspberry pi](https://ieeexplore.ieee.org/document/9288199): A radio frequency-based approach to activity recoginition using Conv/LSTM classifier. Can be used in smart-homes homes. However, just yet not really relyable.    

### Reinforcement Learning: 

- [Ecological Reinforcement Learning](https://arxiv.org/pdf/2006.12478.pdf): Aim to study how the non-episodic RL problem is affected by particular properties of the training environments.

### NLP:
- [Reformer: The efficient Tranformer](https://openreview.net/pdf?id=rkgNKkHtvB): Introduce two techniques to imporve efficiency, such as, locality-sensitive hashing and reversible residual layers. 


2019
--------
### Reinforcement Learning:
[Off-Policy Evaluation via Off-Policy Classification](https://arxiv.org/abs/1906.01624): 
Incorporating Graph Attention Mechanism into Knowledge Graph Reasoning Based on Deep Reinforcement Learning

2018
--------
