# Spring_FrameWork
Spring_FrameWork의 특징

1. 일반적인 자바 객체를 위한 POJO 지원
2. 객체 간의 결합도 줄이는 의존성 주입DI 지원
3. 공통 모듈 재사용하기 위한 관점 지향 프로그래밍AOP 지원
4. 일관성있는 모듈의 트랜잭션 지원

POJO : 별도의 API 사용하여 제한 받지 않는 자바 클래스
의존성 주입 DI : 객체 간의 관계를 관리할 때 사용하는 기법
관점 지향 프로그래밍AOP : 핵심적인 기능에서 부가적인 공통 관심사를 분리하여 공통 모듈로 만들어서 설계하고 개발하는 방법

스프링 모듈 중 중요하게 볼 점
Spring Framework : 핵심 컨테이너 및 의존성 주입 프레임워크

Spring Boot : 독립실행형 Spring 애플리케이션 지원, 빌드 구성 단순화를 위해 스타터 종속성 사용, xml 구성이 필요x


@Controller와 @RestController의 차이점을 간단히 설명하시오.

	@Controller는 View를 반환하고, @RestController는 JSON/XML 형태의 데이터를 직접 반환함 (즉, @ResponseBody가 포함됨).
