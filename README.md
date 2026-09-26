# Final Project - Classify Waste Products Using Transfer Learning

## Important dataset note
The course materials available for this project did not include a dataset. This submission therefore contains a small synthetic demonstration dataset so the notebook can be executed end-to-end. It is not an official Coursera/IBM dataset.

## Graded tasks
The notebook contains separate cells for:
1. TensorFlow version
2. `test_generator`
3. `len(train_generator)`
4. `model.summary()`
5. model compilation
6. extract-features accuracy curves
7. fine-tuned loss curves
8. fine-tuned accuracy curves
9. extract-features test image (`index_to_plot = 1`)
10. fine-tuned test image (`index_to_plot = 1`)

The graded task cells intentionally do not contain the text `#Pre-Defined Data`.

## Running
Install dependencies and run the notebook from top to bottom. VGG16 uses ImageNet pretrained weights, so the first model creation may require internet access to download the weights if they are not already cached.

Before submitting to Coursera, use **Run All** and save the notebook so that the required outputs and plots are stored in the `.ipynb` file.
