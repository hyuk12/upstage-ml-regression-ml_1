# Title (Please modify the title)
## Team

| ![최해혁](https://avatars.githubusercontent.com/u/156163982?v=4) | ![이재윤](https://avatars.githubusercontent.com/u/156163982?v=4) | ![박준영](https://avatars.githubusercontent.com/u/156163982?v=4) | ![이동건](https://avatars.githubusercontent.com/u/156163982?v=4) |
|:-------------------------------------------------------------:|:-------------------------------------------------------------:|:-------------------------------------------------------------:|:-------------------------------------------------------------:|
|            [최해혁](https://github.com/UpstageAILab)             |            [이재윤](https://github.com/UpstageAILab)             |            [박준영](https://github.com/UpstageAILab)             |            [이동건](https://github.com/UpstageAILab)             |            [오패캠](https://github.com/UpstageAILab)             |
|                           팀장, 담당 역할                           |                             담당 역할                             |                             담당 역할                             |                             담당 역할                             |

## 0. Overview
### Environment
- Python 3.10+
- Jupyter Notebook
- GPU 서버 환경 (대회 제공)

### Requirements
- pandas
- numpy
- scikit-learn
- lightgbm
- xgboost
- matplotlib
- seaborn

## 1. Competiton Info

### Overview

서울시 아파트 실거래가를 예측하는 회귀 모델 개발 대회입니다. 국토교통부 아파트 실거래가 데이터와 서울시 지하철역/버스정류장 정보를 활용하여 정확한 부동산 가격 예측 모델을 구축하는 것이 목표입니다.

**주요 특징:**
- 대회 유형: Regression (회귀)
- 평가 지표: RMSE (Root Mean Squared Error)
- 예측 대상: 9,272개 아파트의 매매 실거래가
- 제공 데이터: 국토교통부 실거래가 데이터, 지하철역 정보, 버스정류장 정보

### Timeline

- 2024년 9월 1일 (월) 10:00 - 대회 시작
- 2024년 9월 3일 (수) 10:00 - 팀 병합 마감
- 2024년 9월 11일 (목) 19:00 - 최종 제출 마감
- 2024년 10월 30일 (목) 16:00 - GPU 서버 운영 종료

## 2. Components

### Directory

- _Insert your directory structure_

e.g.
```
├── notebooks
│   ├── baseline
│   │   └── baseline_notebook.ipynb     # 베이스라인 코드
│   ├── donggun
│   │   └── donggun_analysis.ipynb      # 동건 팀원 노트북
│   ├── haehyuk
│   │   └── haehyuk_modeling.ipynb      # 해혁 팀원 노트북
│   ├── jaeyun
│   │   └── jaeyun_feature.ipynb        # 재윤 팀원 피처 노트북
│   ├── junyoung
│   │   └── junyoung_ensemble.ipynb     # 준영 팀원 노트북
│   └── requirements.txt                # 프로젝트 의존성 패키지 목록
├── output
│   ├── donggun
│   │   └── submission_donggun.csv      # 동건 팀원 제출 파일
│   ├── haehyuk
│   │   └── submission_haehyuk.csv      # 해혁 팀원 제출 파일
│   ├── jaeyun
│   │   └── submission_jaeyun.csv       # 재윤 팀원 제출 파일
│   └── junyoung
│       └── submission_junyoung.csv     # 준영 팀원 제출 파일
└── src
└── .gitkeep                        # 최종 통합 코드 저장 공간
```

## 3. Data descrption

### Dataset overview

대회에서 제공되는 데이터셋 설명:

1. **아파트 실거래가 데이터 (국토교통부)**
   - 아파트 위치 정보 (구, 동, 번지)
   - 아파트 정보 (면적, 건축연도, 층수 등)
   - 거래 정보 (거래일, 거래금액 등)

2. **지하철역 정보 (서울시)**
   - 지하철역 위치 및 노선 정보
   - 교통 접근성 관련 데이터

3. **버스정류장 정보 (서울시)**
   - 버스정류장 위치 정보
   - 대중교통 편의성 관련 데이터

4. **평가 데이터**
   - 예측해야 할 9,272개 아파트 정보

### EDA

- _Describe your EDA process and step-by-step conclusion_

### Data Processing

- _Describe data processing process (e.g. Data Labeling, Data Cleaning..)_

## 4. Modeling

### Model descrition

- _Write model information and why your select this model_

### Modeling Process

- _Write model train and test process with capture_

## 5. Result

### Leader Board

- _Insert Leader Board Capture_
- _Write rank and score_

### Presentation

- _Insert your presentaion file(pdf) link_

## etc

### Meeting Log

- _Insert your meeting log link like Notion or Google Docs_

### Reference

- _Insert related reference_
