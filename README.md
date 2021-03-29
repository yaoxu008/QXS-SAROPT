# QXS-SAROPT
QXS-SAROPT Dataset

![Image text](https://github.com/yaoxu008/QXS-SAROPT/blob/main/QXSLAB-SAROPT.png)


[Links to download the data](https://www.wenjuan.com/s/UZBZJv5GwL/)

Deep learning methods have made significant progress in ship detection in synthetic aperture radar (SAR) images. The pretraining technique is usually adopted to support deep neural networks-based SAR ship detectors due to the scarce labeled SAR images. However, directly leveraging ImageNet pretraining is hardly to obtain a good ship detector because of different imaging perspective and geometry. In this paper, to resolve the problem of inconsistent imaging perspective between ImageNet and earth observations, we propose an optical ship detector (OSD) pretraining technique, which transfers the characteristics of ships in earth observations to SAR images from a large-scale aerial image dataset. On the other hand, to handle the problem of different imaging geometry between optical and SAR images, we propose an optical-SAR matching (OSM) pretraining technique, which transfers plentiful texture features from optical images to SAR images by common representation learning on the optical-SAR matching task. Finally, observing that the OSD pretraining based SAR ship detector has a better recall on sea area while the OSM pretraining based SAR ship detector can reduce false alarms on land area, we combine the predictions of the two detectors through weighted boxes fusion to further improve detection results. Extensive experiments on four SAR ship detection datasets and two representative CNN-based detection benchmarks are conducted to show the effectiveness and complementarity of the two proposed detectors, and the state-of-the-art performance of the combination of the two detectors. The proposed method won the sixth place of ship detection in SAR images in 2020 Gaofen challenge.

[The QXS-SAROPT Dataset for Deep Learning in SAR-Optical Data Fusion](https://arxiv.org/pdf/2103.08259.pdf)

This paper must be cited when the dataset is used for research purposes.
