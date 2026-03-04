# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 황소리
- 리뷰어 : 정정채


# PRT(Peer Review Template)
- [ ]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - Simplebaseline 모델을 잘 설계함  
      <img width="309" height="381" alt="image" src="https://github.com/user-attachments/assets/213aa06c-bd45-43ef-9e6c-e2b1a2099ed2" />
    - Hourglass와 Simplebaseline 두 모델을 잘 비교함  
      <img width="406" height="255" alt="image" src="https://github.com/user-attachments/assets/d6a3d28f-96a4-4861-bb48-c374421b42d1" />

- [ ]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 두 모델을 비교하기 위한 지표로 PCK(Percentage of Correct Keypoints)을 사용한 것이 인상적이었음
    - PCK를 계산하기 위한 코드를 재사용성 있게 잘 설계함  
      <img width="613" height="708" alt="image" src="https://github.com/user-attachments/assets/9204cbfe-86ed-42e2-936b-5937abcc8c68" />
        
- [ ]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - Out of Memory 이슈에 대응하기 위해 GPU 메모리를 정리하는 부분을 추가함  
      <img width="590" height="208" alt="image" src="https://github.com/user-attachments/assets/6dc33668-0f45-486b-af94-733166745d2f" />

        
- [ ]  **4. 회고를 잘 작성했나요?**
    - 두 모델의 정성적인 부분과 정량적인 부분을 모두 확인하였음
    - Loss 비교 시 절대값이 꼭 중요한 건 아닌 것을 확인함  
      <img width="397" height="208" alt="image" src="https://github.com/user-attachments/assets/0413c897-4d68-4d45-8f53-43d8616e3b42" />



- [ ]  **5. 코드가 간결하고 효율적인가요?**
    - 시각화 모듈을 함수화하여 재사용성 있게 설계함  
      <img width="333" height="225" alt="image" src="https://github.com/user-attachments/assets/05b954b2-5faf-4a46-af5a-b0da68bdf619" />



# 회고(참고 링크 및 코드 개선)
```
- 정량적 지표로 PCK를 활용한 점이 인상적이었음
- 학습이 잘 되는지 확인하기 위해 시각화를 통해 잘 보여주었음
- Loss가 꼭 절대값의 크기가 중요한 것이 아니라 학습의 경향성을 봐야한다는 인사이트를 얻게해줬음 
```
