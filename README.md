# Lumen-Day

## 프로젝트 소개
Lumen-Day는 사용자에게 매 6시간마다 맞춤 운세를 제공하는 웹 애플리케이션입니다. AI 기술을 활용하여 개인화된 운세를 생성하고 제공합니다.

## 주요 기능
- 사용자 인증 및 프로필 관리
- 매 6시간마다 자동 운세 생성
- 운세 기록 조회 및 저장
- 개인화된 운세 추천

## 기술 스택
### 프론트엔드
- React.js
- Material-UI
- Redux

### 백엔드
- Node.js + Express
- MongoDB
- OpenAI API

## 프로젝트 구조
```
Lumen-Day/
├── client/          # 프론트엔드 React 애플리케이션
├── server/          # 백엔드 Express 서버
│   ├── config/      # 환경 설정
│   ├── models/      # MongoDB 모델
│   ├── routes/      # API 라우트
│   └── controllers/ # 컨트롤러
└── README.md
```

## 설치 방법
1. 프로젝트 클론하기
```bash
git clone [프로젝트 URL]
cd Lumen-Day
```

2. 의존성 설치
```bash
npm install
```

3. 환경 변수 설정
`.env` 파일 생성 및 설정:
```
MONGODB_URI=your_mongodb_uri
OPENAI_API_KEY=your_openai_api_key
JWT_SECRET=your_jwt_secret
```

4. 개발 서버 실행
```bash
npm run dev:full
```

## 사용 방법
1. 회원가입 또는 로그인
2. 프로필 설정
3. 운세 생성 및 조회
4. 운세 기록 확인

## 배포
- 프론트엔드: Vercel
- 백엔드: Heroku
- 데이터베이스: MongoDB Atlas

## 라이선스
MIT License
