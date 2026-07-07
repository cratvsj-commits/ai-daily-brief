# AI 데일리 브리핑

멀티에이전트 파이프라인이 매일 AI/개발 트렌드 브리핑을 작성해 GitHub Pages(Jekyll)로 발행하는 프로젝트.

## 실행

- `/daily-post` — 전체 파이프라인 실행 (리서치 → 작성 → 검수 → 발행). 하루 1회.
- 파이프라인 정의: `.claude/skills/daily-post/SKILL.md`
- 에이전트 정의: `.claude/agents/` (researcher, writer, editor)

## 구조

- `_posts/` — 발행된 글 (Jekyll 포스트, `YYYY-MM-DD-daily-brief.md`)
- `memory/covered.md` — 다룬 주제 기록 (중복 방지용, 에이전트 공유 메모리)
- `memory/notes.md` — 운영 노트 (실패 사유 등)
- `scratch/` — 파이프라인 중간 산출물 (gitignore됨)

## 규칙

- 글의 모든 주장은 소스 URL로 뒷받침되어야 한다. 소스 없는 내용은 싣지 않는다.
- 검수(editor) 없이 `_posts/`에 글을 커밋하지 않는다.
- 발행 커밋 메시지: `post: YYYY-MM-DD 데일리 브리핑`
