# 우리한글 도구 (urihangeul-tools)

> **한국어 처리 실용 웹 도구 모음** — 글자 수 세기, 자모 분리, 로마자 표기, 한영 타자 변환 등 18개

[![우리한글](https://img.shields.io/badge/site-urihangeul.com-1f6feb)](https://urihangeul.com)
[![도구 카테고리](https://img.shields.io/badge/도구-카테고리-brightgreen)](https://urihangeul.com/category/tools/korean-tools/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

한국어 글쓰기/텍스트 처리에 필요한 실용 도구들을 모아 무료로 공개합니다. 각 도구는 외부 라이브러리 없이 순수 HTML/CSS/JavaScript로 구현되어 있어 그대로 가져다 쓰기 좋습니다.

## 🚀 웹에서 바로 사용

➜ **[우리한글 — 도구 카테고리](https://urihangeul.com/category/tools/korean-tools/)**

각 도구는 우리한글 홈페이지에서 설치 없이 즉시 실행 가능합니다.

## 📋 도구 리스트

| # | 도구 | 설명 |
|---|---|---|
| 01 | [글자 수 세기](https://urihangeul.com/word-counter/) | 글자/어절/문장/단락 수 동시 표시 |
| 02 | [원고지 계산기](https://urihangeul.com/manuscript-paper-calculator/) | 200자/400자/600자 원고지 매수 환산 |
| 03 | [자모 분리기](https://urihangeul.com/jamo-splitter/) | 한글 → 초성/중성/종성 분해 |
| 04 | [공백 정리기](https://urihangeul.com/whitespace-cleaner/) | 중복 공백/줄바꿈 정리 |
| 05 | [초성 추출기](https://urihangeul.com/chosung-extractor/) | 초성만 뽑아내기 |
| 06 | 로마자 표기 변환기 | 한글 → 로마자 표기법 적용 |
| 07 | 글자 반복 제거기 | 연속 반복 글자 정리 |
| 08 | 한영 타자 변환기 | 한↔영 키 매핑 변환 |
| 09 | 줄 정렬기 | 가나다/역순/중복 제거 |
| 10 | 찾아 바꾸기 | 정규식 지원 텍스트 치환 |
| 11 | 구분자 변환기 | CSV ↔ 줄 단위 변환 |
| 12 | 전통 단위 변환기 | 척/관/되 등 전통 단위 환산 |
| 13 | 숫자 한글 변환기 | 숫자 ↔ 한글(만/억/조) 변환 |
| 14 | 가독성 분석기 | 평균 문장 길이/난이도 판별 |
| 15 | 반복 단어 찾기 | 단어 남용 감지 |
| 16 | 문장 분리기 | 문장 단위 분할 |
| 17 | 특수문자 제거기 | 이모지/URL/해시태그 정리 |
| 18 | 단어 빈도 분석기 | 단어 빈도 + 막대 그래프 |

> 전체 도구 목록은 [도구 카테고리](https://urihangeul.com/category/tools/korean-tools/)에서 한눈에 볼 수 있습니다.

## 🛠 로컬에서 실행

```bash
git clone https://github.com/lime38/urihangeul-tools.git
cd urihangeul-tools/01-word-counter
# index.html 을 브라우저에서 열기
```

각 도구는 단일 HTML 파일 + 공통 `shared/style.css`로 동작. 별도 빌드/서버 불필요.

## 📁 디렉터리 구조

```
urihangeul-tools/
├── README.md
├── LICENSE
├── 01-word-counter/                  ← 글자 수 세기
├── 02-manuscript-paper-calculator/   ← 원고지 계산기
├── 03-jamo-splitter/                 ← 자모 분리기
├── 04-whitespace-cleaner/            ← 공백 정리기
├── 05-chosung-extractor/             ← 초성 추출기
│   ├── index.html
│   └── README.md
└── shared/
    └── style.css                     ← 18개 공통 다크 팔레트
```

## 📜 라이선스

[MIT](LICENSE) — 자유롭게 가져다 쓰셔도 됩니다. 코드 파일 상단의 헤더 주석(출처/홈페이지 링크)은 유지해 주시면 감사하겠습니다.

## 🤝 제작 방식

이 도구들은 사람이 기획/설계/검토하고 AI(Claude)와 협업하여 구현했습니다. 각 commit 메시지에도 공동 작성자(`Co-Authored-By: Claude`)로 명시되어 있습니다.

## 🔗 관련 링크

- 우리한글 홈페이지: https://urihangeul.com
- 도구 카테고리: https://urihangeul.com/category/tools/korean-tools/

---

> 한글 도구 / 한국어 텍스트 처리 / 한글 맞춤법 / 자모 분리 / 로마자 표기 / 글자 수 세기
