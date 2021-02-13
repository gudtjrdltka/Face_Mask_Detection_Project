# Face_Mask_Detection_Project

September 2020 ~ February 2021  

Covid-19 Face Mask Detection Project  
: Detecting correct, incorrectly mask and no mask  
: Using Mask Classifier(MobileNetV2) and face detector(SSD in OpenCV)  

: 3 Labels(correct, incorrectly mask and no mask)로 구분하는 Mask Detector(Mask Classifier + Face Detector)을 구현하였습니다.  

[File & Folder]  
1) modelS(folder)
* model: Mask Classifier(MobileNetV2) - Finetuned to classify 3 labels
* res10_300x300_ssd_iter_140000.caffemodel: Face Detector(in OpenCV)

2) Final Presentation.pdf

3) Try.py
* tensorflow 2.3.0  
* Mask Classifier, Face Detector 모델을 불러와서 비디오 혹은 실시간 영상(웹캠)에 대해 Mask Detection을 수행합니다.

4) mask_classifier.ipynb

* tensorflow 2.3.0
* Mask Classifier model을 만들어주는 코드입니다
* Dataset 정보는 코드 내에 주석을 참고해주세요
* Dataset 경로만 잘 설정해 주시면 model 파일을 생성할 수 있습니다
* models 폴더 내 사전 제작된 model 파일이 있습니다

