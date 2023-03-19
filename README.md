# 개요
간단한 커머스 프로젝트

Use : Spring, Jpa, Mysql, Redis, Docker, AWS

Goal : seller와 customer 를 중개해주는 커머스 서비스 구축

## member
### 공통사항
- [ ] 이메일을 통해서 인증번호를 통한 회원가입

### customer
- [ ] 회원가입
- [ ] 인증(이메일)
- [ ] 로그인 토큰 발행
- [ ] 로그인 토큰을 통한 제어 확인(Jwt, Filter를 사용해서)
- [ ] 예치금 관리

### seller
- [ ] 회원가입

## orderServer

### seller
- [ ] 상품 등록, 수정
- [ ] 상품 삭제

### customer
- [ ] 장바구니를 위한 Redis 연동
- [ ] 상품 검색 & 상세 페이지
- [ ] 장바구니에 물건 추가
- [ ] 장바구니 확인
- [ ] 주문하기
- [ ] 주문내역 이메일로 발송하기

