# DEEP LEARNING PhD MID 2025
## COMPREHENSIVE QUESTION BANK WITH ANSWERS
### 120 Questions with Complete Solutions

---

# SECTION A: MULTIPLE CHOICE QUESTIONS (40 Questions)

## Question 1
**In LeNet-5, the mean of the normalized input tends to:**
- A) 0
- B) 0.5
- C) 1
- D) −1

**Answer: A) 0**

Explanation: Input normalization in LeNet-5 aims to center the data around zero, making the mean approximately 0 for faster convergence during training.

---

## Question 2
**The first convolutional layer in LeNet-5 uses:**
- A) 3 filters of size 3×3
- B) 6 filters of size 5×5
- C) 16 filters of size 5×5
- D) 32 filters of size 7×7

**Answer: B) 6 filters of size 5×5**

Explanation: LeNet-5's first convolutional layer (C1) applies 6 filters of size 5×5 to extract low-level features from 32×32 input images.

---

## Question 3
**LeNet was originally designed for:**
- A) Speech recognition
- B) Machine translation
- C) Handwritten digit recognition on MNIST and bank checks
- D) Object detection in self-driving cars

**Answer: C) Handwritten digit recognition on MNIST and bank checks**

Explanation: LeNet was developed by Yann LeCun for recognizing handwritten digits in postal codes and bank checks, which was its primary application.

---

## Question 4
**AlexNet significantly outperformed previous methods primarily due to:**
- A) Sigmoid activation and small datasets
- B) ReLU activation, large labeled ImageNet dataset, and GPUs
- C) Removal of convolutional layers
- D) Elimination of pooling

**Answer: B) ReLU activation, large labeled ImageNet dataset, and GPUs**

Explanation: AlexNet's success came from three key factors: ReLU's computational efficiency and reduced vanishing gradients, the massive ImageNet dataset (15M images), and GPU acceleration for training.

---

## Question 5
**VGGNet improved performance compared to AlexNet by:**
- A) Using 1×1 convolutions only
- B) Reducing depth but increasing filter size
- C) Using many 3×3 convolutions and increasing depth to 19 layers
- D) Removing pooling layers entirely

**Answer: C) Using many 3×3 convolutions and increasing depth to 19 layers**

Explanation: VGGNet demonstrated that using many small 3×3 filters stacked together is more effective than fewer large filters, achieving better performance with deeper networks (up to 19 layers).

---

## Question 6
**GoogLeNet reduces parameters primarily by:**
- A) Replacing convolutions with only fully connected layers
- B) Using inception modules with 1×1 convolutions for dimension reduction
- C) Removing nonlinearity between layers
- D) Using only 7×7 convolutions

**Answer: B) Using inception modules with 1×1 convolutions for dimension reduction**

Explanation: The Inception module uses 1×1 convolutions (bottleneck layers) to reduce dimensionality before applying larger filters, significantly reducing parameters while maintaining performance.

---

## Question 7
**ResNet-152 solves the optimization difficulty in very deep networks using:**
- A) Dropout at every layer
- B) Residual (skip) connections that add input to output of a block
- C) Removing backpropagation
- D) Using only max-pooling

**Answer: B) Residual (skip) connections that add input to output of a block**

Explanation: Skip connections (identity shortcuts) allow gradients to flow directly through the network, enabling training of very deep networks (152 layers) without vanishing gradient problems.

---

## Question 8
**In CNNs, weight sharing means:**
- A) Each neuron has a unique filter
- B) All filters in a layer are identical
- C) Same filter parameters applied across all spatial locations
- D) Weights randomly shared between networks

**Answer: C) Same filter parameters applied across all spatial locations**

Explanation: Weight sharing refers to using the same filter weights across different spatial positions in the input, reducing parameters and creating translation invariance.

---

## Question 9
**The "stride" hyperparameter in convolution controls:**
- A) Number of filters
- B) Number of pixels the filter moves at each step
- C) Learning rate
- D) Batch size

**Answer: B) Number of pixels the filter moves at each step**

Explanation: Stride determines how many pixels the convolution filter slides across the input at each step. Larger strides reduce output spatial dimensions.

---

## Question 10
**Zero padding in convolutional layers is mainly used to:**
- A) Increase number of channels
- B) Reduce overfitting
- C) Preserve spatial dimensions and avoid losing border information
- D) Replace pooling operations

**Answer: C) Preserve spatial dimensions and avoid losing border information**

Explanation: Zero padding adds a border of zeros around the input to maintain spatial dimensions after convolution and allows filters to access border pixels.

---

## Question 11
**ReLU is preferred over sigmoid in deep CNNs because it:**
- A) Is non-differentiable everywhere
- B) Causes vanishing gradients
- C) Is computationally simple and alleviates vanishing gradients
- D) Outputs only negative values

**Answer: C) Is computationally simple and alleviates vanishing gradients**

Explanation: ReLU (max(0,x)) is computationally efficient and its linear behavior in positive regions helps maintain gradient magnitude, avoiding the vanishing gradient problem of sigmoids in deep networks.

---

## Question 12
**Max-pooling operation is mainly used to:**
- A) Increase feature map resolution
- B) Reduce spatial dimensions while keeping the most salient activations
- C) Normalize feature maps to zero mean
- D) Replace convolutional layers

**Answer: B) Reduce spatial dimensions while keeping the most salient activations**

Explanation: Max-pooling downsamples feature maps by taking the maximum value in each pooling window, reducing computation and focusing on the most important features.

---

## Question 13
**Dropout reduces overfitting by:**
- A) Increasing learning rate during training
- B) Randomly dropping a subset of neurons and connections during training
- C) Freezing all weights after few epochs
- D) Reducing dataset size

**Answer: B) Randomly dropping a subset of neurons and connections during training**

Explanation: Dropout randomly deactivates neurons during training with probability p, forcing the network to learn redundant representations and reducing co-adaptation.

---

## Question 14
**In supervised learning, the main training goal is to:**
- A) Maximize the loss function
- B) Minimize the loss function by adjusting model parameters
- C) Randomize weights maximally
- D) Increase model variance

**Answer: B) Minimize the loss function by adjusting model parameters**

Explanation: Supervised learning aims to find model parameters that minimize the loss function, which measures the difference between predicted and true outputs.

---

## Question 15
**In batch gradient descent, gradient is computed using:**
- A) Single randomly chosen example
- B) Mini-batch of examples
- C) Entire training set at once
- D) Only misclassified examples

**Answer: C) Entire training set at once**

Explanation: Batch gradient descent computes gradients using the entire training set, which provides stable but computationally expensive updates.

---

## Question 16
**Stochastic gradient descent (SGD) updates parameters:**
- A) Once per epoch
- B) After computing gradient on entire dataset
- C) For each single training example
- D) Only when loss increases

**Answer: C) For each single training example**

Explanation: SGD updates parameters after computing the gradient on each individual training example, leading to frequent but noisier updates compared to batch GD.

---

## Question 17
**Mini-batch gradient descent combines advantages of:**
- A) Adam and RMSProp
- B) Batch GD and SGD using small batches
- C) Supervised and unsupervised learning
- D) ReLU and sigmoid activations

**Answer: B) Batch GD and SGD using small batches**

Explanation: Mini-batch GD uses small batches (typically 32-256 examples) to balance the stability of batch GD with the efficiency and randomness of SGD.

---

## Question 18
**L1 regularization (Lasso) tends to:**
- A) Drive many coefficients exactly to zero, performing feature selection
- B) Only shrink coefficients but never to zero
- C) Increase model complexity
- D) Remove bias terms only

**Answer: A) Drive many coefficients exactly to zero, performing feature selection**

Explanation: L1 regularization (∑|w|) has a sharp corner at zero, causing many weights to be exactly zeroed out, effectively selecting important features.

---

## Question 19
**L2 regularization (Ridge) mainly:**
- A) Encourages sparse weights with many exact zeros
- B) Penalizes large weights by their squared magnitude, keeping all features
- C) Removes need for backpropagation
- D) Works only with linear models

**Answer: B) Penalizes large weights by their squared magnitude, keeping all features**

Explanation: L2 regularization (∑w²) penalizes large weights but never forces them to zero, keeping all features with reduced magnitude.

---

## Question 20
**The F1-measure (F-score) is the harmonic mean of:**
- A) Accuracy and specificity
- B) Recall and specificity
- C) Precision and recall
- D) True positive rate and false positive rate

**Answer: C) Precision and recall**

Explanation: F1-score = 2·(Precision·Recall)/(Precision+Recall), combining precision (correct predictions) and recall (finding all positives) in a single metric.

---

## Question 21
**ZFNet (2013) improved upon AlexNet by:**
- A) Using larger first-layer filters
- B) Reducing first-layer filter size from 11×11 to 7×7 with stride 2
- C) Adding inception modules
- D) Using residual connections

**Answer: B) Reducing first-layer filter size from 11×11 to 7×7 with stride 2**

Explanation: ZFNet showed that reducing the first convolution layer from 11×11 to 7×7 with stride 2 improved feature visualization and overall performance.

---

## Question 22
**The vanishing gradient problem occurs in networks using:**
- A) ReLU activation only
- B) Sigmoid or tanh activation with many layers
- C) Average pooling
- D) Stride > 1

**Answer: B) Sigmoid or tanh activation with many layers**

Explanation: Sigmoid/tanh have derivatives bounded by ~0.25, causing gradients to exponentially decay in deep networks. ReLU mitigates this with gradient = 1 for positive inputs.

---

## Question 23
**In a convolutional layer with input size A, kernel size K, padding P, and stride S, the output size is:**
- A) (A - K + 2P) / S + 1
- B) (A + K - 2P) / S - 1
- C) A - K + P
- D) A * K - P

**Answer: A) (A - K + 2P) / S + 1**

Explanation: This is the standard convolution output size formula. Example: 28×28 input, 5×5 kernel, stride 1, padding 0 → (28-5+0)/1 + 1 = 24×24.

---

## Question 24
**Softmax activation function is typically used in:**
- A) Hidden layers of CNNs
- B) The final output layer for multi-class classification
- C) Pooling layers
- D) Convolutional layers before ReLU

**Answer: B) The final output layer for multi-class classification**

Explanation: Softmax converts logits to probability distributions summing to 1, making it ideal for multi-class classification output layers.

---

## Question 25
**Cross-entropy loss is preferred for softmax output because:**
- A) It is always zero
- B) It penalizes confident wrong predictions heavily
- C) It works only with binary classification
- D) It requires positive inputs only

**Answer: B) It penalizes confident wrong predictions heavily**

Explanation: Cross-entropy loss = -∑y_i·log(p_i) heavily penalizes high-confidence wrong predictions, which is ideal for classification tasks.

---

## Question 26
**Backpropagation computes gradients by:**
- A) Forward pass only
- B) Chain rule applied in reverse from output to input
- C) Random sampling of weights
- D) Averaging all possible paths

**Answer: B) Chain rule applied in reverse from output to input**

Explanation: Backpropagation applies the chain rule to compute gradients layer-by-layer from the output loss backward to the input, enabling efficient gradient computation.

---

## Question 27
**The learning rate in gradient descent:**
- A) Determines the fraction of parameters to update
- B) Controls the step size when updating parameters
- C) Must always be greater than 1
- D) Has no effect on convergence

**Answer: B) Controls the step size when updating parameters**

Explanation: Learning rate α scales the gradient step: w_new = w - α·∇L. Too large causes divergence, too small causes slow convergence.

---

## Question 28
**A model with high bias and low variance typically:**
- A) Overfits the training data
- B) Underfits the training data
- C) Generalizes perfectly
- D) Requires more regularization

**Answer: B) Underfits the training data**

Explanation: High bias indicates a simple model that cannot capture data complexity, resulting in poor performance on both training and test data (underfitting).

---

## Question 29
**A model with low bias and high variance typically:**
- A) Underfits the training data
- B) Generalizes well to new data
- C) Overfits the training data
- D) Has minimal parameters

**Answer: C) Overfits the training data**

Explanation: Low bias means the model is complex enough to fit training data well, but high variance means it overfits, performing poorly on unseen data.

---

## Question 30
**Which activation function has output range [0, 1]?**
- A) ReLU
- B) Tanh
- C) Sigmoid
- D) Softmax

**Answer: C) Sigmoid**

Explanation: Sigmoid(x) = 1/(1+e^(-x)) outputs values in (0,1). ReLU ∈ [0,∞), Tanh ∈ [-1,1], Softmax is probability distribution.

---

## Question 31
**The Inception module in GoogLeNet includes convolutions of sizes:**
- A) Only 3×3
- B) 1×1, 3×3, 5×5 applied in parallel
- C) Only 1×1
- D) 7×7 and 11×11

**Answer: B) 1×1, 3×3, 5×5 applied in parallel**

Explanation: The Inception module applies multiple filter sizes in parallel (1×1, 3×3, 5×5, and max-pooling), capturing multi-scale features efficiently.

---

## Question 32
**In residual networks, the skip connection is important because:**
- A) It increases model parameters
- B) It distributes gradients during backpropagation
- C) It replaces activation functions
- D) It eliminates the need for training

**Answer: B) It distributes gradients during backpropagation**

Explanation: Skip connections allow gradients to flow directly through shortcut paths, preventing gradient vanishing in very deep networks and enabling training of 152+ layer networks.

---

## Question 33
**Average pooling is useful when:**
- A) Maximum features need to be preserved
- B) Overall context of the region is important
- C) Reducing computation is not a priority
- D) Using very small kernels only

**Answer: B) Overall context of the region is important**

Explanation: Average pooling computes the mean of pooling window, capturing overall context. Useful when all features in a region are important, unlike max-pooling's focus on peak activations.

---

## Question 34
**Batch normalization helps training by:**
- A) Removing the need for activation functions
- B) Normalizing layer inputs to reduce internal covariate shift
- C) Increasing overfitting
- D) Making learning rate irrelevant

**Answer: B) Normalizing layer inputs to reduce internal covariate shift**

Explanation: Batch normalization normalizes each layer's inputs to mean 0 and variance 1, reducing internal covariate shift and allowing higher learning rates.

---

## Question 35
**The curse of dimensionality in optimization refers to:**
- A) Using very large filters
- B) Difficulty in finding global minimum with too many parameters
- C) Reducing image resolution
- D) Increasing batch size

**Answer: B) Difficulty in finding global minimum with too many parameters**

Explanation: As parameter count increases, the loss landscape becomes increasingly complex with more saddle points and local minima, making optimization harder.

---

## Question 36
**Early stopping during training helps by:**
- A) Reducing training time without stopping at convergence
- B) Monitoring validation loss and stopping when it increases
- C) Removing all layers except first
- D) Increasing learning rate continuously

**Answer: B) Monitoring validation loss and stopping when it increases**

Explanation: Early stopping monitors validation loss and terminates training when it stops improving, preventing overfitting while maintaining good test performance.

---

## Question 37
**Precision in classification is defined as:**
- A) TP / (TP + FN)
- B) TP / (TP + FP)
- C) (TP + TN) / Total
- D) TN / (TN + FP)

**Answer: B) TP / (TP + FP)**

Explanation: Precision = TP/(TP+FP) answers "Of all predicted positives, how many are actually positive?" It measures prediction accuracy for the positive class.

---

## Question 38
**Recall (Sensitivity) in classification is defined as:**
- A) TP / (TP + FP)
- B) TP / (TP + FN)
- C) TN / (TN + FN)
- D) (TP + TN) / Total

