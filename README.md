## [PawTalk Frontend] 
강아지들의 커뮤니티 **PawTalk**  
AI를 활용한 강아지 전용 커뮤니티 서비스의 프론트엔드 프로젝트입니다.

### 개발 인원 및 기간 
- **개발 기간** : 2025-11-10 ~ 2025-12-07
- **개발 인원** : 1명 (본인)

### 기술 스택
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)


## [백엔드 연결]
- **백엔드 github** : https://github.com/jOyEjeaN2/wbp-ai-backend

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

## [프로젝트 구조]
```
wbp_frontend/
│── index.html
│── /assets
│── /static
└── README.md
```
백엔드와 완전히 독립된 Git 레포로 관리됨.


## [주요 기능]
### 🐶 1) 게시글 읽기·쓰기

- 제목, 내용 작성
- 이미지 첨부
- 조회수 / 좋아요 / 댓글 표시
- 게시글 수정 및 삭제

### 🤖 2) AI 톤 변환
사용자가 작성한 문장을 선택한 컨셉에 맞춰 **자동으로 변환**

- 강아지 시점 / 우리집 주인 자랑 / 산책 일기

### 🧑‍⚕️ 3) AI 고민 상담 모드

훈련사 또는 수의사 말투로 고민을 변환해 제공:

