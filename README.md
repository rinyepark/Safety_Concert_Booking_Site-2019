# 콘서트 공정 예매 서비스(My universe)
<img src="https://user-images.githubusercontent.com/109687076/184577762-eb9f20c4-801c-4209-878f-466559adf83f.JPG" width="60%">

[관련자료](http://yerin.creatorlink.net/CONCERT-BOOKING-SITE)

## 1. Duration
- 2019.03 ~ 2019.06
- Team Project(4 members)

## 2. Skills - 사용 시스템 환경
    * OS: Windows, Mac
    * Language: Python, html/css, javascripts
    * framework: Django
    * DBMS: PostgreSQL

## 3. Contents 

<img src="https://user-images.githubusercontent.com/109687076/184578078-13ca29d4-384e-4adb-aaa9-a151d1b330d8.JPG" width="50%"><img src="https://user-images.githubusercontent.com/109687076/184578079-2cc8687d-c1bb-4c3e-9841-0b0fbd062279.JPG" width="50%">
<img src="https://user-images.githubusercontent.com/109687076/184578080-f42207e5-9397-4e7c-b37b-60b414e50708.JPG" width="50%"><img src="https://user-images.githubusercontent.com/109687076/184578082-e3d7cbc5-d8bc-4705-8c4d-aaf2c7bd0dd2.JPG" width="50%">
<img src="https://user-images.githubusercontent.com/109687076/184578085-dd308447-69b9-459e-8a59-b33e9560c6d5.JPG" width="50%"><img src="https://user-images.githubusercontent.com/109687076/184578070-9955113e-e2d7-4bd4-a3a2-fe69d5969e32.JPG" width="50%">
<img src="https://user-images.githubusercontent.com/109687076/184578073-6bcceeaa-14d7-4ebe-b23c-389b23b5bc0f.JPG" width="50%"><img src="https://user-images.githubusercontent.com/109687076/184578074-caf74e8a-53db-41c3-b028-a1c181e825ce.JPG" width="50%">
<img src="https://user-images.githubusercontent.com/109687076/184578076-2c7cb533-0129-45e0-8594-c97608c83ec8.JPG" width="50%"><img src="https://user-images.githubusercontent.com/109687076/184578077-e9b1fdcd-c5f6-4bbb-95d9-f206578280b8.JPG" width="50%">


## 4. Results

* 설계 목표 달성 정도<br><br>
    1. 회원 및 비회원 권한
        - [x] 로그인, 회원가입
        - [x] 회원가입한 사용자에 대해 회원 권한 부여
        - [x] 로그인한 사용자만 예매/마이페이지 이용 가능
        - [x] 비로그인한 사용자의 다른 기능 이용 가능
    <br><br>
    2. 공연 예매 기능
        - [x] 예매 기간인 콘서트는 예매 가능
        - [x] 예매 기간이 아닌 콘서트는 예매 불가능
        - [x] 예매 불가능 좌석에 대한 예매 금지 처리
        - [x] 동일 공연 예매 불가능
        - [x] 마이페이지에서 예매내역 확인 가능
        - [x] 해당 좌석 가격 만큼 사용자의 코인(연료) 감소
        - [ ] 예매 취소기능
        - [ ] 모바일 티켓 제공
    <br><br>
    3. 데이터 관리
        - [x] 사상된 릴레이션 구조에 맞춘 테이블 생성 및 데이터 저장
        - [x] 대용량 데이터 사용 (실제 데이터 및 파생데이터를 포함해 약 2만여개 이상의 데이터)
        - [x] 효율적인 쿼리 사용 (Django의 ORM 및 쿼리 셋 이용)
        - [x] 무결성 제약조건 유지
        - [x] 회원가입, 관심 콘서트/가수, 예매, 코인충전 등의 기능을 통해 생성되는 데이터 DB에 저장
    <br><br>
    4. 기본기능 및 추가기능
        - [x] 공연 제목을 이용한 검색 가능 여부
        - [ ] 상세검색 기능
        - [x] 로그인한 사용자의 관심 콘서트/가수 등록 가능
        - [x] 포인트 형식의 코인(연료) 충전 가능
        - [x] 로그인한 사용자의 마이페이지 확인 가능
        - [x] 전체, 일정별, 가수별로 콘서트 목록 제공
        - [x] 콘서트 포스터 클릭 시 상세정보 제공
        - [x] 예매 시 해당 공연의 일자 및 좌석 선택 가능
        - [x] 티켓팅 페이지 접속 가능
