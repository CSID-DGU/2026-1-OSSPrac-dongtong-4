# 2026-1-OSSPrac-dongtong-4

2026년 1학기 오픈소스소프트웨어실습 4팀 **동통** 팀 프로젝트 저장소입니다.

본 프로젝트는 Flask를 기반으로 팀 소개 웹사이트를 구현하고, Docker 환경을 구성하여 다른 실행 환경에서도 동일하게 웹 애플리케이션을 실행할 수 있도록 제작한 실습 프로젝트입니다.

---

## 프로젝트 소개

기존의 정적인 팀 소개 웹사이트를 발전시켜, 팀원 소개와 상세 페이지를 구성하고 방문자 메시지 입력 기능을 추가한 동적인 Flask 웹 애플리케이션입니다.

웹사이트에서는 다음 내용을 확인할 수 있습니다.

- 팀 소개
- 팀원별 역할 및 상세 정보
- 프로젝트 개발 과정
- 방문자 메시지 입력 및 확인
- Flask 기반 웹 구조
- Docker 및 Docker Compose 실행 환경
- GitHub 협업 과정

---

## 팀원 소개

| 역할 | 이름 | 담당 |
|---|---|---|
| 팀장 | 지소윤 | Flask 서버 구조, 프로젝트 소개 영역, 구조 시각화 |
| 팀원 | 이동은 | 메인 화면 UI, 팀원 카드 디자인, 반응형 레이아웃 |
| 팀원 | 조수아 | 개발과정 섹션, Navbar 연결, 팀원 상세 페이지 및 방문자 메시지 기능 |

---

## 주요 기능

### 1. 메인 페이지

팀명, 프로젝트 소개 문구, 팀원 소개 카드가 출력됩니다.

### 2. 팀원 상세 페이지

각 팀원 카드를 클릭하면 팀원별 상세 페이지로 이동합니다.

팀원 상세 페이지에서는 다음 정보를 확인할 수 있습니다.

- 담당 역할
- 기술 스택
- 프로젝트 기여 내용
- 자기소개
- 포트폴리오 링크

### 3. 개발과정 섹션

프로젝트 진행 흐름, 역할 분담, 협업 방식, Docker 실행 환경 등을 정리했습니다.

### 4. 방문자 메시지 기능

사용자가 이름, 관심 분야, 메시지를 입력하면 결과 페이지에서 입력 내용을 확인할 수 있습니다.

또한 메시지 목록 페이지에서 입력된 방문자 메시지를 확인할 수 있습니다.

---

## 기술 스택

| 구분 | 사용 기술 |
|---|---|
| Backend | Python, Flask |
| Frontend | HTML, CSS, Bootstrap, JavaScript |
| Template | Jinja2 |
| DevOps | Docker, Docker Compose |
| Collaboration | Git, GitHub, Pull Request, Merge |

---

## 프로젝트 구조

```text
2026-1-OSSPrac-dongtong-4
├── Subject3_2
│   ├── team.py
│   ├── Dockerfile
│   ├── docker-compose.yml
│   ├── uwsgi.ini
│   ├── templates
│   │   ├── base.html
│   │   ├── index.html
│   │   ├── member_detail.html
│   │   ├── input.html
│   │   ├── result.html
│   │   ├── messages.html
│   │   └── contact.html
│   └── static
│       ├── css
│       ├── images
│       └── js
├── README.md
└── LICENSE
