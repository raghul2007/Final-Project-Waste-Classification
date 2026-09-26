# Final Project - Classify Waste Products Using Transfer Learning

This project implements an AI-powered binary waste classifier for EcoClean using transfer learning with VGG16.

## Classes
- Organic
- Recyclable

## Notebook
Open `Final project.ipynb` and run all cells from top to bottom.

## Required Tasks
1. Print TensorFlow version
2. Create `test_generator` using `test_datagen`
3. Print length of `train_generator`
4. Print model summary
5. Compile the model
6. Plot extract-feature training/validation accuracy
7. Plot fine-tuned training/validation loss
8. Plot fine-tuned training/validation accuracy
9. Plot test image using Extract Features Model with `index_to_plot = 1`
10. Plot test image using Fine-Tuned Model with `index_to_plot = 1`

## Dataset
A small synthetic fallback dataset is generated automatically if no real images are placed in the dataset folders. Replace it with the course's real waste images when available for genuine model performance.
