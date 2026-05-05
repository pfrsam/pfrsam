<h1 align="center">Hi, I'm Sarvarbek 👋</h1>

<p align="center">
  <b>AI/ML Engineer in Training · Hanyang University · Seoul, South Korea 🇰🇷</b><br/>
  <i>Building deep learning systems from scratch — one architecture at a time.</i>
</p>

<p align="center">
  <a href="mailto:sayfitdinovsarvar12@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://github.com/pfrsam">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
</p>

---

## 🧑‍💻 About Me

I'm a data science student at **Hanyang University**, passionate about deep learning, computer vision, and building end-to-end AI systems. I grew up in **Uzbekistan** and now study in **Seoul** — motivated by using AI to tackle real-world challenges.

- 🔭 I implement deep learning models **from scratch** in PyTorch — no black boxes
- 🌐 I build and **deploy full-stack web applications** with custom domains and hosting
- 🎯 Interested in ML research, computer vision, and applying for research fellowships

Feel free to explore my work in the **[Repositories](https://github.com/pfrsam?tab=repositories)** section.

---

## 🧠 Machine Learning Knowledge

I have solid theoretical and practical foundations in classical and modern machine learning, including:

**Fundamentals**
- Supervised & unsupervised learning, train/val/test splits, cross-validation
- Bias-variance tradeoff, overfitting, regularization (L1/L2, dropout)
- Loss functions: Cross-Entropy, MSE, Hinge Loss, Focal Loss, GIoU Loss
- Optimization: SGD, Adam, learning rate scheduling, gradient clipping
- Model training: mini-batch gradient descent, batch normalization, early stopping
- Fine-tuning & transfer learning, Parameter-Efficient Fine-Tuning (PEFT): LoRA, DoRA
- Data augmentation, class imbalance handling, dataset balancing

**Classical ML Algorithms**
- **k-Nearest Neighbors (k-NN):** Distance-based non-parametric classifier; implemented with custom MaxPriorityQueue and vectorized PyTorch broadcasting
- **Support Vector Machines (SVM):** Soft-margin SVM with Hinge Loss and L2 regularization for binary and multiclass classification via One-vs-Rest
- **Logistic Regression:** Multinomial logistic regression with Softmax for multiclass problems

---

## 🏗️ Deep Learning Architectures

### 🖼️ Convolutional Neural Networks (CNNs)
Image classification backbones for learning spatial feature hierarchies:
- **ResNet (18, 50)** — Residual connections with skip connections to solve the vanishing gradient problem; Bottleneck blocks for deeper networks
- **DenseNet (101)** — Dense connections where each layer receives feature maps from all preceding layers, maximizing feature reuse and gradient flow
- **EfficientNet** — Compound scaling of depth, width, and resolution using Mobile Inverted Bottleneck (MBConv) blocks with SiLU activations

### 📦 Object Detection
Region-based and end-to-end detection architectures:
- **R-CNN** — Two-stage detector: selective search generates ~2000 region proposals, each warped and passed through a CNN for classification
- **Fast R-CNN** — Improves R-CNN by running the entire image through a CNN once and using RoI Pooling to extract per-region features from the shared feature map
- **Faster R-CNN** — Replaces selective search with a learnable **Region Proposal Network (RPN)** fully integrated with the detection head; end-to-end trainable
- **RetinaNet** — Single-stage detector using a **Feature Pyramid Network (FPN)** backbone and **Focal Loss** to address extreme foreground-background class imbalance during dense prediction
- **DETR (Detection Transformer)** — Eliminates anchors and NMS entirely; treats detection as a set prediction problem using a Transformer encoder-decoder with **Hungarian matching** and GIoU loss

### 🔁 Recurrent Neural Networks (RNNs)
Sequential and temporal modeling architectures:
- **RNN** — Basic recurrent unit for sequence modeling; suffers from vanishing gradients on long sequences
- **LSTM (Long Short-Term Memory)** — Introduces input, forget, and output gates to learn long-range dependencies; avoids vanishing gradients
- **GRU (Gated Recurrent Unit)** — Streamlined version of LSTM with update and reset gates; fewer parameters, competitive performance
- **ConvLSTM** — Extends LSTM to spatiotemporal data by replacing matrix multiplications with convolutions; used for sequence prediction on spatial grids (e.g., satellite imagery)

### 🤖 Transformers & Vision Transformers
Attention-based architectures for vision and language:
- **Transformer** — Self-attention and cross-attention with multi-head attention, positional encodings, and FFN layers; foundation of modern deep learning
- **ViT (Vision Transformer)** — Splits an image into fixed-size patches treated as tokens; applies a standard Transformer encoder for image classification
- **Swin Transformer** — Hierarchical ViT using shifted window attention for efficient local-to-global feature extraction; serves as a strong backbone for downstream vision tasks
- **DETR** — See Object Detection above

---

## 🛠️ Tech Stack

### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

### Deep Learning & ML
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Weights & Biases](https://img.shields.io/badge/W%26B-FFBE00?style=flat-square&logo=weightsandbiases&logoColor=black)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)

### Web & Backend
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

### Tools & Platforms
![Google Colab](https://img.shields.io/badge/Colab-F9AB00?style=flat-square&logo=googlecolab&logoColor=black)
![Google Earth Engine](https://img.shields.io/badge/Google%20Earth%20Engine-4285F4?style=flat-square&logo=google&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

## 🌐 Web Development & Deployment

I build production-ready full-stack web applications and deploy them to live servers:

- **Django (Backend):** REST API design, ORM-based database management with PostgreSQL, user authentication (login, registration, session handling), URL routing, middleware, static & media file handling, and admin panel customization
- **Frontend:** Responsive UI with HTML5, CSS3, and JavaScript; interactive maps with Leaflet.js and data visualization with Chart.js
- **Deployment:** Configure and deploy projects on hosting servers (ISPmanager / Plesk); set up custom domains, SSL certificates, and serve Django apps with production-grade web servers
- **Database:** PostgreSQL for relational data modeling; SQLite for lightweight local development

---

## 📬 Contact

If you'd like to collaborate, discuss research, or just say hi:

**📧 sayfitdinovsarvar12@gmail.com**

---

<p align="center">
  <i>"The best way to understand an algorithm is to build it yourself."</i>
</p>
