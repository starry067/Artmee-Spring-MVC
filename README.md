# 🎨 Artmee: 전시회 종합 정보 및 예약 관리 시스템
> **솔데스크 IT 아카데미 파이널 프로젝트**
> **개발 기간:** 2024.02.01 ~ 2024.02.23 (약 3주)<br/>
> **My Role:** **UI/UX 총괄(Sole Designer), Frontend & Backend Core, PM**

## 💻 프로젝트 소개
**"파편화된 전시 정보를 통합하고, 커뮤니티 기능을 더하다"**

기존 전시회 관련 사이트의 **1) 분산된 정보, 2) 커뮤니티 부재, 3) 복잡한 예매 동선** 문제를 해결하기 위해 기획된 **All-in-One 전시회 플랫폼**입니다.<br/>
단순 정보 제공을 넘어, **사용자 경험(UX)을 최우선으로 고려한 직관적인 UI 설계**와 **Ajax 기반의 실시간 소통(댓글/후기)** 기능을 구현하여 플랫폼의 완성도를 높였습니다.

<br/>

## 👥 Team Members & Roles
| **[@starry067](https://github.com/starry067) (Me)** | [@ddooing](https://github.com/ddooing) | [@Timtory](https://github.com/Timtory) | [@pore133](https://github.com/pore133) |
| :---: | :---: | :---: | :---: |
| <img src="https://avatars.githubusercontent.com/u/55232668?v=4" width="100"/> | <img src="https://avatars.githubusercontent.com/u/118183105?v=4" width="100"/> | <img src="https://avatars.githubusercontent.com/u/101092238?v=4" width="100"/> | <img src="https://avatars.githubusercontent.com/u/94101325?v=4" width="100"/> |
| **UI/UX 총괄 (100%)**<br>공지사항/게시판(Ajax)<br>프론트 디자인<br>PPT 디자인 제작 | 결제/장바구니<br>결제 내역 관리<br>아카이브 | 전시회 등록<br>배너 관리<br>(관리자 페이지) | 로그인/회원가입<br>회원 관리<br>(관리자 페이지) |

### 🤝 Common Tasks (팀 공통 기여)
- **Database Modeling:** Oracle DB 설계 및 정규화 과정 공동 참여
- **Project Presentation:** 최종 발표 시연 및 질의응답 공동 진행

<br/>

## 👨‍💻 Key Contributions (핵심 기여도)
**팀 내 유일한 UI/UX 설계자이자 핵심 기능을 구현한 개발자**로서 기획부터 개발까지 프로젝트 전반을 주도했습니다.

### 1. 🎨 UI/UX Design & Architecture (기여도 100%)
- **Figma를 활용한 웹 전체 화면 설계 및 프로토타입 제작 전담 (60장 이상)**
- Happy Path뿐만 아니라 예외 케이스(Error Case)까지 고려한 상세 화면 설계
- 사용자 동선을 고려한 예매 프로세스 최적화 및 디자인 시스템 구축

#### 📐 Design Overview (전체 설계 흐름)
> **직접 설계한 60+ 페이지 분량의 전체 와이어프레임 및 디자인 구조입니다.**
> <br/>
> <img src="https://github.com/starry067/Artmee-Spring-MVC/blob/main/docs/image/%ED%94%84%EB%A1%A0%ED%8A%B8%EC%97%94%EB%93%9C_%EC%84%A4%EA%B3%84.png" width="100%" title="Click to view original"/>
> <br/>
> [![Figma](https://img.shields.io/badge/Figma-View_Full_Design-F24E1E?style=for-the-badge&logo=figma&logoColor=white)](https://www.figma.com/design/87VN2UQwmssNYxS3uuSNIZ/%EC%86%94%EB%8D%B0%EC%8A%A4%ED%81%AC-3%EC%A1%B0-2%EC%B0%A8?t=YMoO6JZGgRDkG1Ux-0)
> *(👆 위 배너를 클릭하면 Figma에서 상세 화면을 확인하실 수 있습니다.)*

### 2. 📢 공지사항 및 게시판 시스템 (기술적 심화)
- **공지사항:** 관리자(Admin) 권한 제어 로직 및 중요 공지 상단 고정(Pin) 기능 구현
- **게시판(Community):**
    - **Ajax 비동기 통신 도입:** 댓글 작성/삭제 시 전체 페이지 새로고침(Reload) 없이 데이터만 부분 업데이트되도록 구현하여 **UX 대폭 개선**
    - MyBatis 동적 쿼리(`<if>`, `<choose>`)를 활용한 다중 조건 검색(제목, 내용, 작성자) 최적화

<br/>

## ⚙️ Development Environment
### Backend & Server
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=java&logoColor=white) ![Spring](https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=spring&logoColor=white) ![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

### Frontend & Design
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=flat-square&logo=jquery&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)

### APIs
- **Payment:** Toss Payments API
- **Map:** Kakao Map API

<br/>

## 🚀 Trouble Shooting (문제 해결 경험)
### Issue: 댓글 등록 시 화면 깜빡임으로 인한 사용자 경험 저하
- **Problem:** 초기 구현 시 Form Submit 방식을 사용하여, 댓글 하나를 달 때마다 전체 페이지가 새로고침되고 스크롤이 초기화되는 불편함 발생.
- **Solution:** **jQuery Ajax**를 활용한 비동기 통신 방식으로 리팩토링.
    - Controller에서 View 대신 JSON 데이터를 반환하도록 `@ResponseBody` 적용.
    - 성공(Success) 콜백 함수에서 DOM을 직접 조작하여 댓글 목록만 부분 렌더링.
- **Result:** 페이지 이동 없이 즉각적인 피드백을 제공하는 **SPA(Single Page Application)와 유사한 부드러운 사용자 경험** 확보.

<br/>

## 🖥 UI Design & Implementation (화면 구성)
*(이미지를 클릭하면 원본 크기로 보실 수 있습니다)*

| 메인 화면 | 로그인/회원가입 |
| :---: | :---: |
| <img src="https://github.com/starry067/Artmee-Spring-MVC/blob/main/docs/image/%EC%95%84%ED%8A%B8%EB%AF%B8_%EB%A9%94%EC%9D%B8.png?raw=true" width="100%"/> | <img src="https://github.com/starry067/Artmee-Spring-MVC/blob/main/docs/image/%EC%95%84%ED%8A%B8%EB%AF%B8_%EB%A1%9C%EA%B7%B8%EC%9D%B8_%ED%9A%8C%EC%9B%90%EA%B0%80%EC%9E%85.png?raw=true" width="100%"/> |

| 마이페이지 (정보/예매내역) | 전시회 목록/상세 |
| :---: | :---: |
| <img src="https://github.com/starry067/Artmee-Spring-MVC/blob/main/docs/image/%EC%95%84%ED%8A%B8%EB%AF%B8_%EB%A7%88%EC%9D%B4%ED%8E%98%EC%9D%B4%EC%A7%80.png?raw=true" width="100%"/> | <img src="https://github.com/starry067/Artmee-Spring-MVC/blob/main/docs/image/%EC%95%84%ED%8A%B8%EB%AF%B8_%EC%A0%84%EC%8B%9C%ED%9A%8C.png?raw=true" width="100%"/> |

| 장바구니/결제 | 공지사항/게시판 (Ajax 적용) |
| :---: | :---: |
| <img src="https://github.com/starry067/Artmee-Spring-MVC/blob/main/docs/image/%EC%95%84%ED%8A%B8%EB%AF%B8_%EC%9E%A5%EB%B0%94%EA%B5%AC%EB%8B%88.png?raw=true" width="100%"/> | <img src="https://github.com/starry067/Artmee-Spring-MVC/blob/main/docs/image/%EC%95%84%ED%8A%B8%EB%AF%B8_%EA%B3%B5%EC%A7%80%EC%82%AC%ED%95%AD.png?raw=true" width="100%"/> |

| 전시회/배너 신청 | 관리자 페이지 |
| :---: | :---: |
| <img src="https://github.com/starry067/Artmee-Spring-MVC/blob/main/docs/image/%EC%95%84%ED%8A%B8%EB%AF%B8_%EC%A0%84%EC%8B%9C%ED%9A%8C%EC%8B%A0%EC%B2%AD.png?raw=true" width="100%"/> | <img src="https://github.com/starry067/Artmee-Spring-MVC/blob/main/docs/image/%EC%95%84%ED%8A%B8%EB%AF%B8_%EA%B4%80%EB%A6%AC%EC%9E%90%ED%8E%98%EC%9D%B4%EC%A7%80.png?raw=true" width="100%"/> |
