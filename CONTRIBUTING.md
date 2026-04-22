# Contributing Guide

## 1. 기본 원칙

- 모든 작업은 이슈를 먼저 생성한 뒤 진행합니다.

- 모든 변경 사항은 Pull Request를 통해 반영합니다.

- `main`, `dev` 브랜치에 직접 push 하지 않습니다.

- 기능 개발은 지정된 작업 브랜치에서 진행합니다.

## 2. 브랜치 전략

### 기본 브랜치

- `main` : 운영(최종 배포) 브랜치

- `dev` : 기능 개발 내용을 통합하는 기본 개발 브랜치

- `feat` : 개별 개발 브랜치

- `release/*` : 배포 직전 dev에서 분기하는 릴리즈 브랜치

### 작업 브랜치

형식:

```text

{type}/{issue-number}-{short-description}
