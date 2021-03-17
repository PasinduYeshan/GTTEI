## Classification of Anomalies  in Gastrointestinal Tract through Endoscopic Imagery with Deep Learning

In this project we focused on classifying anomalies in Gastrointestinal Tract through Endoscopic Imagery with Deep Learning. We developed two models for this project and out of that modules, when used InceptionV3 model as base model, we got 92.73% training accuracy and 90.00% validation accuracy. Even though we got 93.12% training accuracy from the model which used VGG19 as the base model, validation accuracy was 87.25%. Therefore, as the appropriate model we selected InceptionV3  model and then as the first step we extracted and flattened the feature vector. Final classification was obtained by sending the resultant vector of the first step, through two dense layers with Re-LU activation and one dense layer with SoftMax activation.
#
## How to run the project
There are two .ipynb file per each model. To run the model you can use 
* Jupyter Notebook
    * Prerequisite
         * python 3.8
         * Anaconda Navigator
         * Tensorflow
         * Keras
         * matplotlib

    > You can simply open this .ipynb file and run all the cells to obtain result.

* Google Colaboratory
    > You can go to open notebook option in google Colaboratory and use upload option and upload the notebook to your google drive and run each cell. 
