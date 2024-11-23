# Dog vs Cat Image Classification Using Transfer Learning  

This project implements a binary image classification system to distinguish between images of dogs and cats using transfer learning. By leveraging the VGG16 pre-trained model, the solution achieves efficient feature extraction and accurate predictions.  

---

## Features  
- **Data Preprocessing**:  
  - Resized images to `(224, 224)` for compatibility with VGG16.  
  - Assigned class labels (`0` for cats, `1` for dogs).  
  - Splits dataset into training, validation, and test sets.  

- **Model Development**:  
  - Used VGG16 pre-trained on ImageNet as a feature extractor.  
  - Added custom dense layers for binary classification.  
  - Compiled with the Adam optimizer and sparse categorical cross-entropy loss.  

- **Model Training and Evaluation**:  
  - Tracks performance using accuracy, precision, recall, F1-score, and confusion matrix.  
  - Visualizes predictions for test images alongside true labels.  

---

## Usage  
1. **Clone the repository**:  
   ```bash
   git clone https://github.com/yourusername/dog-cat-classifier.git
   cd dog-cat-classifier
2. **Install Dependecies**:
    pip install -r requirements.txt
3. **Prepare the dataset**:
   Place cat images in one folder and dog images in another.
   Update the cats_folder and dogs_folder paths in the script.
4. **Run the script**:
   python classifier.py

## Results
**Results**
**Performance Metrics**:

Achieved high accuracy in distinguishing between dogs and cats.
Precision, recall, F1-score, and confusion matrix demonstrate robustness.

**Visualizations**:

Displays test image predictions vs. true labels for easy evaluation.
