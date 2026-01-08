# Shopify 테마 필수 파일 체크리스트

## ✅ 완료된 항목

### Config (설정 파일)
- [x] config/settings_schema.json
- [x] config/settings_data.json

### Layout (레이아웃)
- [x] layout/theme.liquid

### Sections (섹션)
- [x] sections/header.liquid
- [x] sections/footer.liquid
- [x] sections/hero-slider.liquid
- [x] sections/featured-products.liquid

### Templates (템플릿)
- [x] templates/index.json (홈페이지)
- [x] templates/product.liquid (상품 페이지)
- [x] templates/collection.liquid (컬렉션 페이지)
- [x] templates/cart.liquid (장바구니)
- [x] templates/page.liquid (일반 페이지)

### Snippets (스니펫)
- [x] snippets/social-meta-tags.liquid
- [x] snippets/css-variables.liquid
- [x] snippets/pagination.liquid
- [x] snippets/product-card.liquid

### Assets (정적 파일)
- [x] assets/theme.css (커스텀 스타일)
- [x] assets/bootstrap.min.css
- [x] assets/font-awesome.min.css
- [x] assets/animate.min.css
- [x] assets/style.css
- [x] assets/bootstrap.min.js
- [x] assets/jquery-1.10.2.min.js
- [x] assets/wow.min.js

## 🔄 변환 내역

### Jekyll → Shopify Liquid 태그 변환
- `{{ site.title }}` → `{{ shop.name }}`
- `{{ site.baseurl }}` → 제거 (Shopify는 baseurl 불필요)
- `{{ page.title }}` → `{{ page_title }}`
- `{{ content }}` → `{{ content_for_layout }}`
- Jekyll 포스트 → Shopify 블로그/상품

### 새로 생성된 Shopify 전용 기능
- 상품 (products) 시스템
- 컬렉션 (collections) 시스템
- 장바구니 (cart) 시스템
- 체크아웃 (checkout) 연동
- Liquid 필터 및 객체

## 📋 다음 단계

1. **테마 테스트**
   - Shopify Partner 계정에서 개발 스토어 생성
   - 테마 업로드 및 테스트

2. **상품 데이터 추가**
   - 샘플 상품 추가
   - 컬렉션 생성
   - 이미지 업로드

3. **페이지 생성**
   - About (회사소개) 페이지
   - Contact (문의하기) 페이지
   - Team (판매팀) 페이지

4. **커스터마이징**
   - 로고 업로드
   - 색상 설정
   - 메뉴 구성

## 🎯 Shopify 업로드 준비 완료

이 테마는 Shopify에 바로 업로드 가능한 완전한 구조를 갖추고 있습니다.
