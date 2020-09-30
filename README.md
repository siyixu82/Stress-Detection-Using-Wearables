# Stress-Detection-Using-Wearables
 
 ## Project Introduction
The proposed study is a continuation of case study 3 of STA540. During the course, I have conducted feature extraction and trained machine learning model for detecting stress using WESAD data, a multimodal dataset for wearable stress, and affect detection. The model achieved a max accuracy of 83.4% for classifying stress vs. non-stress conditions.

The project also left some interesting problems to explore. For example, stress vs. non-stress's model achieved better accuracy than stress vs. amusement model, showing that amusement is harder to differentiate from stress. This study thus will also focus on stress vs. non-stress vs. amusement. Also based on the previous project, EDA and heart rate variability showed high importance over others. The proposed study also aims to conduct feature engineering to find the most important feature in predicting stress vs. non-stress and stress vs. non-stress vs. amusement. And the study will apply the knowledge to examine the stress detection accuracy of known wearables devices such as Apple Watch and Fitbit.

## Data
Schmidt, Philip, Attila Reiss, Robert Duerichen, Claus Marberger, and Kristof Van Laerhoven. “Introducing WESAD, a Multimodal Dataset for Wearable Stress and Affect Detection.” Proceedings of the 2018 on International Conference on Multimodal Interaction - ICMI 18, 2018. https://doi.org/10.1145/3242969.3242985.

## Reference
- The DBDP ML-Methods, https://github.com/DigitalBiomarkerDiscoveryPipeline/ML-Methods
- “Step-by-Step Guide to leave-one-person-out Cross Validation with Random Forests in Python”, https://medium.com/analytics-vidhya/step-by-step-guide-to-leave-one-person-out-cross-validation-with-random-forests-in-python-34b2eaefb628
