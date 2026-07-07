## Tom and Jerry Multi-Label Classifier

EfficientNet-B0-based Multi-Label Image Classification Model

EfficientNet-B0 기반 멀티라벨 이미지 분류 모델


## Overview

This project is an EfficientNet-B0-based multi-label image classification model that predicts the presence of Tom and Jerry in an image using the Kaggle - Tom and Jerry Image Classification dataset.

The project was developed using OpenAI Codex as an AI-assisted coding tool. AI was used to accelerate implementation, while model training, debugging, validation, and performance analysis were carried out by the author.


본 프로젝트는 Kaggle - Tom and Jerry Image Classification 데이터셋을 활용하여 이미지 속 Tom과 Jerry의 존재 여부를 예측하는 EfficientNet-B0 기반 멀티라벨 이미지 분류 모델입니다.

프로젝트는 OpenAI Codex를 활용한 AI-Assisted Development 방식으로 개발되었으며, AI를 코드 작성 보조 도구로 활용하고 모델 학습, 디버깅, 성능 검증 및 결과 분석은 직접 수행했습니다.


## Features

* EfficientNet-B0 Transfer Learning
* Multi-Label Image Classification
* PyTorch-based Training & Inference
* Training / Validation Loss Visualization
* Accuracy Evaluation
* Confusion Matrix Analysis
* Threshold Optimization
* Error Analysis
* Challenge Set Evaluation


## Tech Stack

* Python
* PyTorch
* torchvision
* EfficientNet-B0
* NumPy
* Pandas
* Matplotlib
* OpenCV
* Jupyter Notebook


##  Dataset

This project uses the Tom and Jerry Image Classification dataset provided by Kaggle.

The dataset is not included in this repository due to repository size and dataset licensing.

Please download the dataset from Kaggle and place it in the project directory before training.

본 프로젝트는 Kaggle의 Tom and Jerry Image Classification 데이터셋을 사용합니다.

데이터셋은 저장소 용량 및 라이선스 정책으로 인해 GitHub 저장소에 포함하지 않았습니다.

학습을 위해서는 Kaggle에서 데이터셋을 다운로드하여 프로젝트 디렉터리에 배치해 주세요.


##  AI-Assisted Development

OpenAI Codex was used as an AI-assisted coding tool during development.

AI assisted with implementation and code generation, while the project design, model training, debugging, validation, and result analysis were performed by the author.

본 프로젝트는 OpenAI Codex를 활용하여 개발되었습니다.

AI는 코드 작성과 구현을 보조하는 역할을 수행했으며, 프로젝트 설계, 모델 학습, 디버깅, 성능 검증 및 결과 분석은 직접 수행했습니다.


##  Model Information

Item	Description
Backbone	EfficientNet-B0
Framework	PyTorch
Task	Multi-Label Image Classification
Labels	Tom, Jerry


##  Evaluation

The project includes the following evaluation methods:

- Training / Validation Loss
- Exact Match Accuracy
- Character-wise Accuracy
- Confusion Matrix
- Threshold Optimization
- Error Analysis
- Challenge Set Evaluation

프로젝트에서는 다음과 같은 성능 평가를 수행했습니다.

- 학습 및 검증 손실(Training / Validation Loss)
- Exact Match Accuracy
- 클래스별(Character-wise) 정확도
- Confusion Matrix를 통한 분류 성능 분석
- Threshold 최적화
- 오분류(Error) 사례 분석
- Challenge Set 성능 평가


## Future Improvements

- Compare with additional backbone models (ResNet, ConvNeXt, ViT)
- Improve generalization through additional data augmentation
- Optimize the model for real-time inference
- Refactor the notebook into modular Python scripts

향후에는 다음과 같은 방향으로 프로젝트를 개선할 계획입니다.

- ResNet, ConvNeXt, ViT 등 다양한 Backbone 모델과 성능 비교
- 추가적인 데이터 증강을 통한 일반화 성능 향상
- 실시간 추론을 위한 모델 최적화
- Jupyter Notebook 기반 코드를 모듈화된 Python 프로젝트 구조로 리팩터링


## License

This project was created for **educational and portfolio purposes**.

본 프로젝트는 학습 및 포트폴리오 목적으로 제작되었습니다.

데이터셋의 저작권은 원 저작자 및 Kaggle에 있으며, 본 저장소에는 데이터셋이 포함되어 있지 않습니다.
