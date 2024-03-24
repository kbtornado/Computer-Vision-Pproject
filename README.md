# Computer-Vision-Pproject
This GitHub repository contains a machine learning project focused on brain tumor detection and classification. The project aims to accurately detect and classify brain tumors using a combination of two datasets. The dataset consists of images belonging to four classes: Glioma, Meningioma, Pituitary, and No tumor.

The project follows a systematic approach to achieve accurate results. The key steps involved in the process are:

Preprocessing: The images undergo preprocessing to enhance image quality and reduce noise. A median filter is applied to filter the images and prepare them for further analysis.

Feature Extraction: The Histogram of Oriented Gradients (HOG) feature descriptor is used to extract relevant features from the preprocessed images. HOG captures shape and texture information, which are important for tumor classification.

Dimensionality Reduction: Principal Component Analysis (PCA) is applied to reduce the dimensionality of the feature space. This helps in reducing computational complexity and improving the efficiency of subsequent steps.

Cross-Validation: K-fold cross-validation is performed to evaluate the performance of the model. The dataset is divided into K subsets (folds), allowing for robust estimation of the model's accuracy by training and testing on different combinations of the data.

Machine Learning Models: Several machine learning models are applied to the preprocessed and feature-extracted data. The models are trained and tested on the dataset to determine the best-performing algorithm for brain tumor detection and classification.

After thorough evaluation, the XGBoost model achieved the highest accuracy of 92.02%. XGBoost is a gradient boosting algorithm known for its ability to handle complex datasets and produce accurate predictions. The main goal of this repository is to provide a comprehensive resource for researchers, students, and developers interested in brain tumor detection and classification using machine learning techniques.
