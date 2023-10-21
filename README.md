# LesionDetector
Detection of lesions using endoscopic imaging data. We develop a lesion detection model using meditation data of Capsule Endascopy (capsule endoscope), which is used for minimally invasive surgery. Muti-Class Object Detection is performed and the number of classes is 4.

## 01 Data set
1. train - 학습용 json 파일 62622개
2. test - 평가용 json 파일 20874개
### 이미지 데이터는 base64형식으로 json파일에 포함되어있다.
3. class_id.csv - 객체별 제출 id정보

| class : 객체이름| class_id : 객체 id|
| --------------- |----------:| 
| 01_ulcer      |1|
| 02_mass       | 2| 
| 04_lymph      |3|
| 05_bleeding   |4|

## 02 EDA

### Statistics by Lesion Type
![01](https://github.com/hyeseon-cpu/first/assets/128684012/9172a30a-787f-43bd-9071-aadc50775c33)
### Cases with Only One Type of Lesion
![02](https://github.com/hyeseon-cpu/first/assets/128684012/de157e81-8ef0-4428-b291-395f1860e843)
### Cases with Two Types of Lesions
![03](https://github.com/hyeseon-cpu/first/assets/128684012/d9a9c62f-76ea-4cf1-b322-a4533fcc5195)
### Cases with Duplicate Lesions
![04](https://github.com/hyeseon-cpu/first/assets/128684012/7303be66-4c71-4f18-98b7-5659dd880c60)
### Image Size Statistics
![05](https://github.com/hyeseon-cpu/first/assets/128684012/8cdbbf8d-4abe-4ca7-8a05-4aa4699396d9.png)
### Bounding Box Count
![05](https://github.com/hyeseon-cpu/first/assets/128684012/8cdbbf8d-4abe-4ca7-8a05-4aa4699396d9.png)
