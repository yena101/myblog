# Find me 

![KakaoTalk_20240620_173026827](https://github.com/yena101/myblog/assets/130446733/81227c85-cbfb-400a-97e0-4ff776b29172)

```
❓  하루에 한 개씩 질문을 받아 답변하며 힐링할 수 있는 앱
```
- 프로젝트 기간 : `2024.05` ~ `2024.06`


# :one: 미리보기

| ![image](https://github.com/yena101/myblog/assets/130446733/5b4eaed5-3537-4f9a-8747-9446e3341610) |![image](https://github.com/yena101/myblog/assets/130446733/b94c0e33-96d7-4d4f-a171-4bb7b4fef59e) | ![image](https://github.com/yena101/myblog/assets/130446733/2c654275-8ae2-4c3b-b3e6-dc83cec56842) |![image](https://github.com/yena101/myblog/assets/130446733/7122bcfd-250a-4488-9196-018827921954) | ![image](https://github.com/yena101/myblog/assets/130446733/97747c85-89ac-4d59-9dad-af3e6a9e137f) 
|-|-|-|-|-|
| !![image](https://github.com/yena101/myblog/assets/130446733/7063076b-a6d9-473b-940b-3b5a9db258ec) | ![image](https://github.com/yena101/myblog/assets/130446733/9ede85dd-bab3-4fad-8644-f5278b817c50) | ![image](https://github.com/yena101/myblog/assets/130446733/9f7603d7-7bc5-49fb-9c54-8ce13b321782) | ![image](https://github.com/yena101/myblog/assets/130446733/40fa8be5-1f81-4e1a-a749-0381aad776d7) | ![image](https://github.com/yena101/myblog/assets/130446733/a69bc940-f963-428c-8c96-fa7f32ed5027) | ![image](https://github.com/yena101/myblog/assets/130446733/c0474818-5489-4c00-9bc6-30ed3bcf0084) | ![image](https://github.com/yena101/myblog/assets/130446733/5f4d5d42-d85b-4a23-b137-93c45fac0049) | ![image](https://github.com/yena101/myblog/assets/130446733/f12fe057-b3a7-41dc-a4ea-03bb92778b9a) | ![image](https://github.com/yena101/myblog/assets/130446733/e36f5656-5a3c-4a34-a1b7-30482bbb86c2) | ![image](https://github.com/yena101/myblog/assets/130446733/cbb215b2-b223-44b1-8490-548f44fea290) | ![image](https://github.com/yena101/myblog/assets/130446733/8f6d15bb-eadf-4afa-887d-b2e63b17e88b) | ![image](https://github.com/yena101/myblog/assets/130446733/90ea556f-23e2-482a-a799-eebfb3ebbbf9) | ![image](https://github.com/yena101/myblog/assets/130446733/a981cf2b-9f6b-4836-8f0f-7338116da3c4) | ![image](https://github.com/yena101/myblog/assets/130446733/15478df6-3651-453d-8dbf-842e1bb396b6) |






















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
 
