# covid19_xray_detection
COVID19 detection using Chest X-Ray Detection

The model was trained using a transfer learning approach using VGG16 as a pre trained [model](https://neurohive.io/en/popular-networks/vgg16/). The [COVID-19 dataset](https://github.com/ieee8023/covid-chestxray-dataset) used is an open-source dataset which consists of COVID-19 images from publicly available research, as well as lung images with different pneumonia-causing diseases such as SARS, Streptococcus, and Pneumocystis. The healthy X-ray dataset was taken from [kaggel Chest X-rays Dataset](https://www.kaggle.com/nih-chest-xrays/data). To even things out, 400 images of each classes were taken and split into 80-20% train test split. Performance analysis graphs are included in the repository. The model was trained on [Google Colab](https://www.youtube.com/watch?v=inN8seMm7UI) so some of the code in the notebook is to link the colab with the drive. 
 
