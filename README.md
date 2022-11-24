# FirecovNet
**Implementation of my paper [FirecovNet: A Novel, Lightweight, and Fast Deep Learning-Based Network for Detecting COVID-19 Patients Using Chest X-rays](https://doi.org/10.3390/electronics11193068/)**



**Abstract**

At the end of 2019, a new virus (SARS-CoV-2) called COVID-19 was reported in Wuhan, China, and spread rapidly worldwide. After two years later, several variants of this virus were created, infecting 608 million people and causing 6.51 million deaths. Due to the insufficient sensitivity of RT-PCR test kits, one of the main tools for detecting the virus, chest X-ray images are a popular tool for diagnosing the virus in patients with respiratory symptoms. Models based on deep learning are showing promising results in combating this pandemic. A novel convolutional neural network, FirecovNet, is suggested in this study that detects COVID-19 infection automatically based on raw chest X-ray images. With an architecture inspired by the integration of DarkNet and SqueezeNet networks, the proposed model has fewer parameters than state-of-the-art models and is trained using COVID-19, bacterial pneumonia, normal, lung opacity, and viral pneumonia images, which were collected from two public datasets and also are symmetric in the distribution in class. FirecovNet performance has been verified using the stratified 5-fold cross-validation method. A total of five classification tasks are performed, including four 4-class classifications, and one 5-class classification, and the accuracy of all tasks was at least 95.9%. For all classification tasks, the proposed network has demonstrated promising results in precision, sensitivity, and F1-score. Moreover, a comparison was made between the proposed network and eight deep transfer learning networks and in terms of accuracy, precision, sensitivity, F1-score, speed, and size of the saved model; FirecovNet was very promising. Therefore, FirecovNet can be useful as a tool for more accurate diagnosis of the COVID-19 virus, along with diagnostic tests, in situations where the number of specialist radiologists may be limited.


![image](https://user-images.githubusercontent.com/57661230/203859044-c7f153f5-7cb0-4748-ae69-149c762cdcfe.png)



![image](https://user-images.githubusercontent.com/57661230/203859616-622b499e-874a-454f-9cf1-749e27487733.png)

**If you have used the codes in your research works, we would appreciate citation to our paper:**

*L. Hassanlou, S. Meshgini, R. Afrouzian, A. Farzamnia, and E. G. Moung, “FirecovNet: A Novel, Lightweight, and Fast Deep Learning-Based Network for Detecting COVID-19 Patients Using Chest X-rays,” Electronics, vol. 11, no. 19, p. 3068, Sep. 2022, doi: 10.3390/electronics11193068.*
