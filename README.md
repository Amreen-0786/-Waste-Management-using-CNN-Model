# Waste Classification using CNN Model

## Dataset : https://www.kaggle.com/datasets/techsash/waste-classification-data/data
## In week-1..,

Firstly, the dataset was carefully prepared for training. Images were loaded dynamically from the given file paths, and OpenCV was used for reading and processing them into a consistent format. This ensured the data was clean and ready for use by the CNN model.

To improve the learning capability of the model, data augmentation techniques were applied. These techniques included operations like flipping, rotating, and zooming the images to create a more diverse training dataset. This helped the model generalize better to unseen data.

The training process was further optimized by including Batch Normalization layers in the CNN architecture. This helped stabilize the training and made it faster by normalizing the outputs of each layer.

Unnecessary warnings were suppressed in the code to make the output cleaner and more focused, allowing for better readability during development.

Lastly, the notebook incorporated a feature to visualize the CNN model architecture. This made it easier to understand and debug the model's structure.

These enhancements collectively improved the model's performance and usability, making it more robust for the task of waste classification.


## In Week-2..,

### CNN Model Development
During Week-2, the focus was on the design and development of a CNN model. The architecture of the model included:
- **Convolutional Layers**: Three convolutional layers were used to extract meaningful features from input images, each followed by pooling layers to downsample the feature maps and reduce dimensionality.
- **Dense Layers**: After flattening the output from the convolutional layers, dense layers were added to capture complex patterns. To prevent overfitting, dropout regularization was incorporated into the dense layers.
- **Final Layer**: A **sigmoid activation function** was used in the final output layer, which is suitable for binary classification tasks, categorizing the waste into two classes: Organic and Recyclable.

### Model Training and Results
- **Data Augmentation**: To increase the robustness of the model, data augmentation techniques such as rotation, width and height shift, zoom, and horizontal flip were applied to the training images. This helped in generating more varied training samples.
- **Training Accuracy**: The model achieved an impressive **training accuracy of 95.43%**, showing that it effectively learned from the training data.
- **Validation Accuracy**: The model's **validation accuracy stabilized around 90%**, indicating that while the model generalized well, there was still potential to improve its performance further.

### Improvements and Next Steps
Looking ahead, the following steps have been identified to enhance the model's performance:
- **Hyperparameter Tuning**: Experimenting with different learning rates, batch sizes, and kernel sizes to optimize the model and improve accuracy.
- **Early Stopping**: Implementing early stopping during training to prevent overfitting and enhance generalization by halting the training process when performance on the validation set starts to degrade.
- **Evaluation Metrics**: Incorporating additional metrics like precision, recall, and F1 score to gain a more detailed understanding of the model's classification effectiveness.

These efforts represent a solid foundation in developing a reliable waste classification system. The clear pathways for further optimization demonstrate potential for improving both accuracy and generalization in future iterations.

## In Week-3..,

During Week-3, model training, model testing and model deployment with accuracy and recall visualizations

# Thank You
