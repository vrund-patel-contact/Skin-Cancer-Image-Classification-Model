# Skin-Cancer-Image-Classification-Model

utilized and modified a EfficientNetB5 Convolutional Neural Network that can accurately identify whether an image is malignant or benign. 

- The model has an accuracy of 92.90%.
- The model has a test loss of 17.43%.

![Image](https://github.com/user-attachments/assets/3178ee6e-1555-433f-a23c-2d68c7107f48)

In order to analyze all of the model's results, we can check other values as well. The model displayed the following results:

- Precision (Macro Average): 93.00%
- Recall (Macro Average): 93.00%
- F1-score (Macro Average): 93.00%

![Image](https://github.com/user-attachments/assets/3bd846ba-03f9-43fc-830b-85c64bd8b28a)

The confusion matrix specifies that:
- 950 images were benign and the model correctly identified them as benign (true-negative).
- 50 images were benign but the model identified them as malignant (false-positive).
- 92 images were malignant but the model identified them as benign (false-negative).
- 908 images were malignant and the model correctly identified them as malignant (true-positive).
