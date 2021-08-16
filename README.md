# COVID19-Classification

- 진행날짜 : 2020.06.20 ~ 2020.07.06


- 그동안 Vision관련 논문 읽은 것을 바탕으로 실제 데이터에 적용해보고, 코드로 구현해봤다!
- 옛날 노트북인 core i3로 플젝을 진행했는데 계속 Memory Error가 떴다.
- 코랩으로 갈아탔다. Colab 처음 경험해봤는데 GPU는 신세계였다.
- 이미지 데이터라서 그런지 몰라도 Neaural Net은 컴퓨터 성능이 가장 중요한 것 같다.

</br>
</br>



 # 느낀 점
 > 우선 논문마다, 사이트 마다 용어가 달랐다. 내가 읽은 mobile net과 effecient net 같은 경우, filter라고 되어있는 부분이 어떤 사이트에서는 window라고도 하고, 어떤 곳에서는 kernel이라고 표현했다. 그 용어가 똑같은 개념이라는 것을 인식하기 까지 굉장히 헷갈렸다.
 
 **덧,**
 + Efficient Net
 - Overfitting 발생
 - 아마도 확진자 데이터가 적어서 Auto-Augmentation 을 진행했는데, 이것이 원인이 된 것 같다.

+ VGG, DenseNet, WideResNet 에서는 EffNet만큼의 오버피팅 발생하지 않음.
 - EfficientNet이 하이퍼 파라미터의 수가 더 적어서 오퍼피팅 발생 가능성을 더 높이는 것이 아닌가.. 라는 생각이 든다!
