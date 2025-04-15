# MCP-PRACTICE

개인 MCP(Master Control Program) 프로젝트 연습용 레포지토리입니다. 스프링 프레임워크와 연결하여 프로젝트를 개발할 예정입니다.

## 프로젝트 목표

- MCP 아키텍처와 스프링 프레임워크 연동 학습
- RESTful API 개발 연습
- 데이터베이스 연동 및 관리
- 서버 사이드 로직 구현

## 기술 스택

- Java
- Spring Boot
- Spring Data JPA
- Maven/Gradle
- MySQL/PostgreSQL (예정)
- GitHub Actions (CI/CD)

## 개발 환경 설정

```bash
# 레포지토리 클론
git clone https://github.com/playous/MCP-PRACTICE.git

# 디렉토리 이동
cd MCP-PRACTICE

# Spring Boot 프로젝트 시작 (향후 추가 예정)
# ./mvnw spring-boot:run
```

## MCP와 GitHub 연결 및 사용 방법

### 초기 설정

1. **Git 설치 확인**
   ```bash
   git --version
   ```

2. **GitHub 계정 설정**
   ```bash
   git config --global user.name "GitHub 사용자명"
   git config --global user.email "GitHub 이메일"
   ```

3. **MCP 프로젝트 디렉토리 생성 및 초기화**
   ```bash
   mkdir my-mcp-project
   cd my-mcp-project
   git init
   ```

### 기본 워크플로우

1. **파일 추가 및 변경사항 스테이징**
   ```bash
   git add .  # 모든 변경사항 추가
   # 또는
   git add src/  # 특정 디렉토리만 추가
   ```

2. **커밋하기**
   ```bash
   git commit -m "기능 구현: 로그인 API 개발"
   ```

3. **원격 저장소 연결 (처음 한 번만)**
   ```bash
   git remote add origin https://github.com/playous/MCP-PRACTICE.git
   ```

4. **변경사항 푸시**
   ```bash
   git push -u origin main  # 처음 푸시할 때
   # 이후에는
   git push
   ```

### 브랜치 관리

1. **새 브랜치 생성 및 전환**
   ```bash
   git checkout -b feature/login-api
   ```

2. **브랜치 목록 확인**
   ```bash
   git branch
   ```

3. **브랜치 전환**
   ```bash
   git checkout main
   ```

4. **브랜치 병합**
   ```bash
   git merge feature/login-api
   ```

### MCP 개발 시 권장 GitHub 워크플로우

1. **이슈 생성**: 새로운 기능이나 버그에 대한 이슈 생성
2. **브랜치 생성**: `feature/[이슈번호]-[기능명]` 형식으로 브랜치 생성
3. **코드 작성**: 브랜치에서 코드 작성 및 커밋
4. **PR(Pull Request) 생성**: 작업 완료 후 main 브랜치로 PR 생성
5. **코드 리뷰**: 필요시 코드 리뷰 및 토론
6. **병합**: 승인 후 main 브랜치로 병합
7. **이슈 종료**: 관련 이슈 종료

## 디렉토리 구조 (예정)

```
src/
├── main/
│   ├── java/
│   │   └── com/
│   │       └── example/
│   │           └── mcp/
│   │               ├── controller/
│   │               ├── service/
│   │               ├── repository/
│   │               ├── model/
│   │               └── config/
│   └── resources/
│       ├── static/
│       ├── templates/
│       └── application.properties
└── test/
```

## 라이센스

MIT 라이센스를 따릅니다.
