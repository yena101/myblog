# Find me 

![Group 242](https://user-images.githubusercontent.com/94586184/230772869-10666a35-d9cd-4246-9a09-58aa45499138.png)
```
❓  하루에 한 개씩 질문을 받아 답변하며 힐링할 수 있는 앱
```
- 프로젝트 기간 : `2024.05` ~ `2024.06`


# :one: 미리보기

| ![sc_1][image](https://github.com/yena101/myblog/assets/130446733/5b4eaed5-3537-4f9a-8747-9446e3341610)| ![image](https://github.com/yena101/myblog/assets/130446733/af37b639-55a5-4895-8ff5-c0013e4bb4dd)
| ![sc_5](https://user-images.githubusercontent.com/94586184/230772785-c817f468-1457-4158-9075-82ab47cade2d.png) | ![sc_7](https://user-images.githubusercontent.com/94586184/230772797-9a5da01c-a981-4209-a379-4a556eff4b99.png) |![sc_8](https://user-images.githubusercontent.com/94586184/230772813-e6301b9b-5ca1-40ab-9e0f-f6f6a8d233da.png) |![sc_9](https://user-images.githubusercontent.com/94586184/230772829-7ec44617-037b-4f46-8b8e-400908203447.png)| ![sc_11](https://user-images.githubusercontent.com/94586184/230772836-f486b8a7-fdad-439b-aeeb-3581748f4fa9.png)| 





# :three: 구조
```
📦 haru_question
 ┣ 📂 app
 ┃ ┗ 📜 haru_db.db
 ┃ ┗ 📂 di
 ┃ ┗ 📂 presentation
 ┃ ┃ ┣ 📂 adapter
 ┃ ┃ ┣ 📂 viewmodel
 ┣ 📂 data
 ┃ ┗ 📂 local
 ┃ ┃ ┣ 📂 dao
 ┃ ┃ ┣ 📂 entity
 ┃ ┃ ┣ 📂 model
 ┃ ┃ ┣ 📜 HaruDatabase.kt
 ┃ ┃ ┣ 📜 Prefs.kt
 ┃ ┗ 📂 repository
 ┣ 📂 domin
 ┃ ┗ 📂 model
 ┃ ┗ 📂 repository
 ┃ ┗ 📂 use_case
```
# :four: 기능
- **하루 질문**
    - 하루에 하나씩 답변을 작성할 수 있는 **```질문```** 을 받음
    - 질문과 관련된 **```명언```** 를 받는다.
    - 사용자가 질문에 답변을 하면 하루모음에 **```추가```** 됨
      
- **하루 모음**
    - 사용자가 답변한 질문의 **``` 목록```** 을 조회 가능함
    - 상세정보를 스크린샷하여 구글 계정으로 **```공유```** 와 **```다운로드```** 가 가능함
      
- **하루 고민**
    - 사용자가 마음속으로 고민을 생각하고 화면을 터치하면 무작위로 **```답변```** 이 나옴.
    - 다시하기 버튼을 통해 다시 답변을 받는게 가능함
      
- **앱 상세** ( -- LIST는 작성해놓았지만 시간이 부족하여 기능은 구현하지 못함. 추후 개발 예정)
   
    - 공유하기를 통하여 다른 사람들과 **```공유```** 가 가능함
    - 스토어가기를 통해서 해당 **```구글 스토어```** 로 이동 가능함
    - 문의하기를 통해서 **```고객 센터```** 에 문의하기가 가능함
    - 초기화를 통해서 지금까지 입력한 데이터를 **```초기화```** 가능함
    - 앱 평가하기를 통해 플레이 스토어로 이동하여 **```리뷰```** 가 가능함
    - 앱 버전을 통해서  **```앱의 버전을```** 확인 할 수 있음
      
    
# :five:  보완해야할 점

 
    - 앱 상세 부분의 내용이 실행되도록 구현
    - 구글이나 카카오톡으로도 로그인할 수 있도록 구현
    - 질문의 개수를 데이터베이스에 더 많이 추가되도록 구현
    - 플레이스토어에 배포하도록 할 예정
 
