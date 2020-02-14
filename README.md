# Protein_Secondary_Structure_Prediction

## Purpose
* 정확도를 높이고 손실률을 낮추는 것
* 새로운 아미노산 시퀀스 데이터를 테스트해 예측값과 실제 구조 값 비교

## Reason
* 단백질은 중요한 기능이 있다.
* 2차 구조의 형태에 따라 단백질의 기능이 달라진다.
* 바이오적인 측면에서는 2차 구조 예측 실험이 굉장히 비싸다.
* 3차 구조를 예측하기 전에 2차 구조를 예측해 아미노산 시퀀스를 분석한다.

## Code introduction
* Language : Python
* Editer : Jupyter notebook, Jupyter Lab, Google Colab
* Framework : Tensorflow 1.14, Keras 2.1
* GPU Server : GTX Geforce 2080Ti(UNLV's Lab), Tesla K80(Google Colab)
* model : RNN, GRU, BLSTM
