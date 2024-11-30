# 🛡️ DBNM (Digital Bad-comment Network Manager)

## 🎯 프로젝트 개요
DBNM은 온라인 상의 악성 댓글을 실시간으로 모니터링하고 분석하는 AI 기반 서비스입니다. 
"Day by Bird, Night by Mouse" 🌞🌙 라는 슬로건 아래, 24시간 연중무휴로 악성 댓글을 감지하고 대응 방안을 제시합니다.

## 🔍 문제 정의
현재 인터넷 공간에서 악성 댓글은 정신적 피해를 제공할 뿐만 아니라 기업의 이미지와 수익에까지 큰 영향을 미치고 있습니다. 
하지만 이 문제를 해결하기 위해서는 많은 시간과 비용이 소요되는 것이 현실입니다.

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

### 🔍 데이터 수집 및 분석석

## 🛠️ 주요 라이브러리 설명

### Natural.js
- 텍스트 토큰화
- 형태소 분석
- TF-IDF 구현
- 문장 유사도 분석

### Sentiment
- 텍스트 감정 분석
- 긍정/부정 점수 산출
- 다국어 지원
- 커스텀 어휘 사전 지원

### Puppeteer
- 헤드리스 크롬 브라우저 제어
- 동적 웹페이지 크롤링
- 자동화된 데이터 수집
- 스크린샷 및 PDF 생성

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

## 📊 시장 분석
TAM(전체시장), SAM(유효시장), SOM(수익시장)

잠재 고객: 약 133,000명
초기 목표 고객: 84명
초기 연간 예상 매출: 약 3억원 (월 사용료 30만원 기준)

## ✨ 차별화 요소

1. 체계적인 분석과 보고서
   - 단순 필터링이 아닌 체계적 기록 및 분석
   - 고소 가능성 판단 및 보고서 제공

2. 종합적인 법적 대응 지원
   - 맞춤형 대응 전략 제시
   - 관련 법적 조항 포함

3. 통합 플랫폼 관리
   - 다중 플랫폼 통합 관리
   - 효율적인 악성 댓글 필터링
  
## 🔜 향후 계획
1. **📱 마케팅 확대**
   - 성공 사례 적극 홍보
   - 업계 컨퍼런스 및 세미나 참여
2. **🌏 서비스 확장**
   - 다국어 지원 및 해외 시장 진출
   - 플랫폼 기능 확장
3. **🤖 AI 모델 고도화**
   - 더욱 정확한 악성 댓글 탐지
4. **👥 기업 파트너십 강화**
   - 대형 기획사와 MOU 체결
   - 법률 기관 및 사이버 보안 업체와 제휴

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

## 📞 연락처
- 📧 이메일: contact@dbnm.com
- 🏢 주소: 대구광역시 북구 대학로 80
- 📱 전화: 02-123-4567
