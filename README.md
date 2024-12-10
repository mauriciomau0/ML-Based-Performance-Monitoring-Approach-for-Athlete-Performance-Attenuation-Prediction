# ML-Based-Performance-Monitoring-Approach-for-Athlete-Performance-Attenuation-Prediction
This machine learning approach aims to predict performance attenuation in scenarios using the same or related variables, emphasizing the need for an accurate model and preprocessing technique selection for predictive performance monitoring.

## Abstract 
Assessment of athletes' performance, including pre-game physical measurements and pre/post-game rankings, is challenging due to various physiological, external, and health factors. Established techniques for performance attenuation assessment are vital for mitigating it. Thus, this study aims to improve performance monitoring via predictive models while developing an understanding of performance-attenuation-related metrics through rankings predictions.  The study included data from forty-one male Gaelic football players, including physical, anthropometrical, and subjective markers such as CMJ (Countermovement Jump), DJ (Drop Jump), RSI (Reactive Strength Index), and perceptual responses which were captured to evaluate neuromuscular, perceptual, and biochemical responses. The best machine learning models predicted the rankings, and precision, F1-score, and recall assessed their performance. Additionally, principal component analysis (PCA), a method to reduce data dimensionality, was employed alongside balancing techniques (SMOTE, ROSE, and ADASYN) to examine their influence on the models. Our results emphasize the benefits of combining different models and balancing techniques as the alignment between PCA, SHAP values, and permutation importance reveals the role of various features in predicting performance attenuation-related outcomes, reinforcing factors such as strength metrics, lower body power, and speed, all of which influence our models' predictive capabilities. This machine learning approach aims to predict performance attenuation in scenarios using the same or related variables, emphasizing the need for an accurate model and preprocessing technique selection for predictive performance monitoring. We discuss how balancing techniques offer potential and limitations regarding results' generalizability while calling for developing more advanced protocols to address similar prediction requirements.

Access link to the paper will be available soon. 

## Installation & Setup

This project is designed to be run within Google Colab. To get started:

1. **Access the Notebook:** Click on the "Open in Colab" badge below to open the notebook directly in Google Colab:

   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1q73segl1EtR1S-TfrhBhqi4bpcEh87od?usp=sharing)

2. **Connect to Runtime:** In Colab, click "Connect" in the top right corner to connect to a runtime environment.

3. **Run the Cells:** Execute the code cells in the notebook sequentially to load data, perform preprocessing, train models, and evaluate results. You can run a cell by clicking the play button next to it or pressing `Shift+Enter`.
