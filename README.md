# 우리한글 도구 (urihangeul-tools)

> **한국어 처리 실용 웹 도구 모음** — 글자 수 세기, 자모 분리, 로마자 표기, 한영 타자 변환 등 18개

[![우리한글 블로그](https://img.shields.io/badge/blog-urihangeul.com-1f6feb)](https://urihangeul.com)
[![도구 카테고리](https://img.shields.io/badge/도구-카테고리-brightgreen)](https://urihangeul.com/category/tools/korean-tools/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

한국어 글쓰기·텍스트 처리에 필요한 실용 도구들을 모아 무료로 공개합니다. 각 도구는 외부 라이브러리 없이 순수 HTML/CSS/JavaScript로 구현되어 있어 그대로 가져다 쓰기 좋습니다.

## 🚀 웹에서 바로 사용

➜ **[우리한글 — 도구 카테고리](https://urihangeul.com/category/tools/korean-tools/)**

각 도구는 우리한글 블로그에서 설치 없이 즉시 실행 가능합니다.

## 📋 도구 리스트

| # | 도구 | 설명 | 실행 |
|---|---|---|---|
| 01 | 글자 수 세기 | 글자/어절/문장/단락 수 동시 표시 | [실행해 보기](https://urihangeul.com/word-counter/) |
| 02 | 원고지 계산기 | 원고지 매수 환산 | 준비 중 |
| 03 | 자모 분리기 | 한글 → 초성/중성/종성 분해 | 준비 중 |
| 04 | 공백 정리기 | 중복 공백·줄바꿈 정리 | 준비 중 |
| 05 | 초성 추출기 | 초성만 뽑아내기 | 준비 중 |
| 06 | 로마자 표기 변환기 | 한글 → 로마자 표기법 적용 | 준비 중 |
| 07 | 글자 반복 제거기 | 연속 반복 글자 정리 | 준비 중 |
| 08 | 한영 타자 변환기 | 한↔영 키 매핑 변환 | 준비 중 |
| 09 | 줄 정렬기 | 가나다·역순·중복 제거 | 준비 중 |
| 10 | 찾아 바꾸기 | 정규식 지원 텍스트 치환 | 준비 중 |
| 11 | 구분자 변환기 | CSV ↔ 줄 단위 변환 | 준비 중 |
| 12 | 전통 단위 변환기 | 척·관·되 등 전통 단위 환산 | 준비 중 |
| 13 | 숫자 한글 변환기 | 숫자 ↔ 한글(만·억·조) 변환 | 준비 중 |
| 14 | 가독성 분석기 | 평균 문장 길이·난이도 판별 | 준비 중 |
| 15 | 반복 단어 찾기 | 단어 남용 감지 | 준비 중 |
| 16 | 문장 분리기 | 문장 단위 분할 | 준비 중 |
| 17 | 특수문자 제거기 | 이모지·URL·해시태그 정리 | 준비 중 |
| 18 | 단어 빈도 분석기 | 단어 빈도 + 막대 그래프 | 준비 중 |

> 매일 1개씩 추가 공개 중입니다. 전체 카탈로그는 [블로그 카테고리](https://urihangeul.com/category/tools/korean-tools/) 참고.

## 🛠 로컬에서 실행

```bash
git clone https://github.com/lime38/urihangeul-tools.git
cd urihangeul-tools/01-word-counter
# index.html 을 브라우저에서 열기
```

각 도구는 단일 HTML 파일 + 공통 `shared/style.css`로 동작. 별도 빌드·서버 불필요.

## 📁 디렉터리 구조

```
urihangeul-tools/
├── README.md
├── LICENSE
├── 01-word-counter/      ← 글자 수 세기
│   ├── index.html
│   └── README.md
└── shared/
    └── style.css         ← 18개 공통 다크 팔레트
```

## ✨ 다음 단계 — 우리한글 프로

18개 도구는 시작입니다. **AI 기반 정밀 한국어 맞춤법·표현 교정 서비스 *우리한글 프로*** 가 곧 공개됩니다.

- 어문규정 기반 자동/제안 교정
- 의미 분기 사용자 선택형 팝업
- 사례 검색 기반 설명 생성

➜ 사전 안내 / 베타 신청: **[urihangeul.com](https://urihangeul.com)**

## 📜 라이선스

[MIT](LICENSE) — 자유롭게 가져다 쓰셔도 됩니다. 코드 파일 상단의 헤더 주석(출처·블로그 링크)은 유지해 주시면 감사하겠습니다.

## 🔗 관련 링크

- 도구 카테고리: https://urihangeul.com/category/tools/korean-tools/
- 우리한글 프로: https://urihangeul.com
- 블로그 (한글 맞춤법·도구·언어 콘텐츠): https://urihangeul.com

---

> 한글 도구 / 한국어 텍스트 처리 / 한글 맞춤법 / 자모 분리 / 로마자 표기 / 글자 수 세기
