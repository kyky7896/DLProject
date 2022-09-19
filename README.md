
# 딥러닝 프로젝트 [****Chest X-Ray Images (Pneumonia) Project**** ] 
흉부 방사선 검사 영상을 학습한 데이터 기반으로 입력 영상에서 특징 추출하여 폐렴을 추출한다
<br>
#### 노션주소 : https://www.notion.so/2122b37bb500476d8d92abf9150b4bc8 🎈🎈

[참고 자료 링크]
| Name	|  링크주소 | Tags |
- VGGnet	https://inhovation97.tistory.com/32	VGG, 하이퍼파라메타
- Effcientnet-b0	https://catalog.ngc.nvidia.com/orgs/nvidia/models/efficientnet_b0_pyt_amp	Efficientnet, 하이퍼파라메타
- Resnet	https://myrtle.ai/learn/how-to-train-your-resnet-2-mini-batches/	ResNet, 하이퍼파라메타
- Efficientnet	`https://visionhong.tistory.com/19	Efficientnet
- AdamW	https://hiddenbeginner.github.io/deeplearning/paperreview/2019/12/29/paper_review_AdamW.html	AdamW
![image](https://user-images.githubusercontent.com/77670592/190893365-9cf8a4fb-9b6b-4697-b142-7057895235f5.png)



# ****Chest X-Ray Images (Pneumonia)****


## 1. 목표

 - 다양한 CNN 모델을 이해한다
 - 성능을 올리기 위해 옵티마이저, 중요 하이퍼 파라미터를 이해한다.
 - 런더월드 구성원들의 실력 향상을 위해!  
 - 흉부 방사선 검사 영상 데이터를 다양한 모델에 학습 시켜 최고의 성능을 내자!!
 - 불화, 불수, 불목, 불금을 위해!!!

## 2. 진행과정

![image](https://user-images.githubusercontent.com/77670592/190893224-1ae0a857-2287-4b25-9659-e5762701d331.png)
![image](https://user-images.githubusercontent.com/77670592/190893250-b0a3e7e8-1cb3-4bdd-876b-f1704cf5f362.png)
![image](https://user-images.githubusercontent.com/77670592/190893264-a71a08a7-17f8-4933-97b6-79792a7def97.png)
![image](https://user-images.githubusercontent.com/77670592/190893280-ade1d007-718c-4b2b-b624-0e29545457c3.png)

## 3. 질문

 Q1)  어떤 옵티마이저, 로스 함수를 사용했는지? 

         로스함수: CrossEntropyLoss( ), optimizer: Adam( ), SGD(), AdamW()

 Q2) 처음 시도했던 Network Architecture는 어떤 종류인지? 

        Alexnet, VGG16, googlenet, Resnet50
 

 Q3) 이후 시도해봤던 Network들은 무엇인지?  

        VGG19, EfficientNet, Resnet152
 

 Q4) 과대 적합을 피하기 위해 했던 작업들은 무엇인지? 

       early stopping
  

 Q5) 중요 하이퍼 파리미터(batch size, epoch수, learning rate)은 어떻게 결정했는지? 

       기존 가이드라인, 논문 참고 하여 돌려봄

## 4. 소감

1. 황혜리 : 배려와 공감, 그리고 이해. 행복한 시간이었고 딥러닝 놓치지 않을고얌! , 아쉬웠던 점은 모델에 하이퍼 파라미터들을 여러가지로 구현해서 시각화 하여 어떤것이 좋을지 확인하지 못했던점이 아쉬워요!. 다음에는 꼭 해보도록 하겠습니다 
2. 이경영 : 딥러닝 포기하고 싶었지만 안 할수 있었던 원동력은 좋은 팀원들 덕분이었던것 같아요. 마지막까지 값을 확인하고 싶었으나… GPU사용량이 초과되어서 못돌린게 아쉬웠습니다.  서로의 이해와 배려가 가득찬 프로젝트였어요 다들 고생하셨고 감사합니다 !
3. 김보람 : 좋은 기회로 프로젝트를 같이 하게 되어 너무나 좋았습니다. 팀원 모두 딥러닝에 대한 기초 지식이 없는 상태에서 강의만 듣고 함께 프로젝트를 한다는 게 어려울 수 있지만, 모르는 건 함께, 다 같이 찾아보고 논문 참고해가며 값 조정하고 그랬던 부분이 제게는 참 값진 시간이었습니다. 이렇게 같이 할 수 있는 기회가 정규 과정 속에서 또 없을 수도 있지만, 단합도 잘되고 서로를 배려하며 했던 부분에 인상이 남아 나중에 따로라도 프로젝트를 한번 더 했으면 좋겠습니다.
4. 김재희 :  다양한! 딥러닝 모델 들에 대해서 학습할 수 있는 기회였고, 포기할 뻔한 분야를 프로젝트와 팀원들 덕분에 다시 끌고갈 수 있게 되었습니다. 더 좋은 성능을 위해서 여러 시도를 하고, 더 좋은 성능이 나왔을 때 얻는 쾌감이 무엇인지도 느낄 수 있었습니다!  실력!을 올릴 수 있는 좋은 기회였다고 생각합니다 ㅎㅎ 다들 너무 고생하셨고 감사합니다 ~
