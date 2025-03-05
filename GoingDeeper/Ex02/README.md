# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 김인수
- 리뷰어 : 김민호


# PRT(Peer Review Template)
- [X]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - ![image](https://github.com/user-attachments/assets/b7fd6a48-a908-4531-a61c-5fc6c2b4534e)
        - ![image](https://github.com/user-attachments/assets/7dc09929-7506-497b-9456-bc5611e99241)
        - CAM과 Grad-CAM 모두 구현 후 Activation Map을 시각화 하셨다.
        - ![image](https://github.com/user-attachments/assets/685e03d1-ba78-489c-a2ee-06ca9d69b702)
        - 원본 이미지와의 오버랩도 진행하셨다
        - ![image](https://github.com/user-attachments/assets/dc9ff385-b6d0-4886-b078-9030c122d1de)
        - 마지막으로 iou 측정까지 루브릭에서 요구한 모든 사항을 잘 진행해 주셨다.

    
- [X]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - ![image](https://github.com/user-attachments/assets/523299f0-6a82-42f3-a107-b3a5aed7b23a)
        - grad-cam을 위한 함수를 정의할 때, CAM과 다른 부분이 어떤지 반영하여 주석을 작성하셔서 이해하기 좋았다.
        
- [X]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - ![image](https://github.com/user-attachments/assets/b5d17533-4fc0-48dc-b8f2-063da6809522)
        - grad-cam에서 컨볼루션 레이어 별로 따로 만든 Activation Map을 시각화하는 추가 실험도 진행하셨다.

        
- [X]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - ![image](https://github.com/user-attachments/assets/e9dc5c94-e386-4d79-96be-84d63c07fc94)
        - 회고 역시 잘 작성해주셨다.
        - 코드 리뷰 시 어떤 추가 실험을 더 진행하고 싶은지에 대한 언급도 해주셨다.

        
- [X]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - ![image](https://github.com/user-attachments/assets/317391bd-1f66-4b6b-9ffd-9e424ab39ac6)
        - 전체적으로 함수화가 잘 되어있어, 간결하고 효율적이게 작성해주셨다.



# 회고(참고 링크 및 코드 개선)
```
서로 뽑힌 샘플 이미지가 달라서, 같은 실험이지만 다른 회고와 결론이 나오는 부분이 흥미로웠다. grad-cam과 cam이 왜 다른 결과를 내게 하는지에
대한 결론이 회고에 정리가 잘 되어있어 리뷰하면서 학습에 도움을 받았다.
코드 리뷰 시간에 퍼실님께서 언급해주신 추가 실험 내용도 공유해주셔서, 퀘스트 이후에 좀 더 실험을 진행하고 싶어졌다.
```
