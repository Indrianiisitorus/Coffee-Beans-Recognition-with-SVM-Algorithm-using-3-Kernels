# Coffee-Beans-Recognition-with-SVM-Algorithm-using-3-Kernels

This project is a recognition for coffee beans from Lintong Nihuta namely Arabica Coffee Sigarar Utang varieties using Support Vector Machine (SVM) with 3 types of kernel which are RBF Kernel, Polynomial Kernel, and Sigmoid Kernel. Here we are using non-linear SVM because our dataset will not be linearly separable. 

In this study, the researchers used the dataset used was the Sigarar Utang variety of Arabica coffee beans which consisted of 100 original images of defective coffee beans, 100 original images of non-defective coffee beans, 600 images of defective coffee beans resulting from image preprocessing and 600 images of non-defective coffee beans. image preprocessing, so that the total dataset is 1400 images. Image preprocessing consists of three types of processes, namely resize, grayscale, and augmentation. The algorithm used to introduce the Sigarar Utang Arabica coffee beans based on texture parameters into the defective coffee bean category and the non-defective coffee beans is the Support Vector Machine (SVM) algorithm with three types of kernels, namely RBF, polynomial, and sigmoid kernels.

The research dataset is applied to the feature extraction process using the Gray Level Co-occurrence Matrix (GLCM) method to be able to extract the four features that become texture parameters, namely contrast, homogeneity, correlation, and energy features. After obtaining the dataset in numerical form, then the learning process is carried out using a combination of SVM with three types of kernels to obtain the best modeling that can be used in introducing Arabica coffee beans based on texture parameters. The best modeling is to use a polynomial kernel with an accuracy of 96%. 

So you guyss may see the attachement in folder dataset
