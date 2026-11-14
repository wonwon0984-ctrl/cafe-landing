# ☕ Cafe Ongi — 카페 온기 랜딩 페이지

가상의 동네 카페 **"온기"** 를 소개하는 한 페이지짜리 웹사이트입니다.
별도의 프레임워크나 빌드 과정 없이 **HTML + CSS** 만으로 만들었고, GitHub Pages로 배포되어 있습니다.

🔗 **라이브 사이트:** https://wonwon0984-ctrl.github.io/cafe-landing/

## 페이지 구성

| 섹션 | 내용 |
| --- | --- |
| 히어로 | 카페 소개 문구, CTA 버튼, CSS로 그린 커피잔 애니메이션(김이 피어오름) |
| 소개 | 직접 로스팅 · 매일 굽는 빵 · 머물기 좋은 자리 — 3가지 특징 카드 |
| 메뉴 | 시그니처 음료와 디저트 6종, 가격 |
| 오시는 길 | 주소, 요일별 영업시간 |

## 폴더 구조

```
cafe-landing/
├── index.html   # 페이지 마크업
├── style.css    # 스타일, 애니메이션, 반응형 레이아웃
└── README.md    # 이 문서
```

## 특징

- 이미지 파일 없이 CSS만으로 일러스트 표현
- 모바일 대응 반응형 레이아웃 (820px 이하에서 1단 구성)
- Google Fonts: Gowun Batang(제목), Noto Sans KR(본문)
- 내비게이션 클릭 시 부드러운 스크롤 이동

## 로컬에서 보기

저장소를 받은 뒤 `index.html`을 브라우저로 열면 됩니다.

```bash
git clone https://github.com/wonwon0984-ctrl/cafe-landing.git
cd cafe-landing
start index.html   # macOS: open index.html
```

## 배포

`main` 브랜치 루트(`/`)가 GitHub Pages로 배포됩니다. `main`에 푸시하면 1분 안팎으로 사이트에 자동 반영됩니다.

## 참고

카페 이름, 주소, 메뉴, 가격은 모두 예시용 가상 정보입니다.
