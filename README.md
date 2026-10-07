# ChatGPT 짚짱 아이콘 — GitHub 버전

아이콘 32개와 Tampermonkey userscript입니다.

## 업로드

이 폴더의 icons 폴더와 chatgpt-aicon-github.user.js를
공개 저장소 daeokim/ChatGPT-DCCon-Renderer-Optimized의 main 브랜치 루트에 업로드하세요.

## 설치

Tampermonkey의 새 스크립트 편집기에 chatgpt-aicon-github.user.js 전체 내용을 붙여넣고 저장하세요.
기존 Firebase/localhost 버전은 비활성화한 후 ChatGPT를 새로고침하세요.
Python 서버는 필요 없습니다.

## 테스트

ChatGPT에 다음 태그를 코드블록 없이 그대로 출력해 달라고 요청하세요.

[[icon:생각중]]
[[icon:검색]]
[[icon:검토완료]]
[[icon:출처있음]]
[[icon:해냈다]]

코드블록·입력창의 태그는 변환하지 않습니다.
이미지 다운로드 실패 시 원래 태그가 유지됩니다.

## 구성

icons/: 원본 PNG 32개
chatgpt-aicon-github.user.js: GitHub Raw 이미지 로더

원본 코드: https://github.com/nokryong/ChatGPT-DCCon-Renderer-Optimized
