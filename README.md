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
1. Open SkinLesionClassificationModelTraining.ipynb in Colab.
2. Upload data.zip to Colab.
3. Run SkinLesionClassificationModelTraining.ipynb to train model.
4. Offload model weights (skin_lesion_classifier.tflite, which is created in step 3) to Raspberry Pi.
5. Run classify.py on Rasperry Pi.
