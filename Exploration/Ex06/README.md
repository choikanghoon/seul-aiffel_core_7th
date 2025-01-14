# [Exploration-EX06] Repository

<Exploration 06. 수식 없이도 이해할 수 있는 ChatGPT와 Stable Diffusion> 모듈에서 진행한 메인퀘스트 레포지토리

---

## 파일 구성

1. EX06.ChatGPT_and_Stable_Diffusion
    - 노드 학습 노트북
2. Project_EX06.Generate_image_with_ControlNet
   - 노드를 학습후 프로젝트 진행 노트북

---

## AIFFEL Campus Online Code Peer Review

- Coder : 이슬
- Reviewr : 김민기


# PRT(Peer Review Template)
- [x]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
    - 문제를 해결하는 완성된 코드란 프로젝트 루브릭 3개 중 2개, 
    퀘스트 문제 요구조건 등을 지칭
        - 해당 조건을 만족하는 코드를 캡쳐해 근거로 첨부
        - 두 가지의 전처리기를 같이 사용한 코드이다.
        ![image](https://github.com/NeatyNut/seul/assets/89675001/dee3aa61-11e7-4d2f-a9e4-887742a549bc)
        ![image](https://github.com/NeatyNut/seul/assets/89675001/b30f785a-ca85-418f-bd62-3a6d2d4cda67)
    
- [x]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드가 무슨 기능을 하는지, 왜 그렇게 짜여진건지, 작동 메커니즘이 뭔지 기술.
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부합니다.
        - 하이퍼 파라미터에 관한 설명이 좋았다.
        ![image](https://github.com/NeatyNut/seul/assets/89675001/1d821189-8352-425f-aef7-886858dfee86)

        
- [x]  **3. 에러가 난 부분을 디버깅하여 문제를 “해결한 기록을 남겼거나” 
”새로운 시도 또는 추가 실험을 수행”해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 문제에서 요구하는 조건에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부합니다.
        - CUDA 메모리 이슈가 발생하였다. kernel restart로 대응하셨다.
          ![image](https://github.com/NeatyNut/seul/assets/89675001/2d374d49-1f7f-4fbe-b43c-d973eefb5da4)
          ![image](https://github.com/NeatyNut/seul/assets/89675001/13985072-d030-467c-aa23-e8b8a8241ff5)

        
- [x]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부합니다.
        - 이해 안되는 부분을 잘 서술해주셨다.
          ![image](https://github.com/NeatyNut/seul/assets/89675001/3bb3e99d-3f0d-4ba1-9ac8-9a5628992418)

- [x]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 하드코딩을 하지않고 함수화, 모듈화가 가능한 부분은 함수를 만들거나 클래스로 짰는지
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화했는지
        - 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부합니다.
        - 저장할때 간결하게 os라이브러리를 잘 활용하였다.
          ![image](https://github.com/NeatyNut/seul/assets/89675001/baf32a28-e19f-4a76-88a1-8047a5446203)


# 참고 링크 및 코드 개선
```
# 코드 리뷰 시 참고한 링크가 있다면 링크와 간략한 설명을 첨부합니다.
# 코드 리뷰를 통해 개선한 코드가 있다면 코드와 간략한 설명을 첨부합니다.
```
