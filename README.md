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
- MySQL
- GitHub Actions (예정)

## Claude Desktop과 함께 사용

Claude Desktop과 함께 사용하려면 다음을 추가하세요 `claude_desktop_config.json`:

```json
{
  "mcpServers": {
    "github": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-github"],
      "env": {
        "GITHUB_PERSONAL_ACCESS_TOKEN": "<YOUR_TOKEN>"
      }
    }
  }
}
```

## 라이센스

MIT 라이센스를 따릅니다.
