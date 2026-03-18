---
name: 버그 리포트 (Bug Report) 템플릿
about: 오류나 버그를 발견했을 때 상세 내용을 기록합니다.
title: ''
labels: ''
assignees: ''

---

## 🚨 버그 요약 (Summary)
- 예: 지출 입력 폼에서 '금액'에 문자를 입력하고 저장하면 화면이 멈추는 현상 발생.

## 👣 재현 방법 (Steps to Reproduce)
1. 메인 화면에서 '새 내역 추가' 버튼 클릭
2. 카테고리와 날짜 선택
3. 금액 입력 칸에 숫자 대신 '만원'이라고 텍스트 입력 후 저장 버튼 클릭
4. 콘솔에 TypeError가 찍히며 컴포넌트가 다시 렌더링되지 않음

## 🎯 예상되는 정상 동작 (Expected Behavior)
- 문자가 입력될 경우 저장을 막고 "숫자만 입력해주세요"라는 경고창(Alert)이 떠야 함.

## 💻 환경 (Environment)
- OS: (예: Windows, macOS)
- 브라우저: (예: Chrome 최신 버전, Safari)

## 📸 스크린샷 또는 에러 로그 (Screenshots / Logs)