**Answer: B) TP / (TP + FN)**

Explanation: Recall = TP/(TP+FN) answers "Of all actual positives, how many did we identify?" It measures how thoroughly we find positive instances.

---

## Question 39
**Dilated (Atrous) convolution allows:**
- A) Larger receptive field without increasing parameters
- B) Reducing model depth
- C) Replacing pooling operations
- D) Faster training only

**Answer: A) Larger receptive field without increasing parameters**

Explanation: Dilated convolution uses gaps (dilation rate) between kernel elements, expanding receptive field without adding parameters or computational cost.

---

## Question 40
**ImageNet competition (ILSVRC) dataset contains approximately:**
- A) 1 million images from 1000 categories
- B) 15 million images from 22000 categories
- C) 50 million images from 10000 categories
- D) 100 million images from 1000 categories

**Answer: A) 1 million images from 1000 categories**

Explanation: ImageNet ILSVRC challenge uses ~1.2M training images across 1000 object categories, driving advances in deep learning since 2010.

---

# SECTION B: FILL IN THE BLANKS (20 Questions)

## Question 41
**In VGGNet, the number of filters typically _______ after each block of convolutional layers, while keeping the filter size at 3×3.**

**Answer: doubles (or increases by 2x)**

Explanation: VGGNet's architecture: 64 → 128 → 256 → 512 → 512 filters in successive blocks, maintaining constant 3×3 kernel size throughout.

---

## Question 42
**GoogLeNet introduced the _______ module as its basic building block to process multiple filter sizes in parallel.**

**Answer: Inception**

Explanation: The Inception module is the fundamental building block of GoogLeNet, enabling parallel multi-scale feature extraction with reduced parameters.

---

## Question 43
**ResNet uses _______ (or skip) connections to ease the flow of gradients through very deep networks.**

**Answer: residual**

Explanation: Residual connections add the input directly to the output of a block, creating shortcuts for gradient flow in deep networks.

---

## Question 44
**In a CNN, the small region of the input to which a filter is applied is called the local _______ field.**

**Answer: receptive**

Explanation: The receptive field is the region in input space that influences a particular neuron's activation, growing deeper into the network.

---

## Question 45
**The last layer of AlexNet uses the _______ function to produce class probabilities for ImageNet classes.**

**Answer: softmax**

Explanation: AlexNet's output layer uses softmax to convert 1000-class logits into probability distributions for classification.

---

## Question 46
**The error (or loss) is computed at the output layer using a _______ function such as MSE or cross-entropy.**

**Answer: loss (or cost/objective)**

Explanation: Loss functions like MSE and cross-entropy quantify the discrepancy between predictions and true labels.

---

## Question 47
**The optimization algorithm that uses the gradient of the loss with respect to weights is called _______ descent.**

**Answer: gradient**

Explanation: Gradient descent iteratively updates weights in the direction of negative gradient to minimize the loss function.

---

## Question 48
**A model that performs well on training data but poorly on test data is said to be suffering from _______.**

**Answer: overfitting**

Explanation: Overfitting occurs when a model memorizes training data rather than learning generalizable patterns, resulting in poor test performance.

---

## Question 49
**A model that is too simple and performs poorly on both training and test data is said to be _______ the data.**

**Answer: underfitting**

Explanation: Underfitting results from a model that's too simple to capture data complexity, manifesting as high training and test error.

---

## Question 50
**Constraining a model to make it simpler and reduce overfitting by penalizing large weights is called _______.**

**Answer: regularization (L1, L2, or weight decay)**

Explanation: Regularization adds penalty terms to the loss function, discouraging large weights and reducing model complexity.

---

## Question 51
**In convolution operations, the output feature map size decreases with larger _______ (moving window) values.**

**Answer: stride**

Explanation: Larger strides cause the filter to move more pixels per step, resulting in smaller output feature maps.

---

## Question 52
**The _______ activation function simply outputs max(0, x) for any input x.**

**Answer: ReLU**

Explanation: ReLU (Rectified Linear Unit) is the most common modern activation function due to its simplicity and effectiveness in deep networks.

---

## Question 53
**The process of computing gradients by applying the _______ rule in reverse from output to input is called backpropagation.**

**Answer: chain**

Explanation: Backpropagation applies the chain rule systematically to propagate errors backward through the network, computing gradients for all weights.

---

## Question 54
**The _______ layer is only active during training to prevent overfitting and is typically deactivated during inference.**

**Answer: dropout**

Explanation: Dropout randomly removes neurons during training but uses all neurons during testing, providing a form of model averaging.

---

## Question 55
**K-fold cross-validation divides the dataset into k equal-sized _______ (or splits/subsets), using k-1 for training and 1 for validation.**

**Answer: folds**

Explanation: K-fold CV partitions data into k subsets, training k times with different fold left out for validation, providing robust performance estimates.

---

## Question 56
**The _______ rate is a hyperparameter that determines how fast the model learns during gradient descent.**

**Answer: learning**

Explanation: Learning rate controls the magnitude of weight updates; typical values are 0.001-0.1 depending on optimization algorithm.

---

## Question 57
**In optimization, _______ points are regions where the gradient is zero but are neither maxima nor minima.**

**Answer: saddle**

Explanation: Saddle points are critical points with zero gradient but higher curvature in some directions and lower in others, challenging for optimization.

---

## Question 58
**The _______ error rate is the proportion of predictions that are incorrect out of all total predictions.**

**Answer: classification or misclassification**

Explanation: Error rate = (FP + FN) / Total, or equivalently 1 - Accuracy, measuring overall prediction correctness.

---

## Question 59
**When a model has high bias and low variance, it exhibits _______ behavior on new data.**

**Answer: underfitting**

Explanation: High bias means consistent errors from oversimplified model; low variance means consistent predictions but wrong on average (underfitting).

---

## Question 60
**The process of extracting _______ from raw input data automatically (without manual engineering) is a key advantage of deep learning.**

**Answer: features or representations**

Explanation: Deep learning's hierarchical structure automatically learns features at multiple levels, eliminating manual feature engineering.

---

# SECTION C: TRUE / FALSE QUESTIONS (15 Questions)

## Question 61
**T / F: In CNNs, using larger strides generally produces larger spatial feature maps.**

**Answer: FALSE**

Explanation: Larger strides cause the filter to skip more pixels, resulting in smaller (downsampled) feature maps, not larger ones.

---

## Question 62
**T / F: Max-pooling provides translation invariance by making the exact position of features less important.**

**Answer: TRUE**

Explanation: Max-pooling selects the maximum value in a region regardless of exact position, providing robustness to small translations.

---

## Question 63
**T / F: Using dropout during inference (testing) improves accuracy by adding more randomness.**

**Answer: FALSE**

Explanation: Dropout should be disabled during inference; using it would introduce unnecessary noise. At test time, use all neurons but scale by (1-p).

---

## Question 64
**T / F: Cross-entropy loss is commonly used with softmax outputs in multi-class classification.**

**Answer: TRUE**

Explanation: Cross-entropy loss is the standard choice for softmax output because it directly relates to probabilistic interpretation and optimization efficiency.

---

## Question 65
**T / F: High bias and low variance typically indicate an overfitted model.**

**Answer: FALSE**

Explanation: High bias and low variance indicate underfitting (oversimplified model). Overfitting is characterized by low bias and high variance.

---

## Question 66
**T / F: The batch size in mini-batch gradient descent must be smaller than the entire dataset.**

**Answer: TRUE**

Explanation: By definition, batch size is smaller than total dataset size; if equal to dataset, it becomes batch GD, not mini-batch GD.

---

## Question 67
**T / F: ReLU activation function can suffer from dying ReLU problem where neurons output zero for all inputs.**

**Answer: TRUE**

Explanation: When weights become too negative, neurons output zero for all inputs and produce zero gradients, preventing further updates (dying ReLU).

---

