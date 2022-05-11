# Sign-Language-Pridiction
Sign Language Translator is a machine learning project aims to translate hand gestures to strings. We developed this as a term project of CS 464 Machine Learning course.
How to use

    Clone the repo: git clone https://github.com/ayberktecimer/Sign_Language_Detector.git && cd Sign_Language_Detector
    (Optional) Create a virtual environment
    Install dependencies: pip3 install -r requirements.txt
    Train models: cd src && python3 Runner.py Models are saved in generatedModels directory

Dataset

https://www.kaggle.com/emresulun/sign-language-letter-images

Context Sign language letters captured by webcam and converted to grayscale images.
Letters are not exactly ASL (American Sign Language) but they are adapted from ASL.

Content
2125 images
Image size is 300x300
The first letter indicates the label (e.g. A-1554389290.JPG)
"J" is missing
