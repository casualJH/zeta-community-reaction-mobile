# 제타 커뮤니티 반응 (모바일 + 누적 선택 + 말투 프리셋)

원본 **제타 실시간 커뮤니티 반응** 유저스크립트를 모바일 Safari에서도 버튼이 표시되도록 수정하고, 선택과 말투 설정 기능을 추가

## 원본 및 출처

- 원본 스크립트: https://github.com/imlikedott/zeta-community-reaction/blob/main/zeta-community-reaction.user.js
- 원본 저장소: https://github.com/imlikedott/zeta-community-reaction

## 주요 변경 사항

- 모바일 Safari에서 커뮤니티 반응 버튼의 위치 및 표시 문제 보정
- 최근 말풍선 **5개 / 10개 누적 선택**: 같은 버튼을 여러 번 누르면 선택 수가 누적됨
- 기존처럼 말풍선을 직접 추가하거나 선택 해제 가능
- 말투 지침 및 추가 주문 프리셋 선택, 직접 입력 가능

## 설치

[Tampermonkey 설치용 유저스크립트](https://raw.githubusercontent.com/casualJH/zeta-community-reaction-mobile/main/zeta-community-reaction.user.js)

Tampermonkey가 활성화된 브라우저에서 위 링크로 스크립트를 설치하세요. Gemini API 사용 및 설정은 원본 스크립트의 방식을 따릅니다.

## 자동 업데이트

유저스크립트 메타데이터의 `@updateURL` 및 `@downloadURL`이 이 저장소의 `main` 브랜치 파일을 가리킵니다. 추후 수정 내용을 같은 경로에 올리고 `@version`을 `1.1.2`, `1.1.3` 등으로 올리면 Tampermonkey의 업데이트 확인 기능을 통해 새 버전을 받을 수 있습니다.

**현재 버전: 1.1.1**