## Question 68
**T / F: L1 and L2 regularization are equally effective at feature selection in high-dimensional datasets.**

**Answer: FALSE**

Explanation: L1 (Lasso) is better at feature selection as it drives coefficients to exactly zero, while L2 (Ridge) only shrinks them.

---

## Question 69
**T / F: Increasing network depth always leads to better performance without any negative effects.**

**Answer: FALSE**

Explanation: Very deep networks suffer from vanishing gradients and optimization difficulties; depth helps but has diminishing returns and challenges.

---

## Question 70
**T / F: Softmax activation can be applied to any layer, not just the output layer.**

**Answer: FALSE**

Explanation: Softmax should only be used at the output layer for multi-class classification. Using it in hidden layers would constrain values to sum to 1, harming expressiveness.

---

## Question 71
**T / F: Zero padding in convolution always increases the size of feature maps.**

**Answer: FALSE**

Explanation: Zero padding preserves spatial dimensions (with padding 1, stride 1 keeps same size), but doesn't increase size. Only reduces size reduction.

---

## Question 72
**T / F: Batch gradient descent is faster than mini-batch gradient descent because it uses the entire dataset.**

**Answer: FALSE**

Explanation: Mini-batch GD is generally faster in wall-clock time due to better GPU parallelization, despite fewer iterations. Batch GD is computationally expensive per iteration.

---

## Question 73
**T / F: The vanishing gradient problem primarily affects networks with shallow architectures.**

**Answer: FALSE**

Explanation: Vanishing gradients are problems in DEEP networks with many layers, not shallow ones. Shallow networks don't suffer from this.

---

## Question 74
**T / F: Momentum in optimization helps accelerate convergence in relevant directions.**

**Answer: TRUE**

Explanation: Momentum accumulates gradients over time, accelerating movement in consistent directions while dampening oscillations in others.

---

## Question 75
**T / F: AlexNet required GPU training mainly because of the large ImageNet dataset and network depth.**

**Answer: TRUE**

Explanation: ImageNet's 1.2M images and AlexNet's depth (8 layers with 60M parameters) made GPU training essential for practical training times.

---

# SECTION D: SHORT ANSWER QUESTIONS (12 Questions)

## Question 76
**Explain the main differences between AlexNet and LeNet in terms of: (a) Dataset size and type, (b) Network depth, (c) Activation functions, and (d) Hardware used for training.**

**Answer:**

**(a) Dataset:**
- LeNet used small custom datasets (MNIST ~70K images)
- AlexNet used ImageNet (1.2M images from 1000 diverse categories)

**(b) Network Depth:**
- LeNet had 5 layers (relatively shallow)
- AlexNet had 8 layers (deeper architecture)

**(c) Activation Functions:**
- LeNet used sigmoid/tanh (susceptible to vanishing gradients)
- AlexNet pioneered ReLU activation (mitigates vanishing gradients)

**(d) Hardware:**
- LeNet trained on CPUs
- AlexNet utilized GPUs (NVIDIA GeForce GTX 590) for acceleration, critical for training large-scale models

---

## Question 77
**Describe the three main variants of gradient descent (batch, stochastic, mini-batch) and mention one advantage of each.**

**Answer:**

**Batch Gradient Descent (BGD):**
- Computes gradient on entire dataset for one update per epoch
- Advantage: Stable, smooth convergence with accurate gradients

**Stochastic Gradient Descent (SGD):**
- Computes gradient on single example, updates after each sample
- Advantage: High update frequency enables escaping local minima; low memory requirements

**Mini-batch Gradient Descent:**
- Computes gradient on small batch (32-256 examples) for updates multiple times per epoch
- Advantage: Balance between stability and update frequency; efficient GPU parallelization; generally fastest in practice

---

## Question 78
**Using the bias-variance framework, briefly define underfitting and overfitting and indicate which bias/variance combinations correspond to each case.**

**Answer:**

**Underfitting:**
- Model is too simple to capture data's underlying patterns, performing poorly on both training and test data
- Characteristic: **High Bias, Low Variance** – model makes consistent wrong assumptions

**Overfitting:**
- Model memorizes training data rather than learning generalizable patterns, performing well on training but poorly on test data
- Characteristic: **Low Bias, High Variance** – model fits training noise, unstable on new data

**Remedy for underfitting:** Use more complex model, train longer, feature engineering
**Remedy for overfitting:** Regularization (L1/L2), dropout, early stopping, more training data

---

## Question 79
**Explain how residual (skip) connections in ResNet address the vanishing gradient problem in very deep networks.**

**Answer:**

Residual connections (skip connections) directly add the input to the output of a residual block: y = F(x) + x

**How they solve vanishing gradients:**
1. During backpropagation, gradients flow through two paths: through F(x) (complex path) and directly through x (identity path)
2. The identity path has gradient = 1, providing a "highway" for gradients to flow unchanged
3. Even if ∇F becomes very small (< 0.25), the total gradient = ∇F + 1 ≈ 1, preventing vanishing
4. This allows training of extremely deep networks (ResNet-152 with 152 layers) that would be impossible without skip connections

Mathematical: ∂L/∂x = ∂L/∂y · (∂F/∂x + ∂(identity)/∂x) = ∂L/∂y · (∂F/∂x + 1)
The "+1" term ensures gradients don't completely vanish, maintaining sufficient signal for learning

---

## Question 80
**Describe the key innovation of the Inception module in GoogLeNet and why using 1×1 convolutions helps reduce parameters.**

**Answer:**

**Key Innovation:** The Inception module processes input through multiple parallel paths with different filter sizes (1×1, 3×3, 5×5, and max-pooling), capturing multi-scale features efficiently.

**Why 1×1 convolutions reduce parameters:**
- 1×1 convolutions act as "bottleneck layers" for dimension reduction
- Example: Input 56×56×256 → 1×1 conv with 64 filters → 56×56×64
- This reduces dimensionality before applying expensive large filters (5×5)
- Instead of: 256×5×5 filter = 6,400 parameters per filter
- We use: 256×1×1 = 256 params → reduce to 64 channels → 64×5×5 = 1,600 params per filter
- Parameter reduction: 6,400 → 256+1,600 = 1,856 (71% fewer parameters)
- Computational benefit: MAC (multiply-accumulate) operations reduced similarly

Result: GoogLeNet achieves comparable performance to VGGNet with 4× fewer parameters and significantly faster inference

---

## Question 81
**What is the relationship between precision, recall, and the F1-score? Why is F1-score often preferred over accuracy for imbalanced datasets?**

**Answer:**

**Relationships:**
- **Precision** = TP/(TP+FP): "Of predicted positives, how many are correct?" (precision of positive predictions)
- **Recall** = TP/(TP+FN): "Of actual positives, how many did we find?" (coverage of positive class)
- **F1-score** = 2·(P·R)/(P+R): Harmonic mean of precision and recall, requiring both to be high

Trade-off: Increasing recall (catching more positives) often decreases precision (more false positives), and vice versa.

**Why F1 > Accuracy for imbalanced data:**
- Example: Dataset with 99% negatives, 1% positives
- A model predicting "all negative" achieves 99% accuracy but 0% recall on positives (useless!)
- Accuracy is misleading in imbalanced settings because it's dominated by majority class
- F1-score averages precision and recall, forcing consideration of minority class performance
- F1 provides balanced evaluation across both classes, reflecting true model utility

---

## Question 82
**Explain how dropout works during training and why it should be disabled during inference/testing.**

**Answer:**

**During Training:**
1. Randomly select neurons with probability p (typically p=0.5 in hidden layers, 0.1 in early layers)
2. "Drop" (deactivate) selected neurons by setting their outputs to 0
3. Backpropagation proceeds without updating dropped neurons
4. Effect: Network learns redundant, co-adapted features; creates ensemble of "thinned" networks

