### 회고
![download](https://github.com/minkj1992/ai/assets/37536298/c6d5b946-ea8c-4946-ad6c-8371ab0461ab)


1. [x] 자기만의 카메라앱 기능 구현을 완수하였다.
2. [x] 스티커 이미지를 정확한 원본 위치에 반영하였다.
3. [x] 카메라 스티커앱을 다양한 원본이미지에 적용했을 때의 문제점을 체계적으로 분석하였다.
    1. [x] 더 멀리 떨어진 인물들 비교
    2. [x] 더 어두운 인물 비교
    3. [x] 얼굴 각도에 따른 비교
    4. [x] 단체 사진 비교

- 배운 점: hog와 dil을 통해서 facial detection과 cv2를 통한 이미지 조작을 배웠다.
- 아쉬운 점: facial alignment에 대해서 더 공부하고 싶었고, np.where에서 mask된 내용x가 sticker y에 영향을 끼치는 이유를 발견하지 못했다.
- 느낀 점: cv2 공식문서가 형편없다는 것을 깨달았다.
- 어려웠던 점: 없다.

---

### 피어리뷰
(reviewed by 손영철)

🔑 **PRT(Peer Review Template)**

- [O]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요? (완성도)**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
    - 문제를 해결하는 완성된 코드란 프로젝트 루브릭 3개 중 2개, 
    퀘스트 문제 요구조건 등을 지칭
        - 해당 조건을 만족하는 부분의 코드 및 결과물을 캡쳐하여 사진으로 첨부
        - <img width="400px" src="https://github.com/minkj1992/ai/assets/34268173/411c8f2b-0279-4197-adcb-474c751a76a1">
        - <img width="400px" src="https://github.com/minkj1992/ai/assets/34268173/6c356a15-8bb8-4025-a6df-f2e72171cebd">
        - <img width="400px" src="https://github.com/minkj1992/ai/assets/34268173/de9cf5b1-002e-4702-be1b-c38a54d50299">

- [O]  **2. 프로젝트에서 핵심적인 부분에 대한 설명이 주석(닥스트링) 및 마크다운 형태로 잘 기록되어있나요? (설명)**
    - [O]  모델 선정 이유
      - 노드 학습에서 사용된 모델을 그대로 쓰는게 아니라, 더 좋은 성능의 최신의 모델을 찾아서 사용하셨습니다 :+1:
      - ![image](https://github.com/minkj1992/ai/assets/34268173/ed27c87a-033a-4306-aef3-ff78aa671664)
    - [O]  Metrics 선정 이유
      - 이번 프로젝트와 연관된 체크 리스트가 아니므로 넘어가겠습니다.
    - [O]  Loss 선정 이유
      - 이번 프로젝트와 연관된 체크 리스트가 아니므로 넘어가겠습니다.

- [O]  **3. 체크리스트에 해당하는 항목들을 모두 수행하였나요? (문제 해결)**
    - [O]  데이터를 분할하여 프로젝트를 진행했나요? (train, validation, test 데이터로 구분)
      - 이번 프로젝트와 연관된 체크 리스트가 아니므로 넘어가겠습니다.
    - [O]  하이퍼파라미터를 변경해가며 여러 시도를 했나요? (learning rate, dropout rate, unit, batch size, epoch 등)
      - 이번 프로젝트와 연관된 체크 리스트가 아니므로 넘어가겠습니다.
    - [O]  각 실험을 시각화하여 비교하였나요?
      - notebook 내에 각 step 별로 image plot을 통해 결과를 확인할 수 있었습니다.
    - [O]  모든 실험 결과가 기록되었나요?
      - 실험 중간 중간 문제와 이를 해결하기 위한 시도들이 잘 정리되어있습니다 :+1:
      - ![image](https://github.com/minkj1992/ai/assets/34268173/0e8e22b0-4576-4b52-9542-2e974f689791)

- [O]  **4. 프로젝트에 대한 회고가 상세히 기록 되어 있나요? (회고, 정리)**
    - [O]  배운 점
    - [O]  아쉬운 점
    - [O]  느낀 점
    - [O]  어려웠던 점
    - 단순히 주어진 과제를 완수하는데에서 더 나아가 실제 서비스로서 사용된다면 고려해야하고 풀어야할 점들에 고민하고 실험을 통해서 개선해나가는 점이 매우 인상 깊었습니다 💯💯
    - ![image](https://github.com/minkj1992/ai/assets/34268173/0a2ef71b-2b24-4436-9976-bbc89b20329f)
    - ![image](https://github.com/minkj1992/ai/assets/34268173/eac0d3de-e6b2-41c7-8068-dc1a812769c5)

