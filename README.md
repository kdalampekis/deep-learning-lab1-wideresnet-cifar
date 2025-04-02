# 🧠 Deep Learning - Lab 1: WideResNet on CIFAR-10 & CIFAR-C

This notebook contains solutions and experiments for **Lab 1** of the Deep Learning course.  
The focus is on training and evaluating **WideResNet architectures** on the **CIFAR-10** dataset, applying **regularization techniques**, and evaluating **generalization** on **CIFAR-C**.

---

## 🔍 Objectives

- Evaluate the performance of WideResNet with different `depth` and `width` values
- Apply **Dropout regularization** to improve model robustness
- Evaluate model on **corrupted data (CIFAR-C)**
- Implement and assess the effect of **Mixup** data augmentation
- Analyze **softmax confidence** distributions (Bonus)

---

## 📊 Technologies Used

- PyTorch
- torchvision
- CIFAR-10 / CIFAR-C
- Google Colab / Drive
- NumPy, Matplotlib

---

## 📎 Instructions

> ⚠️ **Do not edit graded cells.**  
> ✅ Add comments to explain your experimental choices.  
> 🚫 Avoid training for more than 20 epochs per experiment.

---

## 🧪 Model Evaluation Metrics

- Validation Accuracy
- Loss Curves
- CIFAR-C Test Performance
- Softmax Confidence Histograms (bonus)

---

## ✅ Notes

- Training and evaluation pipelines follow the guidelines in the original WideResNet paper.
- Mixup is implemented directly in the CIFAR dataset loading process.
- Ideal for exploring robustness and regularization in deep networks.

---

## 📚 Educational Use

This notebook is part of a university deep learning course and is designed for educational and experimental purposes.
