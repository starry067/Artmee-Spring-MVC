# 🎨 Artmee: 전시회 종합 정보 및 예약 관리 플랫폼
> **솔데스크 IT 아카데미 파이널 프로젝트**
> **개발 기간:** 2023.XX.XX ~ 2024.03.XX (약 X개월)
> **팀원:** 4명 (본인 역할: 백엔드 개발 및 UI/UX 총괄)

## 📖 프로젝트 개요
사용자가 다양한 전시회 정보를 한눈에 확인하고 예약할 수 있는 웹 플랫폼입니다. 전시회 검색부터 예매, 리뷰 작성, 그리고 관리자 페이지를 통한 회원 및 전시 관리 기능을 제공합니다.

## 🛠 Tech Stack
### Environment
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ%20IDEA-000000?style=flat-square&logo=intellij-idea&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![Github](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)

### Backend
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=java&logoColor=white) ![Spring](https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=spring&logoColor=white) ![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white) ![MyBatis](https://img.shields.io/badge/MyBatis-000000?style=flat-square)

### Frontend & Design
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)

---

## 👨‍💻 My Roles & Responsibilities (핵심 기여 부분)
**Backend Developer & UI/UX Designer**로서 시스템의 핵심 로직 구현과 전체적인 사용자 경험을 설계했습니다.

### 1. 관심 전시회 '좋아요' 및 스크랩 기능 구현
- **기능 설명:** 사용자가 관심 있는 전시회를 저장하고 마이페이지에서 모아볼 수 있는 기능
- **기술적 포인트:**
    - Ajax 비동기 통신을 활용하여 페이지 새로고침 없이 즉각적인 UI 반응 처리
    - Oracle DB 설계를 통해 사용자별 좋아요 상태 관리 및 중복 방지 로직 구현

### 2. 커뮤니티(게시판) 및 관람 후기 시스템
- **기능 설명:** 전시회에 대한 기대평 및 관람 후기를 작성, 수정, 삭제(CRUD)하는 기능
- **기술적 포인트:**
    - MyBatis를 활용한 동적 쿼리 작성으로 검색 및 페이징 처리 최적화
    - XSS 방지를 위한 입력 데이터 검증 로직 적용 (필요 시 추가)

### 3. 전체 UI/UX 설계 (Figma)
- **기여도:** 프로젝트 전체 페이지의 와이어프레임 및 프로토타입 제작 (기여도 90% 이상)
- **설계 의도:** 사용자가 전시회 정보를 직관적으로 파악할 수 있도록 이미지 중심의 레이아웃 구성 및 예매 동선 최적화

---

## 💾 ERD 설계
*(친구분 README에 있는 ERD 이미지가 있다면 여기에 넣으세요. 본인이 설계에 참여한 부분을 설명하면 더 좋습니다.)*
- Oracle DB를 사용하여 정규화를 거친 테이블 설계
- 회원, 전시, 예매, 게시판 등 주요 엔티티 간의 관계 설정

## 🚀 Trouble Shooting (문제 해결 경험)
*(이 부분은 면접관이 가장 주의 깊게 봅니다. 기억나는 에피소드 하나만 적어보세요.)*
**Problem:**
- 예: 게시판 페이징 처리 시 쿼리 속도 저하 문제 발생
**Solution:**
- 예: 인덱스(Index) 활용 및 쿼리 튜닝을 통해 조회 속도 개선
- 예: 또는 Ajax 통신 시 JSON 데이터 파싱 오류 해결 과정 등

## 🖥 화면 구성
*(본인이 만든 '좋아요' 기능이나 '게시판' 화면 캡처본을 넣으세요)*
| 메인 화면 | 상세 페이지 (좋아요 기능) |
| :---: | :---: |
| ![Main](이미지경로) | ![Detail](이미지경로) |