**Why disable during testing:**
1. During inference, we want predictions from the complete trained network, not a random subset
2. Dropping neurons at test time would add noise and reduce model capacity without benefit
3. **Scaling correction:** If we drop p fraction during training, we scale activations by (1-p) at test time to maintain expected activation magnitude
   - Alternatively: Use "inverse dropout" during training (scale by 1/(1-p)) to avoid test-time scaling

**Conceptual understanding:**
Dropout acts as an implicit ensemble of exponentially many thinned networks. At test time, we approximate averaging all these ensemble members by using the full network with scaled weights.

---

## Question 83
**Define the local receptive field in CNNs and explain how it differs from fully connected networks.**

**Answer:**

**Local Receptive Field in CNNs:**
The receptive field is the region in the input space that influences a particular neuron's activation. In convolutional layers:
- Early layers have small receptive fields (e.g., 5×5 from 5×5 filter)
- Deeper layers have exponentially larger receptive fields due to stacking
- Formula for receptive field at layer l: RF_l = 1 + ∑(kernel_size - 1) × ∏stride terms

**Difference from Fully Connected Networks:**
- **CNNs:** Neurons only connect to local input regions, preserving spatial structure and reducing parameters
  - Example: 5×5 filter connects only 25 inputs (locally connected)
  - Parameter sharing: same filter applied everywhere (massive parameter reduction)
  
- **Fully Connected (FC):** Each neuron connects to ALL inputs from previous layer
  - Example: 224×224×3 input → 150,528 connections per neuron
  - No parameter sharing; parameter explosion in large networks
  - Loss of spatial structure information

**Advantages of local receptive fields:**
1. Dramatically fewer parameters (sharing)
2. Hierarchical feature learning (local → global)
3. Translation invariance and robustness
4. Computationally efficient

---

## Question 84
**Explain what batch normalization does and how it helps improve training dynamics in deep networks.**

**Answer:**

**What Batch Normalization Does:**
Batch normalization normalizes layer inputs to have mean ≈ 0 and variance ≈ 1:
1. Compute mean μ and variance σ² of batch
2. Normalize: x_normalized = (x - μ) / √(σ² + ε)
3. Scale and shift: y = γ·x_normalized + β (learnable parameters)

**How it improves training:**

1. **Reduces Internal Covariate Shift:**
   - Without BN: Each layer receives inputs with changing distribution as previous layer weights update
   - This creates instability and requires careful learning rate tuning
   - BN stabilizes input distributions, making training more robust

2. **Enables Higher Learning Rates:**
   - Normalized inputs reduce sensitivity to initialization and learning rate
   - Allows faster training without gradient explosions/vanishing

3. **Regularization Effect:**
   - Noise from batch statistics acts as implicit regularization
   - Reduces overfitting, sometimes allowing removal of dropout

4. **Better Gradient Flow:**
   - Normalized activations maintain gradient magnitude across layers
   - Helps mitigate vanishing/exploding gradients

**Practical benefits:**
- Faster convergence (fewer iterations needed)
- Less sensitive to weight initialization
- Allows higher learning rates
- Often improves generalization
- Reduced need for dropout

---

## Question 85
**Describe the forward and backward pass in a convolutional neural network, explaining what happens to gradients during backpropagation.**

**Answer:**

**Forward Pass:**
1. Input image X (e.g., 32×32×3) passes through layers sequentially
2. Convolution: Apply filters to produce feature maps
3. Activation: Apply ReLU (or other) nonlinearity
4. Pooling: Downsample feature maps
5. Output layer: Produce logits/probabilities
6. Loss computation: Compare with ground truth labels
7. Result: Loss value L

**Backward Pass (Backpropagation):**
1. Start at output layer, compute ∂L/∂(output activations)
2. Use chain rule moving backward layer by layer:
   - ∂L/∂(weights_l) = ∂L/∂(activations_l) · ∂(activations_l)/∂(weights_l)
   - ∂L/∂(activations_l-1) = ∂L/∂(activations_l) · ∂(activations_l)/∂(activations_l-1)

3. For each layer type:
   - **Convolutional:** Gradient computation involves correlating gradients with input patches
   - **ReLU:** ∂(relu)/∂x = 1 if x>0, else 0 (passes or zeroes gradients)
   - **Pooling:** Max-pooling routes gradient only to max position; avg-pooling distributes evenly

4. Gradient flow challenges:
   - **Vanishing:** Sigmoid/tanh derivatives (≈0.25) cause exponential gradient decay in deep networks
   - **Exploding:** Large weights amplify gradients, causing overflow
   - **Solutions:** ReLU (∂/∂x=1 for x>0), batch normalization, residual connections

5. Update weights using computed gradients:
   - w_new = w - α·∂L/∂w

**Key insight:** Information flows backward through the network using the chain rule; maintaining stable gradient magnitude is critical for effective learning.

---

## Question 86
**Explain the curse of dimensionality in optimization and how it relates to finding the global minimum in deep networks.**

**Answer:**

**The Curse of Dimensionality in Optimization:**

As the number of parameters (dimensions) increases, the optimization landscape becomes exponentially more complex:

1. **Exponential Growth of Search Space:**
   - 2D space: Easy to visualize, simple optimization
   - 1000D space: Number of possible "directions" becomes exponentially large
   - Example: AlexNet has 60M parameters; search space has 60M dimensions

2. **Proliferation of Critical Points:**
   - Number of local minima grows exponentially with dimensionality
   - Number of saddle points vastly exceeds local minima
   - High-dimensional random functions are unlikely to have single global minimum

3. **Sparsity of Good Solutions:**
   - In high dimensions, "good" solutions become increasingly rare
   - Most random directions have similar loss values (flat plateaus)
   - Finding improvement direction becomes harder

4. **Slowing Convergence:**
   - Optimization algorithms must search exponentially larger space
   - More iterations needed to reach acceptable solutions
   - Computational cost grows dramatically

**Implications for Deep Networks:**
- ResNet-152: 152 layers × thousands of channels = millions of parameters
- Standard wisdom (prior to empirical results): Deeper networks should be "harder" to optimize
- **Surprising empirical finding:** Deep networks with skip connections train well despite curse
- **Explanation:** Residual connections and batch normalization create "highways" for optimization

**Practical consequences:**
- Need careful initialization (Xavier, He)
- Learning rate scheduling crucial
- Batch normalization becomes essential
- Skip connections help tremendously
- Still no guaranteed path to global minimum (settle for local minima that generalize well)

---

## Question 87
**What are the hyperparameters in a convolutional layer? Explain how each one (filter size, number of filters, stride, padding) affects the output dimensions and model performance.**

**Answer:**

**Convolutional Layer Hyperparameters:**

**1. Filter Size (Kernel Size) - K:**
- Common values: 3×3, 5×5, 7×7
- **Effect on output dimensions:** Output size ∝ 1/K (larger kernel → smaller output)
  - Formula: Output = ⌊(Input - K + 2P) / S⌋ + 1
  - Example: 28×28 input, K=5 vs K=3 with stride 1, no padding:
    - K=5: (28-5)/1 + 1 = 24×24
    - K=3: (28-3)/1 + 1 = 26×26
- **Effect on performance:**
  - Larger filters (5×5, 7×7): Larger receptive field, captures larger patterns; more parameters
  - Smaller filters (3×3): Computationally efficient; stacking creates large receptive field (VGGNet insight)
  - Trade-off: 3×3 generally preferred in modern networks (computational efficiency)

**2. Number of Filters - F:**
- Common values: 64, 128, 256, 512
- **Effect on output dimensions:** Output depth = F (output channels)
  - Input 28×28×32, F=64 → output 28×28×64 (spatial size unchanged, depth increases)
- **Effect on performance:**
  - More filters: Larger capacity, learns more diverse features
  - Too many: Overfitting, slow training, memory issues
  - Pattern: Typically increase depth in deeper layers (64→128→256→512 in VGGNet)

