# Find me 

![Group 242](https://user-images.githubusercontent.com/94586184/230772869-10666a35-d9cd-4246-9a09-58aa45499138.png)
```
❓  하루에 한 개씩 질문을 받아 답변하며 힐링할 수 있는 앱
```
- 프로젝트 기간 : `2022.08` ~ `2022.10`


  <a href="https://play.google.com/store/apps/details?id=com.colddelight.haru_question"><img src="https://img.shields.io/badge/Goolge Play-414141?style=flat&logo=googleplay&logoColor=white&link=https://play.google.com/store/apps/details?id=com.colddelight.haru_question"/></a>   <a href="https://strong-marlin-f95.notion.site/SRS-a1c9777dfa4b485195dafb0dcc8d7d9d"><img src="https://img.shields.io/badge/SRS-414141?style=flat&logo=readthedocs&logoColor=white&link=https://strong-marlin-f95.notion.site/SRS-a1c9777dfa4b485195dafb0dcc8d7d9d"/></a>
  
# :one: 미리보기

| ![sc_12](https://user-images.githubusercontent.com/94586184/230772664-7a97f9d5-26e3-482f-ba4b-05366f0648e4.png)| ![sc_1](https://user-images.githubusercontent.com/94586184/230772672-9bd7733b-7f96-40ee-bd1c-a85109b55852.png)|![sc_2](https://user-images.githubusercontent.com/94586184/230772676-0b55067a-52b4-4b05-8a05-3036e91ec8fb.png) | ![sc_6](https://user-images.githubusercontent.com/94586184/230772685-073df27c-0d9b-417d-8f6c-157100ab1320.png)|![sc_3](https://user-images.githubusercontent.com/94586184/230772750-bbeef7db-2c87-4de7-97db-dafacf385d24.png) |



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
    - 하루에 하나씩 답변을 작성할 수 있는 **```질문```** 을 받는다.
    - 질문과 관련된 **```명언```** 를 받는다.
    - 사용자가 질문에 답변을 하면 하루모음에 **```추가```** 된다.
      
- **하루 모음**
    - 사용자가 답변한 질문의 **``` 목록```** 을 조회 가능하다.
    - 상세정보를 스크린샷하여 구글 계정으로 **```공유```** 와 **```다운로드```** 가 가능하다.
      
- **하루 고민**
    - 사용자가 마음속으로 고민을 생각하고 화면을 터치하면 무작위로 **```답변```** 이 나온다.
    - 다시하기 버튼을 통해 다시 답변을 받는게 가능하다.
      
- **앱 상세** ( -- LIST는 작성해놓았지만 시간이 부족하여 기능은 구현하지 못함. 추후 개발 예정)
   
    - 공유하기를 통하여 다른 사람들과 **```공유```** 가 가능하다.
    - 스토어가기를 통해서 해당 **```구글 스토어```** 로 이동 가능하다.
    - 문의하기를 통해서 **```고객 센터```** 에 문의하기가 가능하다.
    - 초기화를 통해서 지금까지 입력한 데이터를 **```초기화```** 가능하다.
    - 앱 평가하기를 통해 플레이 스토어로 이동하여 **```리뷰```** 가 가능하다.
    - 앱 버전을 통해서  **```앱의 버전을```** 확인 할 수 있다.
      
    
    
