## [PawTalk Frontend] 
### 🐶 AI 톤 변환 기술을 접목한 반려견 커뮤니티 - **PawTalk**
**PawTalk**는 반려인이 작성한 글을 AI가 강아지의 시점이나 전문가의 말투로 변환해주는 AI 기반 멀티 페르소나 커뮤니티입니다. </br>
프론트엔드와 백엔드를 분리한 독립적 구조로 설계되었으며 직관적인 UI를 통해 AI 기능을 누구나 쉽게 경험할 수 있도록 제작되었습니다. 


<img width="1415" height="746" alt="PawTalk 홈화면" src="https://github.com/user-attachments/assets/47566603-24ef-48b3-9407-030109f8efca" />
<img width="1410" height="721" alt="스크린샷 2026-04-28 오후 10 45 04" src="https://github.com/user-attachments/assets/491510f1-408f-43ba-98d8-363630f187df" />


### 개발 인원 및 기간 
- **개발 기간** : 2025-11-10 ~ 2025-12-07 (4주)
- **개발 인원** : 1명 (개인 프로젝트)
- **주요목표** : LLM 기능을 커뮤니티 서비스에 자연스럽게 녹여내고 프론트엔드-백엔드 간 효율적인 통신 구조 설계

### 🛠 기술 스택
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)

&nbsp;

## [주요 기능]
### 🤖 1. AI 톤 변환 
사용자가 작성한 문장을 선택한 컨셉에 맞춰 **변환**

- **강아지 시점** : "나 오늘 산책해서 신나!" 등 반려견의 입장에서 작성한 듯한 글로 변환
- **우리집 주인 자랑** : 반려견이 주인을 칭찬하는 귀여운 말투로 변환 
- **산책 일기** : 오늘의 산책 기록을 강아지의 입장으로 변환

### 🧑‍⚕️ 2. AI 고민 상담 모드
훈련사 또는 수의사 페르소나를 AI에 부여하여 사용자의 고민에 대해 전문적인 말투로 답변을 제공하거나 글을 정리

### 🐶 3. 커뮤니티 기본 기능
- 게시글 및 이미지 업로드 (CRUD)
- 실시간 조회수, 좋아요, 댓글 기능 반영
- 사용자 친화적인 카드형 UI 레이아웃 


&nbsp; 

## [백엔드 연결]
- **백엔드 github** : https://github.com/jOyEjeaN2/wbp-ai-backend

현재 프론트는 다음 주소로 API 요청을 보냄:
```
http://localhost:8000
```

백엔드를 실행한 뒤 브라우저에서 다음처럼 띄울 수 있음:
```
cd wbp_frontend
python -m http.server 5500
```

이후 접속:
```
http://localhost:5500
```

&nbsp;

## [📂 프로젝트 구조]
```
wbp_frontend/
│── index.html
│── /assets
│── /static
└── README.md
```
백엔드와 독립된 구조로 설계되어 유지보수와 배포가 용이

&nbsp;