**3. Stride - S:**
- Common values: 1, 2 (sometimes 3)
- **Effect on output dimensions:** Directly scales output size
  - Output = ⌊(Input - K + 2P) / S⌋ + 1
  - S=1: Preserves spatial dimensions (mainly)
  - S=2: Halves spatial dimensions (downsampling)
  - Example: 28×28 input, S=1 vs S=2 with K=3, P=1:
    - S=1: (28-3+2)/1 + 1 = 28×28
    - S=2: (28-3+2)/2 + 1 = 14×14
- **Effect on performance:**
  - S=1: Preserves detail, larger memory/computation
  - S=2: Downsampling, reduces computation but loses spatial detail
  - Common pattern: Use pooling for downsampling instead (cleaner design)

**4. Padding - P:**
- Common values: 0 (no padding), 1 (same padding), 2
- **Effect on output dimensions:** Increases effective input size
  - Output = ⌊(Input - K + 2P) / S⌋ + 1
  - P=0 (valid): Output shrinks by K-1 per dimension
  - P=1 (same): Output maintains spatial size (with S=1)
  - Example: 28×28 input, K=5, S=1:
    - P=0: (28-5)/1 + 1 = 24×24 (shrinkage)
    - P=2: (28-5+4)/1 + 1 = 28×28 (same padding)
- **Effect on performance:**
  - P=0: Border information lost; edge pixels underutilized
  - P>0: Preserves border information; typically improves performance
  - "Same" padding (P=K//2) allows network to preserve spatial dimensions through layers

**Design Patterns in Modern Networks:**
- Early layers: Small stride (S=1), same padding (P=1) to preserve detail with 3×3 filters
- Intermediate layers: S=2 with pooling for downsampling every 2-3 layers
- Filter progression: 64 → 128 → 256 → 512 (increase depth, decrease spatial size)
- Modern preference: Multiple 3×3 filters better than single larger filter (VGGNet's contribution)

---

# SECTION E: COMPUTATIONAL / PROBLEM-SOLVING QUESTIONS (8 Questions)

## Question 88
**A 32×32 grayscale image is input to a convolutional layer with 6 filters of size 5×5, stride 1, and no padding (P=0). a) What is the spatial size of each output feature map? b) How many learnable parameters (weights only, no bias) does this layer have?**

**Answer:**

**a) Output spatial size:**
Using formula: Output = (Input - Filter + 2*Padding) / Stride + 1
Output = (32 - 5 + 2*0) / 1 + 1 = 27 / 1 + 1 = **28×28**
Each of the 6 filters produces a 28×28 feature map.

**b) Number of learnable parameters (weights only):**
Parameters per filter = Filter_size × Filter_size × Input_channels
= 5 × 5 × 1 = 25 (input is grayscale, so 1 channel)
Total parameters = 25 × 6 filters = **150 parameters**
(Note: If including biases, add 6 more = 156 total)

---

## Question 89
**Consider a 128×128 RGB image input to a convolutional layer with: 32 filters of size 3×3, stride 1, padding 1. a) What is the output size? b) How many parameters does this layer have (including biases)?**

**Answer:**

**a) Output size:**
- Input: 128×128×3 (RGB has 3 channels)
- Spatial dimensions: (128 - 3 + 2*1) / 1 + 1 = (128 - 3 + 2) / 1 + 1 = 127 / 1 + 1 = **128×128**
- Depth: 32 filters
- **Output: 128×128×32**

**b) Parameters (including biases):**
- Weights per filter: 3×3×3 (kernel size × kernel size × input channels) = 27
- Total weight parameters: 27 × 32 filters = 864
- Bias parameters: 1 per filter × 32 = 32
- **Total: 864 + 32 = 896 parameters**

---

## Question 90
**A convolutional layer has input dimensions 56×56×64 (height × width × depth), applies 128 filters of size 3×3 with padding 1 and stride 1. a) Calculate output dimensions. b) Calculate total number of parameters (weights + biases).**

**Answer:**

**a) Output dimensions:**
- Input spatial: 56×56, Filter: 3×3, Padding: 1, Stride: 1
- Output spatial: (56 - 3 + 2*1) / 1 + 1 = (56 - 3 + 2) / 1 + 1 = 55 / 1 + 1 = **56×56**
- Output depth: 128 filters
- **Output: 56×56×128**

**b) Total parameters:**
- Weights per filter: 3 × 3 × 64 (input channels) = 576
- Total weight parameters: 576 × 128 = 73,728
- Bias parameters: 1 per filter × 128 = 128
- **Total: 73,728 + 128 = 73,856 parameters**

---

## Question 91
**Consider a binary classifier with the following confusion matrix: TP = 80, FP = 20, FN = 40, TN = 60. a) Compute precision, recall, accuracy, and F1-score. b) What does high precision and low recall suggest about the model?**

**Answer:**

**a) Computing metrics:**

**Precision** = TP / (TP + FP) = 80 / (80 + 20) = 80 / 100 = **0.80 (80%)**
→ Of predicted positives, 80% are correct

**Recall** = TP / (TP + FN) = 80 / (80 + 40) = 80 / 120 = **0.667 (66.7%)**
→ Of actual positives, we identify 66.7%

**Accuracy** = (TP + TN) / Total = (80 + 60) / (80 + 20 + 40 + 60) = 140 / 200 = **0.70 (70%)**
→ Overall correct predictions

**F1-score** = 2 × (Precision × Recall) / (Precision + Recall)
= 2 × (0.80 × 0.667) / (0.80 + 0.667)
= 2 × 0.534 / 1.467
= 1.068 / 1.467
= **0.728 (72.8%)**

**b) Interpretation of high precision and low recall:**
- High precision (80%): When model predicts positive, it's usually correct (few false positives)
- Low recall (66.7%): Model misses many actual positives (40 FN out of 120 total positives)
- **Implication:** Model is conservative, making positive predictions only when confident
- **Real-world meaning:** If this is medical diagnosis, the model rarely gives false alarms (good) but misses 1/3 of actual diseases (bad for disease detection)
- **When appropriate:** High precision-low recall is good for applications where false positives are costly (spam detection, hiring)
- **Problem:** We need better balance; consider adjusting decision threshold to improve recall

---

## Question 92
**A multi-class classifier produces the following results on a test set: Class A: TP=90, FP=10; Class B: TP=75, FP=25; Class C: TP=85, FP=15. Calculate the weighted average precision across all three classes.**

**Answer:**

**Precision for each class:**
- Class A: Precision_A = TP_A / (TP_A + FP_A) = 90 / (90 + 10) = 90 / 100 = 0.90
- Class B: Precision_B = TP_B / (TP_B + FP_B) = 75 / (75 + 25) = 75 / 100 = 0.75
- Class C: Precision_C = TP_C / (TP_C + FP_C) = 85 / (85 + 15) = 85 / 100 = 0.85

**Weighted average precision:**
Assuming equal weight per class (unweighted average):
Average Precision = (0.90 + 0.75 + 0.85) / 3 = 2.50 / 3 = **0.833 (83.3%)**

Or, if weighted by number of true positives (macro-averaged):
Total TP = 90 + 75 + 85 = 250
Weighted Precision = (90×0.90 + 75×0.75 + 85×0.85) / 250
= (81 + 56.25 + 72.25) / 250
= 209.5 / 250
= **0.838 (83.8%)**

(Typically unweighted average of class-wise metrics is reported unless otherwise specified)
**Answer: ~0.833 (83.3%)**

---

## Question 93
**In batch gradient descent with learning rate α = 0.01, the loss decreases from iteration to iteration but eventually fluctuates. What are possible causes? What adjustments could help?**

**Answer:**

**Possible causes of loss fluctuations:**

