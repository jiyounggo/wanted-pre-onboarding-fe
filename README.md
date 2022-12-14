# ✍️test 원티드 프리온보딩 프론트엔드 - 선발 과제


<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=React&logoColor=white"/> <img src="https://img.shields.io/badge/JavaScript-FDB515?style=flat-square&logo=JavaScript&logoColor=white"/> <img src="https://img.shields.io/badge/emotion-ff69b4"/>

## 실행방법

```c
npm install
npm start
```

## 프로젝트 설명

- 본 프로젝트는 Todo List 할일 목록 App입니다.
- 회원가입과 로그인 기능이 구현되어 있습니다.
- 투두 리스트 게시글의 CRUD 기능이 구현되어 있습니다.

## 💻데모영상

### 로그인/회원가입

| 로그인                                                                                                            | 회원가입                                                                                                            | 로그아웃                                                                                                            |
| ----------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------- |
| ![로그인](https://user-images.githubusercontent.com/103088450/185093711-702e2454-f841-4fbd-982d-86072ceb178f.gif) | ![회원가입](https://user-images.githubusercontent.com/103088450/185096348-cdee149f-6032-40db-b823-72bd6704c6ce.gif) | ![로그아웃](https://user-images.githubusercontent.com/103088450/185096483-04a2bc5a-efcf-4dd1-9c5e-fc699b4b0bef.gif) |

### 투두 리스트

| 글쓰기                                                                                                             | 글수정                                                                                                            | 글삭제                                                                                                             |
| ------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------ |
| ![글 추가](https://user-images.githubusercontent.com/103088450/185098289-31afbce7-e943-4ac6-8d05-863a5184c6e4.gif) | ![글수정](https://user-images.githubusercontent.com/103088450/185159276-1fdb7f6b-5e55-433d-8cb6-a8e58b637840.gif) | ![글 삭제](https://user-images.githubusercontent.com/103088450/185098330-ac3749c2-5f34-4021-a7e8-d90d476f1a84.gif) |

## 구현 기능

- Login / SignUp

  - 로그인,회원가입을 별도의 경로로 분리하여 개발
  - 이메일/비밀번호 유효성 확인(이메일 조건: @ 포함비밀번호 조건: 8자 이상)
  - 입력된 이메일과 비밀번호가 유효성검사를 통과 할때만 버튼이 활성화
  - 유효성 검사를 통과하지 않으면 아래에 경고 문구 표시
  - 로그인 API를 호출하고, 올바른 응답을 받았을 때 /todo 경로로 이동
  - 로그인 유무에 따른 리다이렉트
  - 로그아웃 기능 추가

- 투두 리스트
  - /todo경로에 접속하면 투두 리스트의 목록을 표시
  - 새로고침을 했을 때 현재 상태가 유지
  - 추가 버튼을 클릭하면 할 일이 추가
  - 수정 버튼을 클릭하면 수정 모드를 활성화하고, 수정 내용을 제출하거나 취소
  - 삭제 버튼을 클릭하면 해당 Todo를 삭제
