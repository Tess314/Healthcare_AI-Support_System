# Healthcare_AI-Support_System
Classify medical images using a Raspberry Pi

---------
File list
---------
data.zip </br>
SkinLesionClassificationModelTraining.ipynb </br>
classify.py

----------------------------
Tools used for building
----------------------------
Google Colab

----------
How to run
----------
1. Open SkinLesionClassificationModelTraining.ipynb in Colab
2. Upload data.zip to Colab
3. Run SkinLesionClassificationModelTraining.ipynb to create model weights
4. Offload exported model weights (skin_lesion_classifier.tflite) to Raspberry Pi
5. Run classify.py on Rasperry Pi
