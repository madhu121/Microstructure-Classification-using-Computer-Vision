# Microstructure-Classification-of-Ultra-High-Steel-Carbon-using-Twin-SVM

This project represents my final year thesis work conducted at IIT Madras under the guidance of Dr. Mansi Sharma, an INSPIRE faculty member in the Department of Electrical Engineering, and Dr. Satyesh Kumar Yadav, an Assistant Professor in the Department of Metallurgical and Materials Engineering at IIT Madras.

Materials Informatics, particularly Image Driven Machine Learning, aims to efficiently extract quantitative data from micrographs for characterizing microstructural characteristics. In this study, we focus on Ultra High Carbon Steel (UHCS) and explore various SVM learning algorithms to classify microstructures from image data.

We have developed a microstructure classification model using the UHCS dataset by Carnegie Mellon University, based on the work of Hecht et al., which categorizes microstructures into four labels: "Pearlite," "Spheroidite," "Carbide Network," and "Widmanstätten." The dataset includes images captured at a range of magnifications. Prior to training SVM-based learning algorithms, we performed feature extraction and dimensionality reduction.

During feature extraction, we evaluated features from different layers of the pre-trained VGG16 model based on their accuracy. For classification, we implemented a two-stage pipeline involving binary classification and voting. We utilized Twin Support Vector Machine and Least Squares Support Vector Machine for binary classification and compared their performance with the classical SVM algorithm. Our results indicate that the Twin Support Vector Machine with a linear kernel outperformed other classifiers.

Additionally, we utilized t-SNE, a visualization technique, to provide graphical insights into the classification process.

## References

- Hecht, M. D., B. A. Webler, and Y. N. Picard (2016). Digital image analysis to quantify carbide networks in ultrahigh carbon steels. Materials Characterization, 117, 134–143. (https://www.sciencedirect.com/science/article/pii/S104458031630105X)
- Hecht, M. D., Y. N. Picard, and B. A. Webler (2017). Coarsening of inter-and intra- granular proeutectoid cementite in an initially pearlitic 2c-4cr ultrahigh carbon steel. Met- allurgical and Materials Transactions A, 48(5), 2320–2335. (https://link.springer.com/article/10.1007/s11661-017-4012-2)
