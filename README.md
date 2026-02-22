# 🛒 쇼핑 리스트 앱

순수 Vanilla HTML/CSS/JavaScript로 만든 간단한 쇼핑 리스트 웹 앱입니다. 별도 설치 없이 브라우저에서 바로 실행됩니다.

## 기능

- **아이템 추가** — 입력 후 `추가` 버튼 클릭 또는 `Enter` 키
- **완료 체크** — 아이템 클릭 또는 체크박스 클릭 (토글)
- **아이템 삭제** — ✕ 버튼으로 개별 삭제
- **완료 항목 일괄 삭제** — 하단 버튼 클릭
- **필터** — 전체 / 미완료 / 완료 탭
- **데이터 유지** — `localStorage`에 자동 저장 (새로고침해도 유지)

## 실행 방법

```bash
# 저장소 클론
git clone https://github.com/indy10/shopping-listapp.git
cd shopping-listapp

# index.html을 브라우저에서 열기
start index.html        # Windows
open index.html         # macOS
xdg-open index.html     # Linux
```

또는 `index.html` 파일을 더블클릭하면 바로 실행됩니다.

## 기술 스택

- HTML5
- CSS3 (Flexbox, CSS Animations)
- Vanilla JavaScript (ES2020+)
- Web Storage API (localStorage)

## 파일 구조

```
shopping-listapp/
└── index.html   # 앱 전체 (HTML + CSS + JS)
```
