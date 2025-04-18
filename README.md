# 실전! 스프링 부트와 JPA 활용
[실전! 스프링 부트와 JPA 활용1 - 웹 애플리케이션 개발](https://www.inflearn.com/course/%EC%8A%A4%ED%94%84%EB%A7%81%EB%B6%80%ED%8A%B8-JPA-%ED%99%9C%EC%9A%A9-1?) (김영한)

# 기록
- 프로젝트 생성
- 라이브러리 확인
- HTML 생성 후 동작 확인(controller)
  - static, templates
- H2 데이터베이스 설치 및 실행
- JPA와 DB 설정 후 테스트(.yml)

- 요구사항 분석
- ERD 설계
- 도메인 분석 설계(회원, 상품, 주문 등)

- 회원 도메인 개발(리포지토리, 서비스)
- 상품 도메인 개발(리포지토리, 서비스)
- 주문 도메인 개발(리포지토리, 서비스)

- 도메인 모델 패턴
  -> 서비스가 아닌 도메인에 비즈니스 로직, 생성 메서드 등 개발

# 어노테이션
* @Transactional(readOnly = true)
* @Transactional
* @RequiredArgsConstructor @Autowired
* @NoArgsConstructor(access = AccessLevel.PROTECTED)
* @Inheritance(strategy = InheritanceType.SINGLE_TABLE)
* @DiscriminatorColumn(name = " ")
* @DiscriminatorValue(" ")

테스트
* @SpringBootTest
* @Transactional


# 찾아볼 것
- @Setter를 안쓰면...
