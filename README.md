# 박민수

Java/Spring Boot 기반 백엔드 개발을 중심으로 학습하고 프로젝트를 진행해 왔습니다.  
기능 구현에 그치지 않고, 구조와 데이터 흐름, 배포 과정까지 함께 고민하는 개발자를 지향합니다.

## Tech Stack
- Backend: Java, Spring Boot
- Database: MySQL, Redis
- Infra/Tools: Docker, Git/GitHub, GitHub Actions, Jenkins, Nginx
- Others: JavaScript, Python, Flask, PyQt5

## Projects

### 1. Chat Server
Spring Boot 기반 1:1 채팅 서버 개인 프로젝트입니다.  
1:1 채팅 메시지 송수신 기능을 구현하면서 ERD와 서비스 구조를 여러 번 다시 고민했습니다.  
처음에는 chatRoom과 chatList 중심으로 단순하게 설계했지만, 사용자 관계와 메시지 표시 방식까지 고려하면서 각 역할을 더 분리할 필요가 있다고 판단했습니다.  
또한 Controller에서 바로 Application Service를 호출하던 구조도 기능이 늘어나며 흐름이 섞이기 시작해, Facade Service를 두고 유스케이스 단위로 처리 과정을 정리하는 방향으로 구조를 바꾸었습니다.

- Tech: Java, Spring Boot, MySQL, Docker
- Repository: https://github.com/minsu11/chat-server

### 2. My-Books
유사 MSA 구조로 개발한 온라인 서점 팀 프로젝트입니다.  
주문/결제, 관리자 정책 등록·수정·삭제, 포인트 사용 및 적립 기능을 구현했고,  
GitHub Actions, Jenkins, Docker를 활용한 배포 흐름도 함께 경험했습니다.  
프로젝트 전체 구조는 GitHub Organization 메인 README에 정리되어 있습니다.

- Tech: Java, Spring Boot, MySQL, Redis, Docker, Jenkins, GitHub Actions
- Organization: https://github.com/My-Books-projects

### 3. Real-Time Location System
BLE 기반 실시간 실내 위치 추정 시스템 팀 프로젝트입니다.  
PyQt UI와 서버 보조 역할을 맡아 기능 구현과 데이터 흐름이 연결되는 과정을 경험했습니다.

- Tech: Python, Flask, PyQt5
- Repository: https://github.com/minsu11/RTLS

## Experience
### NHN Academy TA
- 강의 보조, 질의응답 및 과제 채점
- 연수생 프로젝트 코드리뷰 및 디버깅 지원
- 구현 의도와 판단 근거를 먼저 듣고 함께 해결 방향을 정리하는 방식으로 피드백 진행

## Links
- Portfolio: https://minsu-portpolio.notion.site/ea90b01b8d874c88bb94dbd89d7d2b11?source=copy_link
- Email: zmfjtnl2@gmail.com
