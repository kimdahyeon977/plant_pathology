# :leaves: Plant Pathology 프로젝트의 코드를 모아두었습니다. :leaves: 

### 크게 3가지 모델로 이루어져있습니다. 하위 분류는 버전차이입니다. ###
### (1) . classification 
### (2) . Detection
### (3) . Image Retreival

## < 각 파일에 대한 간략한 설명 > ##

## (1). Classification
#### (1-1). active-learning.ipynb : 분류모델에 active learning을 적용한 코드입니다.

#### (1-2). cross-validation_(3).ipynb : 분류모델에 active learning을 적용하기 전 코드입니다. 결과를 시각화한 코드도 포함합니다.

## (2). Detection
#### (2-1). ai.ipynb : icevision으로 객체 인식을 한 기본 코드입니다.

#### (2-2). ai_best.ipynb : 앙상블, early stopping 등으로 성능을 개선한 코드입니다.

#### (2-3). runnig-flash-objectdetection.ipynb : pytorch-lightning의 flash를 이용해서 객체 인식을 한 코드입니다.

#### (2-4). Yolov5.ipynb : darknet의 yolov5을 이용하여 객체 인식을 한 코드입니다.

## (3). Image Retreival

#### (3-1). metriclearning.ipynb : pytorch-metric-learning 라이브러리를 사용한 Image retreival 코드입니다.
