# Django Project

---

## 프로젝트 생성

- Project Name : mysite

- App Name : articles

---

 ## 페이지 생성

1. **index page**
   - `/index/` : 전체 게시글 목록을 보여줄 페이지
2. **create pages **
   - `/new/` : 글 작성을 위한 form (제목, 내용) 입력 페이지
   - `/create/` : 글 작성 결과 (제목, 내용)를 출력하는 페이지

---

## 추가

1. **base template **
   - 모든 템플릿들이 상속 받을 base.html

---

## 주의사항

1. **urls.py 설정 분리**
   - app_name도 함께 설정
2. **template 폴더 구조**