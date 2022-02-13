# UNET-tf2

> 딥러닝 논문 구현 프로젝트 파일 구조
#### 1. train.py : 모델 class를 인스턴스로 선언하고 For-loop를 돌면서 gradient descent를 수행하면서 파라미터를 업데이트하는 로직
#### 2. evaluate.py / test.py : Training된 파라미터를 불러와서 evaluation이나 test/inference를 진행하는 로직
#### 3. model.py : Keras Subclassing 형태의 모델 구조 class 정의
#### 4. loss.py : 모델의 Loss Function을 정의
#### 5. dataset.py : 데이터 전처리 및 batch 단위로 묶는 로직
#### 6. utils.py : 딥러닝 메인 로직 외에 유틸리티성 기능들을 모아 놓은 로직