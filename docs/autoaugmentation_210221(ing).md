# paper 정리 
## autoaugment : learning augmentation strategies from data

### 1. abstract 

- 이미지 분류의 정확성을 높이기 위한 효과적인 방법으로 데이터 증강기술 제안 
- auto augmentation은 딥러닝 기술을 이용하여 자동으로 데이터 증강을 하는 것 
- CIFAR-10,100, SVHN, ImageNet 으로 테스트 
- 기존 방법보다 ~1%정도 정확도 향상 

### 2. introduction 

- dataset에따라 효과적인 데이터 증강 기술이 다르므로 수많은 경우의 수에대해 학습을 통해 자동으로 적합한 증강기술을 찾아내는 것이 필요
- 가능한 augmentation operation : translation, rotation, color normalization, shear ...)

