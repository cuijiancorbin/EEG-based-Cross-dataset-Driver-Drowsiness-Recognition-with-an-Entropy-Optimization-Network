# EEG-based-Cross-dataset-Driver-Drowsiness-Recognition-with-an-Entropy-Optimization-Network
Cross-dataset driver drowsiness recognition with EEG is important for the advancement of a calibrationfree driver drowsiness recognition system. Nevertheless, this task is challenging due to the impact of distribution drift on recognition accuracy. In this paper, we propose a novel model named entropy optimization network (EON) for the task. The model takes a novel two-step strategy
to separate the unlabeled data from the target domain. It firstly pushes the samples out of support of source towards the decision boundary and then gradually separates them (entropy reduction) with a self-training framework by taking adequate advantage of underlying patterns inherent in the unlabeled dataset. The proposed method is tested on the domain adaptation task with two public datasets, and achieves 2-class recognition accuracies of 89.2% and 77.6%, which beats other baseline methods. Our work illuminates a promising direction in achieving the ultimate objective of developing a driver drowsiness recognition system without calibration.

The processed SADT dataset can be downloaded here: https://figshare.com/articles/dataset/EEG_driver_drowsiness_dataset/14273687

The processed SEED-VIG dataset can be downloaded here: https://figshare.com/articles/dataset/Extracted_SEED-VIG_dataset_for_cross-dataset_driver_drowsiness_recognition/26104987

Description on the backbone ICNN model can be found from:

Cui J, Lan Z, Sourina O, et al. EEG-based cross-subject driver drowsiness recognition with an interpretable convolutional neural network[J]. IEEE Transactions on Neural Networks and Learning Systems, 2022, 34(10): 7921-7933. DOI: 10.1109/TNNLS.2022.3147208

The paper is under review now ...
