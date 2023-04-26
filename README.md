Chest X-ray (CXR) is a non-invasive imaging modality used in the prognosis and management of chronic lung disorders like
tuberculosis (TB), pneumonia, coronavirus disease (COVID-19), etc. It is also used to help diagnose and monitor treatment for
various lung abnormalities. Most existing computer-aided diagnosis (CAD) systems only used classification tasks, and only a
few works have been dedicated to disease localization and severity scoring. Moreover, the existing deep learning approaches
use a class activation map and a saliency map, which generate a rough localization. This study aims to develop an end-to-end
multi-stage architecture for disease classification, infection region identification, and disease severity assessment. The first
stage of the proposed architecture identifies the relevant lung regions by eliminating the irrelevant portions. The second stage
classifies the images into one class based on an advanced fuzzy-based ensemble approach. The last stage of the network
identifies the infection regions, calculates the amount of infection if the image is classified as COVID-19, and assigns a score
(0–3) based on the severity of the infection. The COVID-19 images are classified into more specific severity levels, such
as mild, moderate, severe, and critical, according to the score assigned by the modified RALE scoring system. The study
utilizes publicly available datasets for the experiments and outperforms four previous state-of-the-art works. Lung segmentation,
followed by the proposed ensemble-based classification approach, improves the classification process. Our AI solution can be
helpful for clinicians and radiologists to report chest X- rays as a secondary reader to ensure no potential COVID cases were
missed, reduce reporting turnaround times, support clinical decision-making for better patient outcomes, and help alleviate
hospital staff workloads
