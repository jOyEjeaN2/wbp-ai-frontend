## [Gaver Frontend] 
강아지들의 커뮤니티 **Gaver**의 프론트엔드 프로젝트
HTML · CSS · JavaScript 기반으로 작성되며 FastAPI 백엔드와 연동됩니다.

## 🔗 백엔드 연결

현재 프론트는 다음 주소로 API 요청을 보냅니다:
```
http://localhost:8000
```

백엔드를 실행한 뒤 브라우저에서 다음처럼 띄울 수 있습니다:
```
cd wbp_frontend
python -m http.server 5500
```

이후 접속:
```
http://localhost:5500
```
---
## 🗂️ 프로젝트 구조
```
wbp_frontend/
│── index.html
│── /assets
│── /static
└── README.md
```
백엔드와 완전히 독립된 Git 레포로 관리됨.

---
## ✨ 주요 기능
### 🐶 1) 게시글 읽기·쓰기

- 제목, 내용 작성
- 이미지 첨부
- 조회수 / 좋아요 / 댓글 표시
- 게시글 수정 및 삭제

### 🤖 2) AI 톤 변환

글 내용을 선택한 강아지 전용 톤으로 자동 변환:

강아지 시점 / 우리집 주인 자랑 / 산책 일기

### 🧑‍⚕️ 3) AI 고민 상담 모드

훈련사 또는 수의사 말투로 고민을 변환해 제공:


