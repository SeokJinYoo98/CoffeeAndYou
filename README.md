# TinyInvite

Codex를 활용해 제작한 모바일 웹 인터랙션 프로토타입입니다.

사용자가 초대를 수락하고 원하는 코스를 선택한 뒤, 해당 코스의 일정 작성용 Google Form으로 이동하는 흐름을 구현했습니다.

## Demo

- GitHub Pages: https://seokjinyoo98.github.io/TinyInvite/

## 주요 기능

- 초대 수락 → 코스 선택 → 결과 확인 → 일정 작성 화면 전환
- 거절 버튼 클릭 시 위치 이동 및 단계별 크기 축소
- 거절 버튼이 수락 버튼과 겹치거나 버튼 영역 밖으로 벗어나지 않도록 이동 범위 제한
- 선택한 코스에 맞는 결과 이미지와 Google Form 연결
- 모바일 화면과 Safe Area를 고려한 반응형 UI

## 기술 스택

- HTML
- CSS
- JavaScript
- GitHub Pages
- Google Forms
- Codex

## AI 활용 방식

화면 구성과 동작에 필요한 요구사항을 먼저 정리한 뒤, HTML·CSS·JavaScript 코드는 Codex로 생성했습니다.

생성된 결과는 브라우저에서 직접 실행하며 다음 항목을 반복해서 확인하고 수정했습니다.

- 거절 버튼이 수락 버튼과 겹치는 문제
- 작은 화면에서 버튼이 영역 밖으로 벗어나는 문제
- 클릭 횟수에 따른 버튼 크기와 문구 변화
- 코스별 이미지와 Google Form 연결
- 화면 전환과 모바일 레이아웃

## 담당 범위

- 서비스 콘셉트와 사용자 흐름 설계
- 기능 요구사항 작성 및 프롬프트 구체화
- 생성 결과 실행 및 동작 검증
- 수정 사항 정리와 반복 요청
- Google Form 연결
- GitHub Pages 배포

HTML·CSS·JavaScript 코드 작성과 수정은 Codex를 통해 진행했습니다.

## 사용자 흐름

1. 초대 화면에서 수락 또는 거절 버튼 선택
2. 영화, 카공, 술자리 중 원하는 코스 선택
3. 선택 결과 확인
4. 코스별 Google Form에서 일정 작성

## 프로젝트 구조

```text
TinyInvite/
└─ index.html
```

별도의 프레임워크 없이 하나의 HTML 파일에 스타일과 동작을 구성한 프로토타입입니다.
