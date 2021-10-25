# COVID19_detection_CNN_ensemble
CNN Ensemble Approach to Detect COVID-19 from Computed Tomography Chest Images

Abstract: In January 2020, the World Health Organization declared a global health emergency concerning the spread of a new coronavirus disease, which was later named COVID-19. Early and fast diagnosis and isolation of COVID-19 patients have proven to be instrumental in limiting the spread of the disease. Computed tomography (CT) is a promising imaging method for fast diagnosis of COVID-19. In this study, we develop a unique preprocessing step to resize CT chest images to a fixed size (256 × 256 pixels) that preserves the aspect ratio and reduces image loss. Then, we present a deep learning (DL) method to classify CT chest images based on the light-weight pre-trained EfficientNet-B3 CNN model and ensemble techniques. The proposed method, which we refer to as EfficientNet-B3-GAP-Ensemble, comprises an ensemble of a modified version of the EfficientNet-B3. We build the ensemble using multiple runs and multiple training epochs. We test the EfficientNet-B3-GAP-Ensemble on two common benchmark datasets, i.e., the COVID19-CT and SARS-CoV-2-CT datasets. The proposed method has outperformed state-of-the-art methods for both datasets. For the COVID19-CT dataset, it achieved 88.18% sensitivity, 88.29% precision, 88.18% accuracy, an F1-score of 88.15%, and AUC of 92.10%. With the SARS-CoV-2-CT dataset, we tested the proposed method under different train-test splits, i.e., 20%–80%, 50%–50%, and 80%–20%. For the latter split, the proposed method achieved 99.72% accuracy, 99.80% sensitivity, precision, and F1-scores, and an AUC score of 99.99%.



@Article{cmc.2021.015399,
AUTHOR = {Haikel Alhichri},
TITLE = {CNN Ensemble Approach to Detect COVID-19 from Computed Tomography Chest Images},
JOURNAL = {Computers, Materials \& Continua},
VOLUME = {67},
YEAR = {2021},
NUMBER = {3},
PAGES = {3581--3599},
URL = {http://www.techscience.com/cmc/v67n3/41618},
ISSN = {1546-2226},
DOI = {10.32604/cmc.2021.015399}
}
