# Microstructure-Classification-of-Ultra-High-Steel-Carbon-using-Twin-SVM
This project is my final year thesis project at IIT Madras under the supervision of Dr. Mansi Sharma, INSPIRE faculty in Dept. of Electrical Engineering and Dr. Satyesh Kumar Yadav, Assistant Professor in Dept. of Metallurgical and Materials Engineering at IIT Madras.

One of the goals of Materials Informatics (in general) and Image Driven Machine Learning
(in particular) is to extract quantitative data from micrographs to characterize microstructural
characteristics efficiently. Towards this goal, we have presented a case study on Ultra High
Carbon Steel(UHCS) where we investigate different SVM learning algorithms to classify microstructures
from image data.
We have built a microstructure classification model based on the UHCS dataset that classifies a
given microstructure into four labels: "Pearlite," "Spheroidite," "Carbide Network," and "Widmanstätten".
The dataset comprises images taken at a wide range of magnifications. Feature
extraction and dimensionality reduction were implemented before training SVM-based learning
algorithms. In the feature extraction step, features from different layers of the pre-trained
VGG16 model were evaluated based on their accuracy. In the classification step, we use a twostage
pipeline consisting of binary classification and voting. Twin Support Vector Machine and
Least Squares Support Vector Machine are used for binary classification. We then compare the
performance of these classifiers with the classical SVM algorithm. Results demonstrate that
Twin Support Vector Machine with linear kernel performed the best among all other classifiers
considered. Using t-SNE, a visualization technique, we show graphical methods to understand
