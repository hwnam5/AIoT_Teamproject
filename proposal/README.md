# 📊 Projecy Proposal
## 3번재 paper : Dropback
- Dropback 기술을 적용하였을 때랑 기존 pruning 기법 (Dropout)을 적용했을 때 비교
  - Base model : vgg11
  - Dataset : Dog vs Cat (약 500 개의 이미지)
    로컬에서 돌리는 이슈로 dataset의 크기가 작음 => overfitting 문제 있음
  - time : 12M 2S (VGG11 with Dropout) VS 12M 34S (VGG11 with Dropback)

이러한 방식으로 Base모델과 3개의 논문 비교할 예
