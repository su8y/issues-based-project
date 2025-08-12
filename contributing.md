# 기여(참여) 가이드

이 문서는 Issue 중심으로 기여(참여)하기 위한 사용자들을 위한 가이드 입니다.

모든 기여는 Issues -> Pull Requests(PR) -> 흐름을 따르는 것을 원칙으로 합니다.

## 기여 방식 개요 
1. Issue 확인 또는 생성
2. Issue에 대한 합의(Assignee / Discussion)
3. 개발 및 커밋
4. Pull Request 생성
5. 리뷰 & 수정
6. Merge

## Issue 정책

### Issue 생성 전 체크리스트
새 Issue를 생성하기 전 반드시 아래를 확인해주세요.
- [ ] 이미 동일하거나 유사한 Issue가 존재하는지 검색했는가
- [ ] README / 문서를 확인했는가
- [ ] 재현 가능한 정보가 충분한가

### Issue 유형
Issue는 다음 유형 중 하나로 분류됩니다.
Bug
- 기존 기능이 의도대로 동작하지 않는 경우

Feature
- 새로운 기능 추가 제안

Refactor
- 기능 변경 없이 코드 구조 개선

Docs
- 문서 추가/수정 요청

Question
- 사용 방법, 설계 의도에 대한 질문

### Issue에 대한 합의 
작업의 중복을 방지하기 위한 Issue 할당 규칙을 정의합니다.
- Issue는 maintainer가 assignee를 지정하거나
- 기여자가 "I’d like to work on this" 라고 코멘트 후 승인받아 진행합니다.
- 승인 없이 진행한 PR은 반려될 수 있습니다.

## 코드 리뷰 정책(Code Review Policy)
- 모든 PR은 최소 1명 이상의 리뷰 승인이 필요합니다.
- 리뷰 코멘트는 논리적 근거 방식으로 작성해주세요.
- 개인 공격성 표현은 허용하지 않습니다.

## Merge 정책(Merge Policy)
- Squash Merge를 기본으로 합니다
- Merge는 maintainer만 수행합니다.
