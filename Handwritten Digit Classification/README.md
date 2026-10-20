<img src="https://github.com/ChristiaanCronje/data-analytics-portfolio/blob/main/IGNORE/Headers/Handwritten%20Digit%20Classification.svg" alt="Handwritten Digit Classification"/><br>

<h1>
  <img src="https://github.com/ChristiaanCronje/data-analytics-portfolio/blob/main/IGNORE/Headers/Description.svg" alt="Description" height="30px"/>
</h1>

This project uses machine learning to classify handwritten digits from images. Using the `load_digits()` dataset from scikit-learn, I trained a Random Forest classifier to recognise digits from 0 to 9 and evaluated its performance on unseen data.

<h1></h1>

<img src="https://github.com/ChristiaanCronje/data-analytics-portfolio/blob/main/IGNORE/Headers/Dataset.svg" alt="Dataset" height="25px"/>

&#8287;&#8287;• **Dataset:** scikit-learn's built-in handwritten digits dataset.  
&#8287;&#8287;• **Images:** 1,797 grayscale images, each represented by 64 pixel features from an 8×8 image.  
&#8287;&#8287;• **Labels:** The correct digit for each image, ranging from 0 to 9.

<h1></h1>

<img src="https://github.com/ChristiaanCronje/data-analytics-portfolio/blob/main/IGNORE/Headers/Features.svg" alt="Features" height="25px"/>

&#8287;**Data Exploration**  
&#8287;&#8287;&#8287;&#8287;• Inspecting the dataset's dimensions and digit labels.  
&#8287;&#8287;&#8287;&#8287;• Visualising sample handwritten digit images.

&#8287;**Model Training & Selection**  
&#8287;&#8287;&#8287;&#8287;• Splitting the data into training and test sets.  
&#8287;&#8287;&#8287;&#8287;• Training a Random Forest classifier.  
&#8287;&#8287;&#8287;&#8287;• Using GridSearchCV and cross-validation to compare model configurations.

&#8287;**Model Evaluation**  
&#8287;&#8287;&#8287;&#8287;• Evaluating the selected model on the held-out test set.  
&#8287;&#8287;&#8287;&#8287;• Measuring accuracy, precision, recall and F1-score.  
&#8287;&#8287;&#8287;&#8287;• Using a confusion matrix to examine classification errors.

<h1></h1>

<img src="https://github.com/ChristiaanCronje/data-analytics-portfolio/blob/main/IGNORE/Headers/How%20to%20Run.svg" alt="How to Run" height="25px"/>

1. Open `Handwritten_Digit_Classification.ipynb` in Jupyter Notebook or VS Code with Jupyter support.
2. Run the notebook cells in order to reproduce the analysis, train the model and view the evaluation results.

<h1></h1>

<img src="https://github.com/ChristiaanCronje/data-analytics-portfolio/blob/main/IGNORE/Headers/Dependencies.svg" alt="Dependencies" height="30px"/>

&#8287;&#8287;• Python  
&#8287;&#8287;• scikit-learn  
&#8287;&#8287;• numpy  
&#8287;&#8287;• pandas  
&#8287;&#8287;• matplotlib

<h1></h1>

<img src="https://github.com/ChristiaanCronje/data-analytics-portfolio/blob/main/IGNORE/Headers/Limitations.svg" alt="Limitations" height="30px"/>

The dataset contains small 8×8 pixel images, which are simpler than many real-world handwriting images. The model's performance on this dataset may not reflect its performance on images with different sizes, image quality or handwriting styles.
