# 🎮 Opportunity Cost
![123](https://github.com/cho-stone/Portfolio/assets/74195857/3a341f65-e0ee-4d67-8bcc-0af6e2731944)

## 🗒 프로젝트 개요
### 1. 제작기간
> 2017.9 ~ 2017.11
### 2. 참여인원 및 역할
> |이름|역할|
> |:------:|:---:|
> |[배광호](https://github.com/kangho1117)|배경 수집|
> | |캐릭터 디자인|
> | |소설, 코드 검토 및 수정|
> |[조석진](https://github.com/cho-stone)|음향/효과음 수집|
> | |스토리 구성|
> | |프로그래밍|
### 3. 사용 언어 및 도구
[TyranoBuilder Visual Novel Studio](https://tyranobuilder.com/)
 * TyranoBuilder는 비주얼 노벨 게임엔진입니다. 드래그 앤 드롭 방식으로 쉽게 비주얼노벨을 제작할 수 있습니다.  
 * 자체 스크립트(Tyrano Script)로 좀 더 세부적인 기능을 구현할 수 있습니다.
### 4. 장르
> __비주얼 노벨, 로맨스, 청춘__
<br>

## 📖 스토리
> 2년 전, 공원 벤치에 앉아있던 한 소녀를 마주한 은우.
> 
> 그녀에게 이끌려 말을 걸었고 친해지게 되었다.
> 
> 그녀 덕분에 은우는 게임 개발자를 꿈꾸게 되었고
> 
> 은우는 그녀와 함께 고등학교에서 게임 개발 동아리를 만들게 되는데...
> 
> 게임 개발자의 꿈을 꾸게 된 은우는 과연 동아리를 무사히 운영할 수 있을까?
<br>

## ⚙ 게임 진행 방식
![opcg](https://github.com/cho-stone/OPC/assets/74195857/aa9cc507-a175-4596-a173-082e6f1852a2)
* 기본적으로 마우스 클릭을 통해 텍스트를 넘기며 이야기를 진행합니다.
<br>

![1231](https://github.com/cho-stone/OPC/assets/74195857/d19cea23-2a1f-4c44-9008-a4346acee396)
* 선택지가 나오면 둘 중 하나를 골라 이야기를 진행합니다.
* 선택에 따라 결말이 달라집니다.

## 💻 주요 구현 내용
![image](https://github.com/cho-stone/OPC/assets/74195857/198c34bb-34f2-4182-be0f-8ae51480c343)  
> 위와 같이 프로그래밍은 드래그 앤 드롭 방식으로 진행됩니다.
<br>

🚨 비주얼 노벨에서 중요한 분기점은 아래와 같이 구현됩니다. 🚨
<br>

![image](https://github.com/cho-stone/OPC/assets/74195857/25ed6946-335c-4bf4-93c1-37307e690d74)  
* 굿 엔딩과 베드 엔딩을 선택지에 따라 가르기 위해 변수를 선언하여 줍니다.
* 그다음 아래에 분기점을 설정합니다

![image](https://github.com/cho-stone/OPC/assets/74195857/1b0f52b2-252b-4430-a287-6ad39a7f5639)
![image](https://github.com/cho-stone/OPC/assets/74195857/e19aa2bf-9517-4796-b092-e73d24bf61d8)
![image](https://github.com/cho-stone/OPC/assets/74195857/4d554156-8f89-4448-a230-eed9bfdef1dd)  
* 분기점을 선택하면 Label 블록을 통해 각 선택에 맞는 상황으로 이동하게 됩니다.
* 다음 변수를 상황에 맞게 연산하여 줍니다.
* 각 상황 끝에 Jump 블록을 놓아 다음 씬으로 넘어가도록 합니다.

![image](https://github.com/cho-stone/OPC/assets/74195857/1e9c7ef7-9055-4737-b5cc-5495f52091d9)
* 마지막 분기점에서는 엔딩을 가르기 위해 조건문으로 적합한 엔딩을 정해주었습니다.
<br>

## 🔗 Download
https://drive.google.com/file/d/19to6vOYl8tbgSUnF5U2b0mRGRJIUxsQ7/view?usp=drive_link  
> 압축파일을 풀고 OPC.exe를 실행하여 주세요.
