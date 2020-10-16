# DNN 음성 합성기 (음색+감정) 오픈소스
## 소개
+ FastSpeech 기반 다화자 다감정 end-to-end 음성 합성 시스템
  + 모델 모식도 (훈련)

## Demo 실행 예시
1. 실시간 TTS Demo 실행 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/googlecolab/colabtools/blob/master/notebooks/colab-github-demo.ipynb)
2. Install & Setup 섹션 실행 (3~4분 소요)
3. Synthesis 섹션 실행
```
문장을 입력해주세요.
> 안녕하세요.
화자 번호를 입력해주세요. *Option* 여자: 0~4, 10~14 / 남자: 5~9, 15~19
> 0
감정을 입력해주세요. *Option* neutral, happy, sad, angry
> neutral
감정 세기를 입력해주세요. *Option* 0.5(약하게), 1.0(적당하게), 2.0(세게)
> 1.0
RTF=0.030897
```
4. [합성음](https://drive.google.com/file/d/1DCNd3HFNW06qS3Xno75o7tVBlycFbbfq/view?usp=sharing) 확인

## Reference

