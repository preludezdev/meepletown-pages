# Meepletown Pages

이 레포는 GitHub Pages 기반 이벤트 페이지를 관리하기 위한 저장소입니다.

## 개요

- 이벤트 페이지는 `HTML + 이미지` 조합으로 구성됩니다.
- 각 이벤트는 `events` 폴더 아래에 개별 폴더로 추가합니다.
- GitHub Pages로 배포되는 것을 전제로 설계되었습니다.
- 기획자도 직접 이미지와 HTML을 수정해 운영할 수 있도록 단순한 구조를 유지합니다.

## 폴더 구조

```text
events/
  sample-event/
    index.html
    banner.webp
    detail-01.webp
    detail-02.webp

templates/
  event-template.html

docs/
  HOW_TO_CREATE_EVENT.md
```

## 사용 방법

1. `events/sample-event`를 복사합니다.
2. 새 이벤트 폴더를 생성합니다. 예: `events/event-001`
3. 이미지 파일을 교체합니다.
4. `index.html` 문구와 버튼 링크를 수정합니다.
5. 커밋 후 `git push` 하면 GitHub Pages에 반영됩니다.

## 작성 원칙

- 모바일 중심 UI
- 심플하고 깔끔한 카드형 레이아웃
- 큰 버튼과 읽기 쉬운 구조
- 외부 JavaScript 없이 정적 HTML 중심 구성

## 참고 문서

- 기획자 작업 가이드: `docs/HOW_TO_CREATE_EVENT.md`
- 복사용 기본 템플릿: `templates/event-template.html`
