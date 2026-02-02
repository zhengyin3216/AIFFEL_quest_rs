# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 황소리
- 리뷰어 : 정정채


# PRT(Peer Review Template)
- [ ]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 감성분석에 Sentence Piece Tokenizer를 잘 활용하였음 
    - 여러 모델(LSTM, TextCNN 등)을 적용하여 어떤 모델이 감성분석에 적합한지 도출했음
    - <img width="740" height="231" alt="image" src="https://github.com/user-attachments/assets/c450fc97-398f-4710-9103-5c5d06c323f1" />

    
- [ ]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - Early Stopping check를 넣어서 불필요한 학습을 줄였음  
      <img width="582" height="204" alt="image" src="https://github.com/user-attachments/assets/7eb2a006-59eb-4713-9e13-86a8dc7b5c6d" />
    - 데이터 전처리를 통해 노이즈를 제거함
      <img width="497" height="60" alt="image" src="https://github.com/user-attachments/assets/ef1f71a1-144e-4f64-8aa6-68d9a6bfdc68" />


        
- [ ]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 과제 수행 과정에서 큰 오류 없이 전체 코드가 안정적으로 실행되어, 별도의 디버깅 기록은 남기지 않았음
    - 다만, 기본 과제 요구사항 외에도 LSTM, TextCNN 등 다양한 모델을 추가로 적용해보며 성능을 비교하려는 시도가 인상적
    - 이러한 실험 과정과 결과를 조금 더 구체적으로 기록한다면, 향후 학습 과정을 정리하는 데 도움이 될 것으로 보임
        
- [ ]  **4. 회고를 잘 작성했나요?**
    - 과제 수행 결과에 대한 회고나 학습 과정에 대한 정리는 비교적 간단하게 이루어졌음
    - 향후 배운 점이나 어려웠던 부분, 개선하고 싶은 점 등을 함께 정리한다면 학습 효과가 더욱 높아질 것으로 보임
        
- [ ]  **5. 코드가 간결하고 효율적인가요?**
    - 코드가 이해하기 쉽게 잘 작성되었음
    - 코드의 각 부분이 어떤 부분인지 명확히 제목을 적음  
      <img width="472" height="653" alt="image" src="https://github.com/user-attachments/assets/bcf87f16-150f-4ba4-b293-69d8418c9bbc" />


# 회고(참고 링크 및 코드 개선)
- 제가 놓쳤던 데이터 전처리부분과 Early stopping 기법을 적용한 부분을 제 과제에 보완하면 좋겠다는 생각을 했습니다.
- 이전 과제에서 작성했던 코드를 적절히 재활용하여 이번 프로젝트에 효과적으로 적용한 점이 인상적이었습니다. 기존 코드를 잘 이해하고, 현재 과제에 맞게 확장하여 활용한 점에서 학습 내용을 잘 이해하고 있다는 인상을 받았습니다.
