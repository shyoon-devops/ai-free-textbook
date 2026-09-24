# AI 무료 교과서

기초가 없는 사람을 위한 무료 LLM 사용법 가이드. [Mintlify](https://mintlify.com)로 배포한다.

## 로컬 미리보기

```bash
npm i -g mint
mint dev          # http://localhost:3000
mint broken-links # 깨진 링크 검사
```

## 구조

| 경로 | 내용 |
|------|------|
| `index.mdx`, `roadmap.mdx` | 홈, 학습 로드맵 |
| `basics/` | 0단계 · AI와 첫 만남 |
| `talk/` | 1단계 · 대화의 기초 |
| `daily/` | 2단계 · 생활 속 활용 |
| `skills/` | 3단계 · 더 잘 쓰기 |
| `safety/` | 4단계 · 주의사항 |
| `beyond/` | 5단계 · 한 걸음 더 |
| `appendix/` | 자료실 (용어, 질문 모음, 비교표, FAQ) |
| `docs.json` | 사이트 설정과 내비게이션 |

새 페이지는 파일을 만들고 `docs.json`의 `navigation`에 경로를 추가해야 사이드바에 나온다.
작성 규칙은 `AGENTS.md`를 따른다.
