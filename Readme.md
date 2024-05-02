# CNN Image Recognotion and Adversarial attacks

In this project, I used PyTorch within the Python programming language to tackle the challenging task of image classification using Convolutional Neural Networks (CNNs). The primary goal was to develop a robust image classifier capable of differentiating various clothing items within the FashionMNIST dataset. Additionally, I implemented adversarial attacks, specifically the Fast Gradient Sign Method (FGSM) and Projected Gradient Descent (PGD) evasion attacks, to evaluate and enhance the model's resilience against adversarial inputs.

## Project Details:

1. CNN Implementation: Built a CNN for classifying FashionMNIST clothing images. The model has these main component including convolutional and pooling layers, along with three fully connected (fc) layers inspired by LeNet. Achieved training accuracy of 91.65%.
2. FashionMNIST Dataset: Used FashionMNIST dataset (60,000 training, 10,000 testing images).
3. Adversarial Attacks:

-   Fast Gradient Sign Method (FGSM): Perturbed images by adding gradient-based noise. Achieving attack accuracy of 96.07%.
-   Projected Gradient Descent (PGD): Iteratively applied FGSM for robustness testing. Achieving attack accuracy of 95.32%.

4. Robustness Evaluation: Tested model accuracy against normal and adversarial conditions.
5. Model Defense: Explored defense strategies like adversarial training and preprocessing.

# Skills

-   Convolutional Neural Networks (CNN)
-   Data Analysis
-   Data Visualization
-   Matplotlib
-   PyTorch
-   Numpy

# References

-   [Fashion-MNIST](https://github.com/zalandoresearch/fashion-mnist)
-   [FGSM evasion attack](https://arxiv.org/abs/1412.6572)
-   [PGD evasion attack](https://arxiv.org/pdf/1706.06083.pdf)
-   [Reference article](https://medium.com/swlh/gradient-based-adversarial-attacks-an-introduction-526238660dc9)
