# PROTILLA 프로띠아 — 상품 기획 페이지

고래사어묵 신상품 **프로띠아(어육 프로틴 또띠아)** 상품 기획 랜딩 페이지입니다.

## 구성
```
index.html      # 페이지 본체 (CSS·JS 인라인)
assets/         # 이미지 (WebP)
.nojekyll       # GitHub Pages Jekyll 처리 비활성화
```

## 배포
GitHub Pages · `main` 브랜치 `/ (root)`

## 참고
- 원본 HTML은 이미지가 base64로 내장되어 23MB였으나, 이미지를 분리·WebP 변환하여 약 1MB로 경량화했습니다.
- 카카오톡·페이스북 공유 미리보기를 정확히 쓰려면 `index.html`의 `og:image` 값을 전체 주소로 바꿔주세요.
  예: `https://<사용자명>.github.io/<저장소명>/assets/og-image.jpg`
