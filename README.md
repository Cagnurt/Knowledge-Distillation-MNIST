# Knowledge-Distillation-MNIST

This repository contains a notebook for a knowledge distillation project focused on training and evaluating student and teacher models on the MNIST dataset. The notebook includes code for defining the student and teacher models, as well as training and evaluation procedures.

The main task is to complete the implementation of the distillation function, which takes a pretrained teacher model, a student model, a training dataloader, and a temperature constant. The function utilizes Mean Squared Error (MSE) loss for teacher-student probability matching during distillation.

The repository provides a step-by-step guide to perform the following tasks:

1. Train a teacher network for 10 epochs, reporting the best validation and test accuracies achieved. Additionally, plot the validation accuracy as a function of training epochs.
2. Train a student network for 10 epochs, reporting the best validation and test accuracies obtained. Similarly, plot the validation accuracy with respect to training epochs.
3. Distill the knowledge from the teacher model into the student model using the implemented distillation function. Experiment with different temperature constants and the number of epochs. Report the temperature value that achieves the best distillation test accuracy, as well as the best validation and test accuracies obtained through the distillation process. Plot the validation accuracy during training.
4. Finally, plot the validation accuracy for both the distillation process (with the best temperature constant) and the standalone training of the student model on the same graph. Discuss and analyze the results obtained from training the student network without the teacher and the distillation process.

By exploring this repository, you will gain hands-on experience with knowledge distillation techniques and analyze the impact of distillation on the performance of the student model compared to standalone training.