<br>

# 🌜 월간;문 (Monthly-Moon)

> 🌝 KH 정보교육원 Final-Project <br>
> 🌝 조  장 : 김희라(@rlagmlfk) <br>
> 🌝 팀  원 : 공이현(@yihyunkong) 이여진(@yeojining5) 최경진(@jin6796) 황산하(@nahx2) <br>
> 🌝 기  간 : 2022.10.03 ~ 2022.11.16

<br>

## 1️⃣ 프로젝트 소개
**생리대 정기구독 서비스를 중심으로, 다양한 브랜드의 여성 위생용품을 제공하는 쇼핑몰**
- 팀명 : 세일러문(Seller-Moon)
- 프로젝트명 : **월간;문**
  - 달마다 돌아오는 월경(moon)
  - 구독의 주기마다 문 앞에 배송되는 특성(門)

<br>

## 2️⃣ 주제 선정 배경 및 의도
- 펜데믹 시기를 거치며 개인 면역력 관리와 **건강한 삶**에 대한 관심도의 증가. **비대면 서비스 수요**가 늘면서 소비자들이 추가 비용을 지불하더라도 필요한 것을 집에서 편리하게 구매하려는 욕구가 늘어나고 있는 추세.
- 과거 일부 분야에만 한정되었던 구독 서비스가 최근 건강기능식품, 영양제, 세탁, 의류, 식품 등 다양한 영역으로 확대됨에 따라 **구독 경제 시장의 성장세는 앞으로도 지속**될 것이라는 전망.
- 팀원들이 모두 여성으로 구성되어 있어 모두가 공감할 수 있는 아이템으로 **생리대 정기구독 서비스**를 선택하게 되었으며, 이에 따라 **편리하고 윤택한 위생용품 서비스를 제공하는 쇼핑몰**을 프로젝트 주제로 선정.

<br>

## 3️⃣ 개발 일정(공정표)
<img src="https://res.cloudinary.com/drxxdsv01/image/upload/v1668736395/%EA%B3%B5%EC%A0%95%ED%91%9C_eiiqgn.jpg">

<br>

## 4️⃣ ERD
<img src="https://res.cloudinary.com/drxxdsv01/image/upload/v1668736636/ERD_bnmyid.jpg">

<br>

## 5️⃣ 주요 기능
### 1) 회원
| 주요 구현 기능                               | 상세 기능 |
| --------------------------------------- | --------- |
| **로그인** | 이메일, 소셜로그인-네이버/카카오톡<br>로그인 유저 권한 관리 |
| **아이디/비밀번호 찾기**  | 임시비밀번호 메일 전송 |
| **회원가입** | 비밀번호 암호화<br>가입 포인트 지급 및 등급 부여<br>친구 추천코드 생성 및 포인트 지급 |        
| **마이페이지**  | 회원정보 조회/수정<br>정기구독 현황 조회 및 일시정지, 해지<br>커뮤니티-후기-주문배송-포인트-친구코드 조회  |
| **상품**  | 상품 리스트 조회(페이징)<br>상품 상세 페이지 및 장바구니 담기 |
| **장바구니**  | 장바구니 데이터 조회, 등록, 수정, 삭제<br>상품 수량 조정 및 배송비 설정 |
| **주문 & 결제**  | import API 활용 결제 로직<br>배송 정보 등록 및 포인트 수정 |
| **상세주문**  | 상세주문 등록, 수정, 주문취소 시 상태 수정 |
| **상품 후기**  | 후기 등록 및 포인트 지급, 수정, 삭제 |
| **커뮤니티**  | 게시글 등록, 수정, 삭제, 조회<br>댓글 작성,수정,삭제<br>게시글/댓글 신고 |
| **개인 쪽지**  | 받은쪽지/보낸쪽지 전체조회 및 상세조회<br>쪽지 보내기-쪽지 답장 및 수정, 삭제 |
| **1:1문의**  | Firebase Realtime Database를 활용한 실시간 채팅 |
| **고객센터**  | 공지사항/FAQ 조회, 조건검색, 조회수증가, 파일다운로드 |
<br>
### 2) 관리자
| 주요 구현 기능                               | 상세 기능 |
| --------------------------------------- | --------- |
| **회원 & 주문 관리**  | 데이터 전체조회, 상세보기 |
| **상품 후기 관리**  | 베스트 리뷰 선정 및 포인트 지급, 후기 삭제 |
| **거래처 관리**  | 거래처 등록, 수정, 상세보기, 전체조회, 페이징, 조건검색 |
| **상품 관리**  | 상품 등록, 수정, 삭제, 상세보기, 전체조회, 페이징, 조건검색, 이미지업로드 |
| **커뮤니티 관리**  | 게시글/댓글 관리, 블라인드 처리 |
| **포인트 관리**  | 포인트 사용/지급 조회 및 포인트 수동 등록, 수정, 삭제 |
| **고객센터 관리**  | 공지사항 등록, 수정, 삭제, 상세보기, 전체조회, 페이징, 조건검색<br>FAQ 등록, 수정, 삭제, 상세보기, 전체조회, 탭, 조건검색 |

<br>

## 6️⃣ 사용 기술 및 개발 환경
<img src="https://res.cloudinary.com/drxxdsv01/image/upload/v1668785478/%EA%B0%9C%EB%B0%9C%ED%99%98%EA%B2%BD_gzf5vr.png">
<br>
