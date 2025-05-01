# 👀 VOIM 

## 👨‍👩‍👧‍👦 Members
<div align="center">
  
  | **박수민** | **최호** | **임연지** | **주정빈** |
  | :--------: | :------: | :--------: | :--------: |
  | <a href="https://github.com/psm1st"><img src="https://avatars.githubusercontent.com/u/145013061?v=4" width="150"> | <a href="https://github.com/choihooo"><img src="https://avatars.githubusercontent.com/u/67588757?v=4" width="150"> | <a href="https://github.com/yeonjy"><img src="https://avatars.githubusercontent.com/u/81320703?v=4" width="150"> | <a href="https://github.com/zyovn"><img src="https://avatars.githubusercontent.com/u/166782961?v=4" width="150"> | 
  | `frontend` | `frontend` | `backend` | `backend` |
  
</div>

## 📂 ERD
<details>
<summary> ERD </summary>
<img src="https://github.com/user-attachments/assets/21a55374-3eb2-4369-864b-e71d7a7b3fe0" width="300" alt="image" />
</details>

## 📜 API 명세서
[VOIM API 명세서](https://voim.store/api/swagger-ui/index.html#/)

## 🛠️ System Architecture
![Image](https://github.com/user-attachments/assets/53748bbc-c56c-49dc-ac57-2584ac687067)

## ❓ 질문 사항
### 💚 프론트엔드
1. 현재 컴포넌트 구조나 디렉토리 구조에 개선할 점이 있다면 말씀해주세요. 
2. 테스트 코드를 작성하면서 개발하고 있는데 테스트 코드를 먼저 작성하고 거기에 맞춰 개발을 해야하는지 컴포넌트를 먼저 구현하고 테스트 코드를 작성해야할지 잘 모르겠습니다. 어떤 전략을 사용하는 것이 좋을까요?
3. 현재 Webpack 설정 구조가 유지보수나 현재 개발 상황에 적절한가요?

### 💙 백엔드
1. 리뷰 요약이나 이미지 분석에 open ai, clova x를 활용하고 있습니다. 이를 매번 호출할 시, 비용 문제가 발생해 DB에 저장해놓으려고 하는데 redis를 쓰는 게 좋을지 MySQL을 쓰는 게 좋을 지 여쭙고 싶습니다.
2. 현재는 별도의 회원 가입 없이 사용자 정보를 로컬에 저장해놓는 형태로 구현했습니다. 추후, 확장성을 고려하면 회원가입 및 로그인 기능을 구현하는 게 좋을 지 여쭙고 싶습니다.
3. 현재 외부 API를 사용하는 부분이 많은데, 어떻게 해야 외부 api를 효율적으로 관리할 수 있을지 궁금합니다.
