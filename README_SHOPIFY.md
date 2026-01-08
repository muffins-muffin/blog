# 프리미엄 오토 모터스 Shopify 테마

Jekyll 블로그를 Shopify 전자상거래 테마로 완전히 변환했습니다.

## 📦 테마 구조

### `/config` - 테마 설정
- `settings_schema.json` - 테마 커스터마이징 옵션
- `settings_data.json` - 기본 설정 값

### `/layout` - 레이아웃
- `theme.liquid` - 메인 레이아웃 파일

### `/sections` - 섹션 (동적 콘텐츠 블록)
- `header.liquid` - 헤더/네비게이션
- `footer.liquid` - 푸터
- `hero-slider.liquid` - 히어로 슬라이더
- `featured-products.liquid` - 추천 상품 섹션

### `/templates` - 페이지 템플릿
- `index.json` - 홈페이지
- `product.liquid` - 상품 상세 페이지
- `collection.liquid` - 상품 목록 페이지
- `cart.liquid` - 장바구니 페이지
- `page.liquid` - 일반 페이지

### `/snippets` - 재사용 가능한 코드 조각
- `social-meta-tags.liquid` - SNS 메타 태그
- `css-variables.liquid` - CSS 변수
- `pagination.liquid` - 페이지네이션
- `product-card.liquid` - 상품 카드 컴포넌트

### `/assets` - 정적 파일
- CSS, JavaScript, 이미지 파일

## 🚀 Shopify에 업로드하는 방법

### 방법 1: Shopify CLI 사용 (권장)

1. Shopify CLI 설치:
```bash
npm install -g @shopify/cli @shopify/theme
```

2. 테마 업로드:
```bash
cd c:\download_download\blog
shopify theme push
```

### 방법 2: ZIP 파일로 업로드

1. 테마 폴더를 ZIP으로 압축
2. Shopify 관리자 → Online Store → Themes
3. "Upload theme" 클릭하여 ZIP 파일 업로드

## 🎨 주요 기능

- ✅ 완전한 Shopify Liquid 문법 변환
- ✅ 반응형 디자인 (모바일 최적화)
- ✅ 상품 페이지 및 컬렉션 페이지
- ✅ 장바구니 기능
- ✅ 커스터마이징 가능한 섹션
- ✅ 한국어 지원
- ✅ SEO 최적화 (메타 태그)
- ✅ 소셜 미디어 통합

## ⚙️ 설정 방법

Shopify 관리자에서:
1. Online Store → Themes → Customize
2. Theme settings에서:
   - 회사 정보 입력
   - 색상 설정
   - 소셜 미디어 링크 추가
   - 로고 업로드

## 📝 변환 내역

### Jekyll → Shopify 변환
- `_config.yml` → `config/settings_schema.json`
- `_layouts/` → `layout/theme.liquid`
- `_includes/` → `sections/` + `snippets/`
- Jekyll Liquid 태그 → Shopify Liquid 태그
- 정적 블로그 → 전자상거래 사이트

### 새로 추가된 기능
- 상품 관리 시스템
- 장바구니 및 결제 시스템
- 재고 관리
- 주문 처리
- 고객 계정 관리

## 🛠️ 커스터마이징

테마는 Shopify의 섹션 시스템을 사용하여 쉽게 커스터마이징할 수 있습니다:

- 홈페이지: `templates/index.json`에서 섹션 추가/제거
- 헤더: `sections/header.liquid`
- 푸터: `sections/footer.liquid`
- 스타일: `assets/theme.css`

## 📞 지원

문제가 발생하면 [Shopify 테마 문서](https://shopify.dev/themes)를 참조하세요.

## 라이선스

MIT License
