# 🛡️ DBNM (Digital Bullying Network Manager)

## 🎯 프로젝트 개요
DBNM은 온라인 상의 악성 댓글을 실시간으로 모니터링하고 분석하는 AI 기반 서비스입니다. 
"Day by Bird, Night by Mouse" 🌞🌙 라는 슬로건 아래, 24시간 연중무휴로 악성 댓글을 감지하고 대응 방안을 제시합니다.

## 👥 팀원 소개
**DBNM Team**
- 김경민
- 김동완
- 김지욱
- 방예진
- 황원영

## 🎞️ 시연 영상
[시연 영상](링크 넣어주세요)

## 🚀 주요 기능

### 🤖 AI 기반 악성 댓글 탐지
- **🕷️ 데이터 수집 기술**
  - Beautiful Soup과 Scrapy를 활용한 정적 웹페이지 크롤링
  - Selenium을 통한 동적 콘텐츠 수집
  - 실시간 댓글 모니터링을 위한 자동화된 수집 시스템

- **📊 텍스트 분석 및 처리**
  - NLTK를 활용한 자연어 처리
  - VADER 및 TextBlob을 통한 감정 분석
  - TF-IDF를 활용한 핵심 키워드 추출
  - Pandas와 NumPy를 이용한 대규모 데이터 처리

### ⚖️ 법률 분석 시스템
- **📝 자동 법률 검토**
  - 악성 댓글 유형 분류 및 매칭
  - 관련 법률 조항 자동 매칭
  - 고소 가능성 분석 리포트 생성

- **💾 데이터베이스 구축**
  - 악성 댓글 관련 판례 DB
  - 법률 조항 매핑 시스템
  - 실시간 법률 자문 지원

### 🔍 24/7 모니터링 시스템
- **🔔 실시간 알림 시스템**
  - 악성 댓글 발생 즉시 감지
  - 이메일/SMS 알림 서비스
  - 대시보드를 통한 실시간 모니터링

- **📊 리포트 생성**
  - 일간/주간/월간 리포트 자동 생성
  - 데이터 시각화 및 통계 분석
  - PDF 형식의 상세 보고서 제공

## 💻 기술 스택

### 🎨 Frontend
- React.js
- Styled-Components
- React Router DOM

### ⚙️ Backend
- Python
- Flask/Django (REST API)
- WebSocket (실시간 알림)

### 🗄️ 데이터베이스
- MongoDB (댓글 데이터 저장)
- PostgreSQL (사용자 정보 및 서비스 설정)

### 🧠 AI/ML
- TensorFlow/PyTorch (감정 분석 모델)
- Scikit-learn (머신러닝 알고리즘)
- BERT/KoBERT (한국어 자연어 처리)

## 💰 요금제

### 1. Basic 🌱
- 기본 모니터링
- 월 1회 리포트
- 5개 사이트 모니터링
- 300,000원/월

### 2. Professional 🌿
- 실시간 모니터링
- 주간 리포트
- 15개 사이트 모니터링
- 법률 검토 서비스
- 500,000원/월

### 3. Enterprise 🌳
- 24/7 실시간 모니터링
- 맞춤형 리포트
- 무제한 사이트 모니터링
- 전담 매니저 배정
- 1,000,000원/월

## ✨ 특장점
- **🎯 정확한 악성 댓글 탐지**: 최신 AI 기술을 활용한 높은 정확도
- **⚡ 실시간 모니터링**: 24시간 연중무휴 모니터링 시스템
- **📱 간편한 알림**: 즉각적인 알림 시스템
- **👥 전문가 지원**: 법률 검토 및 전문가 상담

## 🛠️ 설치 및 실행 방법

```bash
# Frontend
cd frontend
npm install
npm start

# Backend
cd backend
pip install -r requirements.txt
python app.py
```

## 🤝 기여 방법
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 라이센스
이 프로젝트는 MIT 라이센스를 따릅니다.

## 📞 연락처
- 📧 이메일: contact@dbnm.com
- 🏢 주소: 대구광역시 북구 대학로 80
- 📱 전화: 02-123-4567

## 🔜 향후 계획
1. **📱 모바일 앱 출시**: iOS 및 Android 앱 개발
2. **🌏 글로벌 서비스 확장**: 다국어 지원 및 해외 시장 진출
3. **🤖 AI 모델 고도화**: 더욱 정확한 악성 댓글 탐지
4. **👥 커뮤니티 기능**: 사용자 간 정보 공유 플랫폼 구축