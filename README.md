# ML_S5_etudiants - Machine Learning Course Repository

Official GitHub repository for **ENM-ENSEEIHT Machine Learning** courses. 
This repository contains comprehensive practical sessions, theory slides, and training materials covering fundamental to advanced deep learning concepts.

## Repository Structure

### **practicals/** - Hands-On Learning Modules (P1-P8)

Interactive Jupyter notebooks designed for progressive learning from foundational neural networks to advanced techniques:

#### **P1: Foundations of Neural Networks** 
- **Topics:** Training via Stochastic Gradient Descent (SGD), Multi-layer Perceptron (MLP), Negative log-likelihood loss
- **Key Concepts:** Backpropagation, weight initialization, PyTorch fundamentals
- **Skills:** Understanding the perceptron as basic building block for deep learning

#### **P2: Convolutional Neural Networks - Architecture Deep Dive**
- **Topics:** Convolutional layers, Pooling operations, VGG and ResNet architectures, ImageNet pre-training
- **Key Concepts:** Kernel self-organization during training, feature map visualization, receptive fields
- **Skills:** Understanding CNNs for image feature extraction, classical architecture design

#### **P3: Training Strategies for Vision Models**
- **Topics:** Training from scratch vs. pre-training, Fine-tuning & transfer learning, Data augmentation (DAUG), Freezing layers
- **Key Concepts:** Validation steps, learning curves analysis, generalization and overfitting
- **Applications:** MNIST digit classification, binary image classification with limited data
- **Skills:** Model selection, hyperparameter tuning, handling small datasets efficiently

#### **P4: Attention Mechanisms & Sequential Processing**
- **Topics:** Attentional layers, Multi-headed attention, Transformer architecture fundamentals
- **Key Concepts:** Query-Key-Value computation, self-attention, positional encoding
- **Benchmark Tasks:** Dyck validity testing, addition, parity checks - standard toy problems for sequence models
- **Skills:** Building sequence-to-sequence models, understanding attention flow

#### **P5: Dense Prediction & Weak Supervision (Parts I & II)**

**Part I - Semantic Segmentation & Image Processing:**
- **Topics:** Semantic segmentation, Fully Convolutional Networks (FCN), U-Net architecture
- **Metrics:** Intersection over Union (IoU) for pixel-level evaluation
- **Applications:** Image denoising, scene understanding

**Part II - Learning from Imperfect Supervision:**
- **Topics:** Weak supervision paradigms, Noise-to-Noise learning, Neural Eggs Separation scenario
- **Key Concept:** Training with noisy or incomplete ground truth labels
- **Skills:** Handling real-world annotation challenges, robust learning strategies

#### **P6: Generative Models - GANs**
- **Topics:** Generative Adversarial Networks (GANs), Generator-Discriminator framework
- **Advanced Concepts:** Mode Collapse problem & solutions, Wasserstein GAN (WGAN), Conditional GAN (cGAN)
- **Applications:** Image synthesis, conditional generation
- **Skills:** Adversarial training dynamics, stability techniques, loss function design

#### **P7: Probabilistic Prediction - Quantile Regression**
- **Topics:** Quantile regression, Pinball Loss function, Conditional probability estimation
- **Key Concept:** Learning full conditional distributions $p(y|x)$ rather than point estimates
- **Applications:** Uncertainty quantification, confidence interval prediction
- **Skills:** Custom loss functions, probabilistic neural networks

#### **P8: Learning to Rank - Advanced Loss Functions**
- **Topics:** Learning-to-rank, Ranking functions, Curriculum learning, Hinge Loss, RankNet Loss
- **Key Concepts:**
  - **Siamese Networks:** Shared weight architectures for pairwise comparisons
  - **Hinge Loss:** Margin-based pairwise loss formulation
  - **RankNet Loss:** Bradley-Terry probabilistic model for ranking
  - **Curriculum Learning:** Progressive training difficulty (easy pairs → hard pairs)
  - **Rank Metrics:** Spearman and Kendall correlations
- **Applications:** Object ranking by visual attributes, relevance assessment
- **Skills:** Custom loss design, metric selection for ranking tasks

---

## Machine Learning Concepts Covered

### **Core Neural Network Topics**
- Perceptron & Multi-Layer Perceptron (MLP)
- Stochastic Gradient Descent (SGD) & optimization
- Backpropagation & automatic differentiation
- Activation functions & loss function design

### **Convolutional Methods**
- Convolution operations & spatial feature extraction
- Pooling strategies (Max, Average)
- Classical architectures: VGG, ResNet
- Feature map visualization & interpretation

### **Training Methodologies**
- Training from scratch
- Transfer learning & fine-tuning
- Data augmentation techniques
- Validation strategies & hyperparameter tuning
- Curriculum learning (progressive difficulty)

### **Attention & Transformers**
- Self-attention mechanisms
- Multi-head attention
- Positional encoding
- Sequence-to-sequence models

### **Dense Prediction Tasks**
- Semantic segmentation (pixel-level classification)
- Fully convolutional networks (FCN)
- U-Net encoder-decoder architecture
- Intersection over Union (IoU) metric

### **Generative Models**
- Generative Adversarial Networks (GANs)
- Generator & Discriminator training dynamics
- Mode collapse & stabilization techniques
- Wasserstein distance-based training (WGAN)
- Conditional generation (cGAN)

### **Advanced Loss Functions & Metrics**
- Negative log-likelihood (cross-entropy)
- Hinge loss (margin-based)
- Pinball loss (quantile regression)
- RankNet loss (probabilistic ranking)
- Wasserstein loss
- Ranking metrics (Spearman, Kendall correlations)

### **Specialized Learning Paradigms**
- Supervised learning (classification, regression)
- Weak supervision (learning with noisy labels)
- Self-supervised learning principles
- Probabilistic prediction & uncertainty quantification
- Ranking & ordinal prediction

---

## Additional Resources

### **slides/** 
- Theoretical foundations and mathematical background
- Lecture notes covering concepts in each practical session
- Visual explanations of key algorithms

### **trainings/**
- Presentation sheets for key concepts
- Slide decks with detailed explanations
- Supplementary materials for deeper understanding

---

## Course Information

- **Duration:** Complete course spans approximately 15-20 hours
- **Level:** Advanced Bachelor / Master level
- **Prerequisites:** Basic Python, linear algebra, probability fundamentals
- **Institution:** ENM-ENSEEIHT

---

## Notes

Each practical includes:
- Detailed theoretical background
- Step-by-step code implementation exercises
- Visualization and interpretation of results
- Challenges to deepen understanding

All notebooks are designed for hands-on learning with guided exercises and increasing complexity levels.
