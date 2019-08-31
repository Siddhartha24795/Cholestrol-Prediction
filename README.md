# Cholestrol-Prediction
It explains method to predict cholesterol using simple picture of eye through a normal phone camera.

Steps:

1. The eye images were acquired from the subjects with normal/abnormal cholesterol levels.

2. Along with the eye images, the fasting serum cholesterol levels of the same subjects were documented.

3. After data collection, the eye images in the study database were pre-processed and the cornel lipid deposition was segmented from the other regions of the eye image.

4. After segmentation process, the Gray Level Mean (GLM) value of the segmented lipid deposition was computed. 

5. The Cholesterol Detection Regression (CDR) model was created using the GLM values of the lipid deposition in the input eye images and their corresponding serum cholesterol levels.