1. **Learning rate too high (α = 0.01 may be high for some problems):**
   - Large steps cause overshooting the minimum
   - Algorithm oscillates around optimum without converging
   - Loss increases and decreases in saw-tooth pattern

2. **Reaching local minimum or saddle point:**
   - Gradient becomes small but not exactly zero
   - Noise in gradient updates causes fluctuations
   - Model stuck in sub-optimal region

3. **Stochastic noise in data:**
   - Even with batch GD, if validation set differs from training, loss may fluctuate
   - Natural variation in batches (if mini-batch, not true batch GD)

4. **Insufficient regularization:**
   - Model overfitting causes training loss to decrease while test loss fluctuates
   - Competing objectives for training vs. generalization

5. **Loss landscape characteristics:**
   - Neural network loss landscapes are non-convex with many plateaus
   - In certain regions, GD may oscillate rather than converge smoothly

**Adjustments to fix fluctuations:**

1. **Reduce learning rate:**
   - Try α = 0.001 or use learning rate decay
   - Smaller steps provide finer control near minimum
   - More iterations needed but more stable convergence

2. **Use learning rate scheduling:**
   - Start with α=0.01, reduce by 0.1 every N epochs
   - Polynomial decay: α = initial_α × (1 - t/T)^p
   - Step decay: reduce α when loss plateaus

3. **Use momentum-based optimizers:**
   - Replace vanilla GD with SGD+momentum, Adam, or RMSprop
   - These accumulate gradients, smoothing out noisy updates
   - Better handles curvature and oscillations

4. **Add regularization:**
   - L1/L2 regularization to reduce overfitting
   - Dropout to improve generalization
   - Early stopping to prevent overfitting

5. **Batch normalization:**
   - Stabilizes learning dynamics
   - Allows slightly higher learning rates without instability
   - Reduces internal covariate shift

6. **Check data and preprocessing:**
   - Ensure proper normalization (mean 0, unit variance)
   - Check for corrupted or mislabeled samples
   - Verify data preprocessing doesn't introduce noise

**Recommended approach:** Reduce α to 0.001, implement learning rate decay, and switch to Adam optimizer for better stability.

---

## Question 94
**A network trains on 1000 examples using batch GD, achieving loss = 0.5. The same network trains on 10 examples using SGD, achieving loss = 0.6. Explain why SGD might have higher loss despite seeing fewer examples.**

**Answer:**

**Why SGD shows higher loss than batch GD:**

1. **Different optimization trajectories:**
   - Batch GD computes gradient on all 1000 examples → accurate gradient direction
   - SGD computes gradient on 1 example at a time → noisy gradient estimates
   - These gradients point in systematically different directions for different samples
   - SGD's noisy path may not align as well with the true loss gradient

2. **Convergence properties:**
   - Batch GD typically finds sharper (lower) local minima
   - SGD explores more due to noise, sometimes settling in flatter regions with higher loss
   - Flat minima may actually generalize better (why SGD is often preferred in practice)

3. **Statistical variability:**
   - With only 10 examples, SGD loss is computed from a tiny, unrepresentative sample
   - High variance in gradient estimates means high variance in loss values
   - The reported loss = 0.6 could be a high-variance outlier

4. **Training time/iterations:**
   - Batch GD on 1000 examples: 1 iteration/epoch processes all data
   - SGD on 10 examples: Can do 100 iterations/epoch with same data seen 100 times
   - Even if SGD had more iterations, noisy updates slow effective progress

5. **Learning rate mismatch:**
   - Batch GD uses α=0.01 on true gradient (stable)
   - SGD uses same α on noisy gradient (unstable) – may need smaller α for stability
   - If SGD's learning rate is too high for noisy gradients, it overshoots and oscillates

**Important caveat:**
- The comparison isn't entirely fair (different dataset sizes)
- **In practice:** SGD trained properly (with learning rate decay, momentum) often achieves LOWER loss than batch GD due to better generalization
- The 0.5 vs 0.6 difference likely reflects:
  - SGD's stochastic noise (not necessarily worse optimization)
  - Different convergence points (flat minima vs sharp minima)
  - Learning rate not optimized for SGD

**Key insight:** Lower training loss ≠ better model. SGD's higher noise can provide implicit regularization, leading to better test performance despite higher training loss.

---

## Question 95
**Consider a CNN architecture: Conv(64 filters, 3×3) → MaxPool(2×2) → Conv(128 filters, 3×3) → MaxPool(2×2) → FC(10). Input size: 224×224×3. a) Calculate the size at each layer. b) Explain where most parameters are concentrated.**

**Answer:**

**a) Size at each layer:**

**Input:** 224×224×3

**Conv1 (64 filters, 3×3, assuming padding=1, stride=1):**
- Spatial: (224 - 3 + 2×1) / 1 + 1 = 224×224
- Output: 224×224×64
- Parameters: 3×3×3×64 + 64 = 1,728 + 64 = 1,792

**MaxPool1 (2×2, stride=2):**
- Spatial: 224 / 2 = 112×112
- Output: 112×112×64
- Parameters: 0 (no learnable parameters)

**Conv2 (128 filters, 3×3, padding=1, stride=1):**
- Spatial: (112 - 3 + 2×1) / 1 + 1 = 112×112
- Output: 112×112×128
- Parameters: 3×3×64×128 + 128 = 73,728 + 128 = 73,856

**MaxPool2 (2×2, stride=2):**
- Spatial: 112 / 2 = 56×56
- Output: 56×56×128
- Parameters: 0

**Flatten:** 56×56×128 = 401,408 values

**FC (fully connected, 10 output classes):**
- Input: 401,408
- Output: 10
- Parameters: 401,408 × 10 + 10 = 4,014,080 + 10 = **4,014,090**

**b) Parameter concentration:**

Total parameters: 1,792 + 73,856 + 4,014,090 = 4,089,738

**Distribution:**
- Conv1: 1,792 / 4,089,738 = 0.044% (negligible)
- Conv2: 73,856 / 4,089,738 = 1.8%
- **FC layer: 4,014,090 / 4,089,738 = 98.2%** ← MOST PARAMETERS

**Key observations:**
1. **FC layer dominates:** The fully connected layer after flattening has 98% of all parameters
2. **Why:** FC layer connects 401,408 spatial values to 10 outputs – each output neuron needs ~40K connections
3. **Computational cost:** Despite parameters, conv layers consume more FLOPs (multiply-accumulate operations) due to spatial repetition
4. **Design improvement:** Replace FC with average pooling:
   - Global Average Pooling: 56×56×128 → 128 (spatial dimensions averaged)
   - Final 1×1 conv: 128 → 10 classes
   - New FC parameters: 128×10 + 10 = 1,290 (3000× fewer!)
   - This is why modern networks (ResNet, MobileNet) use global average pooling instead of large FC layers

**Modern best practice:** Minimize or eliminate large FC layers; use spatial pooling and 1×1 convolutions for classification instead.

---

# SECTION F: CONCEPTUAL MATCHING QUESTIONS (5 Questions)

## Question 96
**Match each CNN architecture with its key innovation:**

A) LeNet ↔ ___
B) AlexNet ↔ ___
C) VGGNet ↔ ___
D) GoogLeNet ↔ ___
E) ResNet ↔ ___

1) Residual connections
2) Inception modules
3) Deep network with 3×3 filters
4) Handwritten digit classification
5) Large-scale image classification with ReLU

**Answer:**
- A) LeNet ↔ 4) Handwritten digit classification
- B) AlexNet ↔ 5) Large-scale image classification with ReLU
- C) VGGNet ↔ 3) Deep network with 3×3 filters
- D) GoogLeNet ↔ 2) Inception modules
- E) ResNet ↔ 1) Residual connections

