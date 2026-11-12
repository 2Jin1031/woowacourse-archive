# 우아한테크코스 7기 기록

우아한테크코스 7기 웹 백엔드 과정에서 진행한 미션과 코드 리뷰를 모아둔 레포입니다.

## Level 1 (2025.02 ~ 2025.03)

| 미션 | 핵심 고민 | PR |
|-|-|-|
| 로또 | 원시값 포장과 일급 컬렉션을 어디까지 적용할지 | [1단계](https://github.com/woowacourse/java-lotto/pull/551) · [2단계](https://github.com/woowacourse/java-lotto/pull/629) |
| 출석 | View와 도메인 의존성 분리, 출력 DTO 도입 | [1단계](https://github.com/woowacourse/java-attendance/pull/5) · [2단계](https://github.com/woowacourse/java-attendance/pull/152) |
| 블랙잭 | Player와 Dealer의 중복 제거, ACE 점수 설계의 확장 범위 | [1단계](https://github.com/woowacourse/java-blackjack/pull/832) · [2단계](https://github.com/woowacourse/java-blackjack/pull/920) |
| 장기 | SOLID 원칙 적용과 관련 코드 응집 | [1단계](https://github.com/woowacourse/java-janggi/pull/15) · [2단계](https://github.com/woowacourse/java-janggi/pull/161) |

레벨 1 글쓰기: [나에 대한 빅데이터를 쌓는 시간이었던 레벨!](https://github.com/woowacourse/woowa-writing/pull/700)

## Level 2 (2025.04 ~ 2025.06)

| 미션 | 핵심 고민 | PR |
|-|-|-|
| 방탈출 예약 관리 | 계층 책임 분리와 Repository 인터페이스 도입 | [1~3단계](https://github.com/woowacourse/spring-roomescape-admin/pull/262) · [4~9단계](https://github.com/woowacourse/spring-roomescape-admin/pull/343) · [10단계](https://github.com/woowacourse/spring-roomescape-admin/pull/364) |
| 방탈출 사용자 예약 | DTO 변환 위치, 도메인 예외와 웹 표현 책임 분리 | [1~3단계](https://github.com/woowacourse/spring-roomescape-member/pull/186) · [4~6단계](https://github.com/woowacourse/spring-roomescape-member/pull/323) |
| 방탈출 예약 대기 | 지연 로딩과 fetch join으로 불필요한 쿼리 줄이기 | [1~2단계](https://github.com/woowacourse/spring-roomescape-waiting/pull/246) · [3~4단계](https://github.com/woowacourse/spring-roomescape-waiting/pull/286) |
| 방탈출 결제 배포 | 외부 PG 의존성 추상화와 운영 서버를 호출하지 않는 테스트 | [1단계](https://github.com/woowacourse/spring-roomescape-payment/pull/227) · [2~4단계](https://github.com/woowacourse/spring-roomescape-payment/pull/316) |

레벨 2 글쓰기: [나는 어떠한 사람인가](https://github.com/woowacourse/woowa-writing/pull/847)

## Level 3 · 팀 프로젝트

[물깜](https://github.com/woowacourse-teams/2025-mul-kkam): 수분 섭취를 기록하고 맞춤 알림을 보내는 앱. 팀 프로젝트로 Google Play 출시

## Level 4 (2025.09 ~ 2025.10)

| 미션 | 핵심 고민 | PR |
|-|-|-|
| Tomcat 구현 | Tomcat 동시성 처리 | [1단계](https://github.com/woowacourse/java-http/pull/874) · [2단계](https://github.com/woowacourse/java-http/pull/935) · [3단계](https://github.com/woowacourse/java-http/pull/1030) · [4단계](https://github.com/woowacourse/java-http/pull/1076) |
| @MVC 프레임워크 구현 | HandlerMapping, HandlerAdapter 기반 DispatcherServlet 리팩터링 | [1단계](https://github.com/woowacourse/java-mvc/pull/944) · [2단계](https://github.com/woowacourse/java-mvc/pull/1016) · [3단계](https://github.com/woowacourse/java-mvc/pull/1068) |
| JDBC 라이브러리 구현 | JDBC 트랜잭션 동기화 | [1단계](https://github.com/woowacourse/java-jdbc/pull/957) · [2단계](https://github.com/woowacourse/java-jdbc/pull/1081) · [3단계](https://github.com/woowacourse/java-jdbc/pull/1189) · [4단계](https://github.com/woowacourse/java-jdbc/pull/1248) |

테크니컬 라이팅: [FCM 대량 알림 처리 개선 트러블슈팅](https://github.com/woowacourse/woowa-writing/pull/1071)

테코톡: [FCM의 작동 흐름](https://www.youtube.com/watch?v=5og9G1Ib06w)

## Study

[트러블슈팅 스터디](https://github.com/woowacourse-study/2025-troubleshooting): 개발하면서 겪은 장애, 성능 개선, 새 기능 도입 시 시행착오를 발표하고 토론하는 스터디 (2025.07 ~, 발표 10회)
