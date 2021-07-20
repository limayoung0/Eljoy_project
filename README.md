# 전자제품 대여사이트
1. [개요](https://github.com/limayoung0/Eljoy_project/blob/master/README.md#%EA%B0%9C%EC%9A%94)
2. [내용](https://github.com/limayoung0/Eljoy_project#%EB%82%B4%EC%9A%A9)
3. [구현 기능](https://github.com/limayoung0/Eljoy_project#%EA%B5%AC%ED%98%84-%EA%B8%B0%EB%8A%A5)
  * [마이페이지](https://github.com/limayoung0/Eljoy_project#%EB%A7%88%EC%9D%B4%ED%8E%98%EC%9D%B4%EC%A7%80)
    - [장바구니](https://github.com/limayoung0/Eljoy_project#%EC%9E%A5%EB%B0%94%EA%B5%AC%EB%8B%88)
    - [내 주문내역](https://github.com/limayoung0/Eljoy_project#%EB%82%B4-%EC%A3%BC%EB%AC%B8%EB%82%B4%EC%97%AD)
    - [내 리뷰](https://github.com/limayoung0/Eljoy_project#%EB%82%B4-%EB%A6%AC%EB%B7%B0)
    - [내 질문](https://github.com/limayoung0/Eljoy_project#%EB%82%B4-%EC%A7%88%EB%AC%B8)
  * [고객센터](https://github.com/limayoung0/Eljoy_project#%EA%B3%A0%EA%B0%9D%EC%84%BC%ED%84%B0)
    - [FAQ](https://github.com/limayoung0/Eljoy_project#faq)
    - [공지사항](https://github.com/limayoung0/Eljoy_project#%EA%B3%B5%EC%A7%80%EC%82%AC%ED%95%AD)
    - [Q&A](https://github.com/limayoung0/Eljoy_project#qa)
---
# 개요
* 프로젝트 명 : 전자제품 대여사이트
* 일정 : 2021.05.19 ~ 2021.07.06
* 개발 목적 : 공기청정기나 제습기처럼 황사나 장마로 한 철에만 사용하는, 매일 사용하지 않는 비싼 가전제품을 정해진 기간동안 사용할 수 있도록 대여해 주는 사이트
* 개발 환경
  - O/S : Window 10
  - Server : Apache-tomcat-v9.0
  - Java EE IDE : Eclopse ( version 2021-03 )
  - Database : Oracle SQL Developer ( version 4.1.3.20 )
  - Programming Language : JAVA, HTML, CSS, JavaScript, JSP, SQL 
  - Framework/Flatform : Spring, Mybatis, jQuery, Bootstrap
  - API : Daum map
  - Version management : Git
---
# 내용
* 팀원별 역할
  - 공통 : 주제 선정, 기획, 요구사항 정의, 화면설계, DB설계
  - 김민국 : 관리자 페이지, 상품 상세보기 페이지, 주문 페이지
  - 성근모 : 로그인, 회원가입
  - 임아영 : 마이페이지 ( 장바구니, 내 주문내역, 내 리뷰, 내 질문 ), 고객센터 (FAQ, 공지사항, Q&A ), 로고디자인 아이디어
  - 임채경 : 다음 주소 api, CSS, PPT, 로고디자인 제작

* 구현 기능
  - 마이페이지
  - 고객센터
 
* DB설계
<img src=""  width="700" height="370" align="center">

---
# 구현 기능
## 마이페이지
### 장바구니
<img src="https://user-images.githubusercontent.com/78776635/126303459-e404e974-4cc0-4a39-817f-b3fa4ccf904f.PNG"  width="800" height="370">

* 구현 기능 설명
  - session 을 통해 저장된 사용자의 장바구니 내역 조회
  - 체크박스 전체선택/해제 가능

### 내 주문내역
<img src=""  width="800" height="370">

* 구현 기능 설명
  - session 을 통해 저장된 사용자의 주문 내역 조회
  - 리뷰 작성 클릭 시 리뷰 작성 페이지로 넘어감

### 내 리뷰
<img src=""  width="800" height="370">

* 구현 기능 설명
  - session 을 통해 저장된 사용자의 리뷰 내역 조회
  - 상세보기 가능
  - 수정, 삭제 가능

### 내 질문
<img src=""  width="800" height="370">

* 구현 기능 설명
  - session 을 통해 저장된 사용자의 질문 내역 조회
  - 상세보기 가능
  - 수정, 삭제 가능

## 고객센터
### FAQ
<img src="https://user-images.githubusercontent.com/78776635/126314499-8ee80bba-d808-45b4-8cc4-fdfc3eb81be9.PNG"  width="800" height="370">

* 구현 기능 설명
  - 회원들이 자주 묻는 질문들을 FAQ를 한눈에 보기 편하게 조회
  - 카테고리 클릭 시, 해당 카테고리에 대한 FAQ만 조회 가능
  - 질문 클릭 시, 해당 질문의 답변이 아코디언 형식으로 보여짐
  - 관리자만 FAQ 작성 가능

### 공지사항
<img src="https://user-images.githubusercontent.com/78776635/126314654-0c6d3774-b97e-42b5-b1ae-e5b7e9e2ecc1.PNG"  width="800" height="370">

* 구현 기능 설명
  - 공지사항 게시판 글 목록 조회
  - 게시글 상세조회 ( 제목, 내용, 제목+내용 )
  - 관리자만 글쓰기, 수정, 삭제 가능
  - 상세보기 가능
  - 목록으로 이동

### Q&A
<img src="https://user-images.githubusercontent.com/78776635/126314680-a7dc0581-0e9b-4b5c-85bd-0ad979e94749.PNG"  width="800" height="370">

* 구현 기능 설명
  - 전체 회원의 Q&A 목록 조회
  - 게시글 상세조회 ( 작성자, 제목, 내용, 작성자+제목+내용 )
  - 상세보기 가능
  - 목록으로 이동

---
지금까지 읽어주셔서 감사합니다 :)