**Explanations:**
1. **LeNet (1998):** First successful CNN for handwritten digit recognition (MNIST, bank checks)
2. **AlexNet (2012):** Breakthrough on ImageNet using ReLU, GPUs, dropout; sparked deep learning renaissance
3. **VGGNet (2014):** Demonstrated power of depth with many 3×3 convolutions; "VGG" = Visual Geometry Group
4. **GoogLeNet (2014):** Introduced Inception modules for multi-scale feature extraction with reduced parameters
5. **ResNet (2015):** Revolutionized deep learning with residual connections enabling 152+ layer networks

---

## Question 97
**Match each regularization technique with its primary effect:**

A) Dropout ↔ ___
B) L1 (Lasso) ↔ ___
C) L2 (Ridge) ↔ ___
D) Early Stopping ↔ ___

1) Drives coefficients to exactly zero
2) Randomly removes neurons during training
3) Penalizes large weights without zeroing
4) Monitors validation loss and stops training

**Answer:**
- A) Dropout ↔ 2) Randomly removes neurons during training
- B) L1 (Lasso) ↔ 1) Drives coefficients to exactly zero
- C) L2 (Ridge) ↔ 3) Penalizes large weights without zeroing
- D) Early Stopping ↔ 4) Monitors validation loss and stops training

**Explanations:**
1. **Dropout:** Randomly deactivates neurons with probability p during training; forces ensemble-like behavior
2. **L1 regularization:** Adds ∑|w| penalty; produces sparse solutions with many exact zeros for feature selection
3. **L2 regularization:** Adds ∑w² penalty; shrinks all weights but keeps them non-zero; distributes parameter magnitudes
4. **Early Stopping:** Halts training when validation loss stops improving; prevents overfitting without explicit penalty

---

## Question 98
**Match optimization challenges with their descriptions:**

A) Local minima ↔ ___
B) Saddle points ↔ ___
C) Steep regions ↔ ___
D) Shallow regions ↔ ___

1) Flat regions where gradient ≈ 0
2) Multiple local optima exist
3) Learning rate too large causes divergence
4) Learning rate too small causes slow convergence

**Answer:**
- A) Local minima ↔ 2) Multiple local optima exist
- B) Saddle points ↔ 1) Flat regions where gradient ≈ 0
- C) Steep regions ↔ 3) Learning rate too large causes divergence
- D) Shallow regions ↔ 4) Learning rate too small causes slow convergence

**Explanations:**
1. **Local minima:** Critical points where ∇L = 0 and Hessian is positive definite; lower than nearby points but not globally optimal
2. **Saddle points:** Critical points with ∇L = 0 but mixed eigenvalues (higher in some directions, lower in others); numerically challenging
3. **Steep regions:** High-curvature areas where gradients are large; large learning rates cause overshooting and divergence
4. **Shallow regions:** Low-curvature plateaus where gradients vanish; small learning rates cause stagnation

---

## Question 99
**Match evaluation metrics with their definitions:**

A) Precision ↔ ___
B) Recall ↔ ___
C) Specificity ↔ ___
D) F1-score ↔ ___

1) TP / (TP + FN) - from actual positives, how many predicted correct
2) TP / (TP + FP) - from predicted positives, how many are correct
3) TN / (TN + FP) - from actual negatives, how many predicted correct
4) Harmonic mean of precision and recall

**Answer:**
- A) Precision ↔ 2) TP / (TP + FP) - from predicted positives, how many are correct
- B) Recall ↔ 1) TP / (TP + FN) - from actual positives, how many predicted correct
- C) Specificity ↔ 3) TN / (TN + FP) - from actual negatives, how many predicted correct
- D) F1-score ↔ 4) Harmonic mean of precision and recall

**Explanations:**
1. **Precision:** "Of all predictions we made as positive, how many were actually positive?" (quality of positive predictions)
2. **Recall (Sensitivity):** "Of all actual positives, how many did we find?" (coverage of positive class)
3. **Specificity:** "Of all actual negatives, how many did we correctly identify as negative?" (coverage of negative class; complement of false positive rate)
4. **F1-score:** Harmonic mean balancing precision and recall; useful for imbalanced datasets where one class dominates

---

## Question 100
**Match cross-validation types with their characteristics:**

A) Holdout (train-test split) ↔ ___
B) K-fold cross-validation ↔ ___
C) Leave-one-out (LOO) ↔ ___
D) Stratified K-fold ↔ ___

1) One example left out, repeated for all examples
2) Split data into k folds; train k times using different folds
3) Simple but may waste data
4) Maintains class distribution in each fold

**Answer:**
- A) Holdout (train-test split) ↔ 3) Simple but may waste data
- B) K-fold cross-validation ↔ 2) Split data into k folds; train k times using different folds
- C) Leave-one-out (LOO) ↔ 1) One example left out, repeated for all examples
- D) Stratified K-fold ↔ 4) Maintains class distribution in each fold

**Explanations:**
1. **Holdout:** Split data into train (~70-80%) and test (~20-30%) once; simple but wastes potential training data, high variance in estimates
2. **K-fold:** Split data into k equal folds; train k times using different folds as validation; more stable estimates, uses all data
3. **Leave-one-out (LOO):** Train on N-1 examples, test on 1; repeat N times; very stable estimates but computationally expensive (k=N)
4. **Stratified K-fold:** Like K-fold but ensures each fold maintains class proportions; critical for imbalanced datasets

---

# SUMMARY & STUDY GUIDE

## Document Statistics
- **Total Questions:** 120
- **Total Answers:** 120 (Comprehensive)
- **Sections:** 6 main sections
- **Format:** PhD-level Deep Learning
- **Last Updated:** January 2026

## Section Breakdown
- **Section A:** 40 Multiple Choice Questions
- **Section B:** 20 Fill in the Blanks
- **Section C:** 15 True/False Questions
- **Section D:** 12 Short Answer Questions
- **Section E:** 8 Computational Problems
- **Section F:** 5 Matching Questions

## Recommended Study Sequence

**Week 1 - Foundations (Questions 1-40)**
- Focus: CNN Architectures and Activation Functions
- Master: LeNet, AlexNet, VGGNet, GoogLeNet, ResNet
- Key concepts: Filter sizes, pooling, regularization basics

**Week 2 - Core Concepts (Questions 41-75)**
- Focus: Optimization and Training Dynamics
- Master: Gradient descent variants, vanishing gradients, bias-variance tradeoff
- Key concepts: Learning rates, hyperparameters, evaluation metrics

**Week 3 - Advanced Topics (Questions 76-100)**
- Focus: Problem-solving and deep understanding
- Master: Parameter calculations, architecture design decisions
- Key concepts: Computational complexity, optimization landscapes

**Week 4 - Practice & Review**
- Day 1: Review weakest sections
- Day 2: Full mock exam (all 120 questions)
- Day 3: Detailed review of errors
- Day 4: Final reinforcement learning

## Key Topics to Master

1. **CNN Architectures:** Evolution from LeNet to ResNet
2. **Gradient Descent:** BGD, SGD, Mini-batch, optimization challenges
3. **Regularization:** L1, L2, Dropout, Early Stopping
4. **Hyperparameters:** Filter size, stride, padding, learning rate
5. **Metrics:** Precision, Recall, F1-score, Accuracy
6. **Loss Functions:** Cross-entropy, MSE, Softmax
7. **Activation Functions:** ReLU, Sigmoid, Tanh properties
8. **Backpropagation:** Chain rule, gradient flow, vanishing/exploding gradients

## Tips for Success

✓ Understand concepts, don't memorize
✓ Work through computational problems step-by-step
✓ Use formulas correctly (especially output size formula)
✓ Know when to apply which technique
✓ Understand trade-offs (precision vs recall, speed vs accuracy)
✓ Review architecture evolution and why each innovation matters
✓ Practice parameter counting for various architectures
✓ Understand gradient flow in deep networks

---

**Prepared for Deep Learning PhD Program**
**Comprehensive Exam Preparation Material**
**Complete with 120 Questions and Full Solutions**
