# Pneumonia-identification-from-X-Ray-images
#### Authors : Ana Solbas Casajús and Natalia García Sánchez
---

Final code project for the *Big Data Engineering* course in the **Masters in Computational Biology (UPM)**, with the purpose of training several MLlib Spark-based image classification models for predicting Pneumonia from patients in a Labeled Optical Coherence Tomography (OCT) and Chest X-Ray Image dataset 

The image dataset is composed of three folders `train, `test` and `val`, each of them having two folders relating to images from normal patients (present in the nested `NORMAL` folders) and patients undergoing pneumonia (present in the nested `PNEUMONIA` folders)

| Version   | Date | License | Dataset Folders | Citation | Source |  Acquired from  |
|----------|:-------------:|:------:|:------:|:------:|:------:|:------:|
| v.2.0 |  06/01/2018 | CC BY 4.0 | (`test`,`train`,`val`) | Kermany, D. S., Goldbaum, M., Cai, W., Valentim, C. C. S., Liang, H., Baxter, S. L., McKeown, A., Yang, G., Wu, X., Yan, F., Dong, J., Prasadha, M. K., Pei, J., Ting, M. Y. L., Zhu, J., Li, C., Hewett, S., Dong, J., Ziyar, I., … Zhang, K. (2018). Identifying Medical Diagnoses and Treatable Diseases by Image-Based Deep Learning. Cell, 172(5), 1122-1131.e9. https://doi.org/10.1016/j.cell.2018.02.010 | [Mendeley Data](https://data.mendeley.com/datasets/rscbjbr9sj/2) |  [Kaggle](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia) | 

The code includes the image embedding preprocessing stages, and the training and evaluation of ML models in the pipeline

| Version   | Date | Script | Description | 
|----------|:-------------:|:------:|:------:|
| --- | --- | `Preprocessing.ipynb` | Used for the embedding of images and obtaining the three final datasets `train.csv`, `test.csv` and `val.csv`|

