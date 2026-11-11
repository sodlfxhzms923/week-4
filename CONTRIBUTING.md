# CONTRIBUTING

## 1. 프로젝트 소개

본 프로젝트는 GitHub의 Feature 브랜치 전략, Conventional Commits, Pull Request 및 코드 리뷰 절차를 학습하기 위한 협업 실습 프로젝트입니다.

## 2. 브랜치 전략

- `main`: 안정적인 코드를 관리하는 기본 브랜치
- `feature/*`: 새로운 기능을 개발하는 브랜치
- `fix/*`: 버그를 수정하는 브랜치
- `docs/*`: 문서를 추가하거나 수정하는 브랜치

새로운 브랜치는 최신 `main`을 기준으로 생성하며, 작업 완료 후 Pull Request를 통해 병합합니다.

## 3. 커밋 메시지 규칙

모든 커밋은 Conventional Commits 규칙을 따릅니다.

형식: `type: description`

주요 타입:
- `feat`: 새로운 기능 추가
- `fix`: 버그 수정
- `docs`: 문서 작성 및 수정
- `style`: 코드 형식 변경
- `refactor`: 코드 구조 개선
- `test`: 테스트 코드 추가
- `chore`: 설정 및 유지보수 작업

예시:
- `feat: add homepage structure`
- `fix: improve responsive layout`
- `docs: update contribution guidelines`

## 4. Pull Request 규칙

1. 기능별로 독립된 브랜치에서 작업합니다.
2. Conventional Commits 형식으로 커밋을 작성합니다.
3. 변경 목적과 주요 수정 사항을 PR에 기록합니다.
4. 테스트 결과와 리뷰 요청 사항을 작성합니다.
5. 코드 리뷰 의견을 검토하고 필요한 수정을 반영합니다.
6. 수정 완료 후 PR을 `main`에 병합합니다.

## 5. 코드 리뷰 규칙

코드 리뷰에서는 다음 태그를 사용합니다.

- `[MUST]`: 반드시 수정해야 하는 문제
- `[SHOULD]`: 수정을 권장하는 개선 사항

리뷰 의견에는 문제의 원인과 개선 방향을 구체적으로 작성합니다.

## 6. 리뷰 반영 절차

1. 리뷰 의견을 확인합니다.
2. 필요한 코드 수정을 진행합니다.
3. 수정 내용을 새로운 커밋으로 기록합니다.
4. 리뷰 댓글에 반영 결과를 답변합니다.
5. 해결된 리뷰 대화는 Resolve conversation으로 처리합니다.

## 7. 병합 규칙

- 리뷰에서 지적된 필수 수정 사항은 병합 전에 해결합니다.
- 변경 사항을 최종 확인한 후 `main`에 병합합니다.
- 병합 후 기본 브랜치에서 파일이 정상적으로 반영되었는지 확인합니다.
