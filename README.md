# ds13k

DS13K- built with a VGG-16 Deep Convolutional Neural Network architecture performed with an accuracy rate of 68%.

Here are the models and relevant files produced by the paper "Improving Borderline Adulthood Facial Age Estimation through Ensemble Learning".



Content
--------------------------------------------
The caffe models.
An early VisAGe mean binaryproto file.
The age prototxt with the VGG16 architecture.
---------------------------------------------

If this material is useful for your research, please cite the following:


@inproceedings{10.1145/3339252.3341491,
author = {Anda, Felix and Lillis, David and Kanta, Aikaterini and Becker, Brett A. and Bou-Harb, Elias and Le-Khac, Nhien-An and Scanlon, Mark},
title = {Improving Borderline Adulthood Facial Age Estimation through Ensemble Learning},
year = {2019},
isbn = {9781450371643},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3339252.3341491},
doi = {10.1145/3339252.3341491},
abstract = {Achieving high performance for facial age estimation with subjects in the borderline between adulthood and non-adulthood has always been a challenge. Several studies have used different approaches from the age of a baby to an elder adult and different datasets have been employed to measure the mean absolute error (MAE) ranging between 1.47 to 8 years. The weakness of the algorithms specifically in the borderline has been a motivation for this paper. In our approach, we have developed an ensemble technique that improves the accuracy of underage estimation in conjunction with our deep learning model (DS13K) that has been fine-tuned on the Deep Expectation (DEX) model. We have achieved an accuracy of 68% for the age group 16 to 17 years old, which is 4 times better than the DEX accuracy for such age range. We also present an evaluation of existing cloud-based and offline facial age prediction services, such as Amazon Rekognition, Microsoft Azure Cognitive Services, How-Old.net and DEX.},
booktitle = {Proceedings of the 14th International Conference on Availability, Reliability and Security},
articleno = {57},
numpages = {8},
keywords = {Facial Recognition, Digital Forensics, Deep Learning, Underage Photo Datasets, Child Exploitation Investigation},
location = {Canterbury, CA, United Kingdom},
series = {ARES '19}
}
