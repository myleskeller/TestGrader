# testGrader

Our code investigates the process of automatically grading multiple choice exams using images from a smartphone with computer vision. We leveraged the open-source OpenCV and Tesseract OCR to streamline design with their robust example code and prepackaged computer vision functionality.

Our approach included creating and printing example exams and answer keys, obtaining an image of both and transforming those images back into rectangles, isolating and determining the chosen user-completed exam answers, scoring the exam by comparing the results of the user answers and the answer key, and superimposing the scored results onto the original input image of the exam.

In testing, our program was able to correctly crop, transform, and orient images of an exam and its corresponding answer key, detect the answer bubbles on the exam in 90.67% of user submissions, and correctly interpret the selected answer with 94.1% accuracy

The .ipynb file was way too big up transfer here from Google Colaboratory, so here's the link:
https://colab.research.google.com/drive/1C_xag0p4MkLfrPOihxTeESGrS2IhYgsa?usp=sharing
