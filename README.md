# Face_Mask_Detection_Project

September 2020 ~ February 2021  

Covid-19 Face Mask Detection Project  
: Detecting correct, incorrectly mask and no mask  
: Using image classification model(MobileNetV2) and face detector(SSD in Opencv)  

: 3 Labels(correct, incorrectly mask and no mask)로 구분하는 Mask Detector을 구현하였습니다.  

[File & Folder]  
1) mask_classifier.py

tensorflow 2.3.0
mask_classifier model을 만들어주는 코드입니다
Dataset 정보는 코드 내에 주석을 참고해주세요
Dataset 경로만 잘 설정해 주시면 model 파일을 생성할 수 있습니다
(models 폴더 내 사전 제작된 model 파일이 있습니다)

2) models 폴더

face detector: opencv face detector(SSD와 Resnet-10 기반)
model: mask classifier model(MobileNetV2 기반)

3) video.py

tensorflow 2.3.0
face detector, mask classifier 모델을 불러와서 비디오 혹은 실시간 영상에 대해 mask detection을 수행합니다.
