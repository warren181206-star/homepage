# 골드인사이트 홈페이지 위젯

아임웹 코드 위젯용 HTML 저장소

## 폴더 구조

```
homepage/
├── _config/
│   └── pages.md          # 메뉴/URL 정보 (수정 시 header.html 반영)
├── _shared/
│   ├── header.html       # 공통 헤더 (반복섹션용)
│   └── footer.html       # 공통 푸터 (반복섹션용)
├── pages/
│   ├── home.html             # 메인 페이지
│   ├── gold-insight.html     # 골드인사이트 (상위메뉴)
│   ├── gold-consulting.html  # ㄴ 금투자상담
│   ├── consignment.html      # 위탁거래
│   ├── buy-sell.html         # 금·은 매입 (상위메뉴)
│   ├── buy-back.html         # ㄴ 금매입상담
│   ├── products.html         # 제품안내 (상위메뉴)
│   ├── gold-bar.html         # ㄴ 골드바
│   ├── silver-bar.html       # ㄴ 실버바
│   ├── souvenir.html         # ㄴ 기념품
│   ├── refining.html         # 금·은정련
│   └── notice.html           # 공지사항
├── images/
│   ├── header/              # 헤더용 이미지
│   ├── footer/              # 푸터용 이미지
│   ├── home/
│   ├── gold-insight/
│   ├── gold-consulting/
│   ├── consignment/
│   ├── buy-sell/
│   ├── buy-back/
│   ├── products/
│   ├── gold-bar/
│   ├── silver-bar/
│   ├── souvenir/
│   ├── refining/
│   └── notice/
└── README.md
```

## 아임웹 적용 방법

각 페이지마다 코드위젯 3개 구성:
1. **헤더 위젯** (반복섹션) → `_shared/header.html` 복사
2. **본문 위젯** → `pages/해당페이지.html` 복사
3. **푸터 위젯** (반복섹션) → `_shared/footer.html` 복사

## 이미지 URL 형식

```
https://raw.githubusercontent.com/warren181206-star/homepage/main/images/폴더명/파일명
```

## 페이지 URL 정보

기본 URL: `https://goldinsight053.imweb.me`

| 파일명                  | 메뉴명     | URL                |
| -------------------- | ------- | ------------------ |
| home.html            | 메인 페이지  | `/home`            |
| gold-insight.html    | 골드인사이트  | `/gold-insight`    |
| gold-consulting.html | ㄴ 금투자상담 | `/gold-consulting` |
| consignment.html     | 위탁거래    | `/consignment`     |
| buy-sell.html        | 금·은 매입  | `/buy-sell`        |
| buy-back.html        | ㄴ 금매입상담 | `/buy-back`        |
| products.html        | 제품안내    | `/products`        |
| gold-bar.html        | ㄴ 골드바   | `/gold-bar`        |
| silver-bar.html      | ㄴ 실버바   | `/silver-bar`      |
| souvenir.html        | ㄴ 기념품   | `/souvenir`        |
| refining.html        | 금·은정련   | `/refining`        |
| notice.html          | 공지사항    | `/notice`          |

## 메뉴 수정

`_config/pages.md` 또는 위 URL 정보 수정 후 Claude에게 header.html 업데이트 요청
