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
│   ├── home.html         # 메인 페이지
│   ├── gold-consulting.html
│   ├── consignment.html
│   ├── buy-back.html
│   ├── gold-bar.html
│   ├── silver-bar.html
│   ├── souvenir.html
│   ├── refining.html
│   └── notice.html
├── images/
│   ├── goldbar/
│   └── footer/
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

## 메뉴 수정

`_config/pages.md` 수정 후 Claude에게 header.html 업데이트 요청
