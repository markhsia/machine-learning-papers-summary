# Machine Learning Papers Summary

Docsify Book: https://gitycc.github.io/machine-learning-papers-summary  
Github Repo: https://github.com/GitYCC/machine-learning-papers-summary

### Paper Survey

- [terryum/awesome-deep-learning-papers](https://github.com/terryum/awesome-deep-learning-papers)
- [floodsung/Deep-Learning-Papers-Reading-Roadmap](https://github.com/floodsung/Deep-Learning-Papers-Reading-Roadmap)
- [mhagiwara/100-nlp-papers](https://github.com/mhagiwara/100-nlp-papers)
- [thunlp/GNNPapers](https://github.com/thunlp/GNNPapers)

### Content

#### Understanding / Generalization / Transfer

- **Distilling the knowledge in a neural network** \(2015\), G. Hinton et al. \[➤ [s](understanding-generalization-transfer/distilling-the-knowledge-in-a-neural-network.md)[ummary](understanding-generalization-transfer/distilling-the-knowledge-in-a-neural-network.md)\]
- **Deep neural networks are easily fooled: High confidence predictions for unrecognizable images** \(2015\), A. Nguyen et al. \[➤ [summary](understanding-generalization-transfer/deep-neural-networks-are-easily-fooled-high-confidence-predictions-for-unrecognizable-images.md)\]
- **How transferable are features in deep neural networks?** \(2014\), J. Yosinski et al. \[➤ [summary](understanding-generalization-transfer/how-transferable-are-features-in-deep-neural-networks.md)\]



#### Optimization / Training Techniques



#### Unsupervised



#### Generative Models

- **Glow: Generative Flow with Invertible 1×1 Convolutions** (2018), D. P. Kingma et al. \[➤ [summary](generative/glow.md)\]
- **Density Estimation Using Real NVP** (2017), J. Sohl-Dickstein et al. \[➤ [summary](generative/density-estimation-using-real-nvp.md)\]

#### Computer Vision



#### Computer Vision: Segmentation / Object Detection



#### Advertising / Commerce

- **DeepFM: A Factorization-Machine based Neural Network for CTR Prediction** (2017), H. Guo et al. \[➤ [summary](advertising-commerce/deepfm.md)\]



#### Natural Language Processing

- **Attention Is All You Need** (2017), A. Vaswani et al. \[➤ [summary](nlp/attention-is-all-you-need.md)\]
- **A Fast and Accurate Dependency Parser using Neural Networks** (2014), Chen and Manning. \[➤ [summary](nlp/a-fast-and-accurate-dependency-parser-using-nural-networks.md)\]
- **Glove: Global vectors for word representation** (2014), J. Pennington et al. \[➤ [summary](nlp/GloVe.md)\]
- **Distributed representations of words and phrases and their compositionality** (2013), T. Mikolov et al. \[➤ [summary](nlp/distributed-representations-of-words-and-phrases-and-their-compositionality.md)\]
- **Efficient estimation of word representations in vector space** (2013), T. Mikolov et al. \[➤ [summary](nlp/efficient-estimation-of-word-representations-in-vector-space.md)\]



#### Graph Neural Network

- **Graph Neural Networks: A Review of Methods and Applications** (2018), Jie Zhou, Ganqu Cui, Zhengyan Zhang, Cheng Yang, Zhiyuan Liu, Maosong Sun. \[➤ [summary](gnn/graph-neural-networks-a-review-of-methods-and-applications.md)\]
- **Inductive Representation Learning on Large Graphs** (2018), William L. Hamilton et al. \[➤ [summary](gnn/graph-sage.md)\]
- **Semi-supervised Classification with Graph Convolutional Networks** (2017), Thomas N. Kipf et al. \[➤ [summary](gnn/gcn.md)\]
- **DeepWalk: Online Learning of Social Representations** (2014), B. Perozzi et al. \[➤ [summary](gnn/deep-walk.md)\]



#### Speech

- **WaveGlow: A Flow-based Generative Network for Speech Synthesis** (2018), R. Prenger et al. \[➤ [summary](speech/waveglow.md)\]
- **Natural TTS Synthesis by Conditioning WaveNet On Mel Spectrogram Predictions** (2018), J. Shen et al. \[➤ [summary](speech/tacotron2.md)\]
- **Tacotron: Towards End-to-end Speech Synthesis** (2017), Y. Wang et al. \[➤ [summary](speech/tacotron.md)\]
- **WaveNet: A Generative Model For Raw Audio** (2016), van den Oord, et al. \[➤ [summary](speech/wavenet.md)\]



#### Reinforcement Learning / Robotics



### Contributors

-  [@GitYCC](https://github.com/GitYCC) \[website: [www.ycc.idv.tw](https://www.ycc.idv.tw), email: [ycc.tw.email@gmail.com](mailto:%20ycc.tw.email@gmail.com)\]



Welcome to contribute this repo. together.

### Contribution Rules

- Please use pull-request to merge new changes in `feature/xxx` branch into `master` branch
- Add new article
  - In `README.md`, choose or create a category, add new paper item (sorted by years decreasing) and add link `[➤ summary]` to your new article.
  - In `summary.md`, add path of your article into sidebar.
  - Please follow this file structure: (ref: https://docsify.now.sh)
    ```
    README.md
    summary.md
    some-category ---- assets
                   |     |--- some-image-1
                   |     |--- your-image-2
                   |-- your-article.md
    ```
  - In `your-article.md`, add contributor, paper or code at head of the article.

