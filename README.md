# Neusis Infra

Neusis 프로젝트 전체 스택(Frontend + BackAPI + ML + PostgreSQL)을 한 번에 띄우는 인프라 레포입니다.

## 사용법
```bash
cp .env.example .env
# .env의 POSTGRES_PASSWORD 수정
docker compose --env-file .env up -d


