# 삼성 DS-KAIST AI Expert 프로그램 
## Transfer, Multi-task learning

실습 일시: 2020년 7월 22/29일 (수), 13:30 - 17:30

담당 조교: 탁지훈 (jihoontack@kaist.ac.kr), 모상우 (swmo@kaist.ac.kr)

### Introduction

첨부된 `transfer_learning.ipynb`, `multitask_learning.ipynb` 파일을 확인하세요.

### Environment setting

방법1: 업로드 되어 있는 `env.yml`를 사용하여 다음과 같이 설치를 진행합니다.

```
conda activate
conda env create -f env.yml
```

방법2: 다음 코드를 순차적으로 실행하여, 가상환경에 필요한 package를 설치합니다.

```
conda activate
conda create -y -n <환경 이름, 예시) transfer_0722> python=3.7
conda activate <환경 이름>

pip install jupyterlab
pip install matplotlib
pip install scipy
pip install numpy==1.16
pip install tensorflow-gpu==1.14
```
