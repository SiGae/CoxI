# Database 설계

> notice

- koa의 문제인지 쿼리문에 컬럼과 테이블명에 대문자를 입력할 경우 자동으로 소문자로 변환되고 있음 고로 모든 테이블명과 컬럼명은 소문자로 작성바람 - SiGae

> userinfo - 회원정보 저장

- systemid - 시스템상에서 자동으로 부여하는 ID - int
- userid - 유저가 입력한 ID - varchar
- password - 해당 id의 비밀번호 - varchar
- dominumber - 유저의 거주 동
- auth - 이메일 유효성 검증여부 - boolean ( 기본값 False )
