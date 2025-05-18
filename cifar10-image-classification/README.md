This project implements a Convolutional Neural Network (CNN) using PyTorch to classify images from the CIFAR-10 dataset. It trains a simple CNN model to recognize objects like airplanes, cars, birds, cats, and more.

📌 Project Highlights
- Dataset: CIFAR-10

- Framework: PyTorch

- Model: Custom CNN with convolutional and fully connected layers

- Training: SGD optimizer, CrossEntropyLoss, 30 epochs

- Evaluation: Accuracy calculated on test data

🧠 Model Architecture
- Conv2D → ReLU → MaxPool

- Conv2D → ReLU → MaxPool

- Flatten

- Fully Connected Layers (3 layers total)

📁 Dataset
- CIFAR-10 is automatically downloaded by torchvision.datasets.CIFAR10. It contains:

- 60,000 32x32 color images

- 10 classes: airplane, car, bird, cat, deer, dog, frog, horse, ship, truck

📈 Results
- Trained for 70 epochs

- Final test accuracy: ~67.89%

🧊 Future Improvements
- Use a pretrained model like ResNet

- Add GPU support (already compatible with CUDA)

- Improve accuracy with data augmentation
