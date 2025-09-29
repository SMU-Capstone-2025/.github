# Doctalk - 팀 협업을 더 스마트하게
![2025 캡스톤](https://github.com/user-attachments/assets/0251967a-64b2-4b41-8e7f-8b624eb51e91)
## 🔗 바로가기
- [🌐 Doctalk ](https://docktalk.co.kr)  

## 1. 개요
기존 협업 도구들은 채팅, 문서, 작업 관리가 여러 툴에 분산되어 있어 학생 팀 프로젝트나 기업 협업 환경에서 번거로움이 발생합니다.  
예를 들어,  
- 채팅: 카카오톡 / 디스코드  
- 문서: 구글 독스 / 노션  
- 작업 관리: Jira  

각각의 기능이 분리되어 있어 협업 효율성이 저하되는 문제를 해결하기 위해 본 프로젝트를 기획하였습니다.  

본 프로젝트는 **하나의 플랫폼에서 프로젝트 관리, 작업 관리, 문서 협업, 화상 통화 기능을 통합 제공**하여 효율적이고 직관적인 협업 환경을 제공합니다.  

---

## 2. 주요 기능
### 📂 프로젝트
- 프로젝트 생성 · 조회 · 수정  
- 사용자 초대 및 권한 관리  

### 📝 작업 관리
- 작업 생성 · 조회 · 수정 · 삭제  
- 상태 변경, 버전 관리  

### 📑 문서 관리
- 실시간 동기화  
- 편집 내역 저장 및 조회  
- AI 요약 & 맞춤법 교정  
- 편집 위치 시각화

### 🎥 화상 통화
- 화면 공유 & 채팅  
- 협업 지원  
- 팀 커뮤니케이션  

---

## 3. 아키텍처
<img width="2356" height="1571" alt="image" src="https://github.com/user-attachments/assets/b6cd86da-1f79-4508-8156-3e83949ec285" />


---

## 4. 개발환경
- **프론트엔드**: React, Tailwind CSS, TipTap Editor, WebRTC, WebSocket(STOMP)  
- **백엔드**: Spring Boot(Java), Gradle, MongoDB, Redis, Apache Kafka  
- **인프라/배포**: GitHub Actions, AWS EC2 & ECR, Docker, Nginx  
